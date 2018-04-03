node {
    stage 'Checkout'
    checkout scm

    stage 'Compile'
    sh "./gradlew compileJava"

    stage 'Test'
    sh "./gradlew test"

    stage 'Integration Test'
    sh "./gradlew integrationTest"

    stage 'Build'
    sh "./gradlew build"



}

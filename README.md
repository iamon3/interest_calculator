# interest_calculator
Sample Gradle Java Application

To init gralde java application from scratch (Skip this step. It is needed only for understanding purpose)

    mkdir interest_Calculator
    gradle init --type java-application
    
How to run the application?  2 ways are there. Both options are for linux env. First as mentioned below

    Download the project from github
    ./gradlew run
    
Second approach to run
    ./gradlew build
    cp build/lib/interest_calculator.jar ~/temp
    cd ~/temp
    java -jar interest_calculator.jar
    
Please note, to run on windows, use gradlew.bat instead gradlew
  

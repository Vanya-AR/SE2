pipeline { 
    agent any 
    stages { 
        stage('Compile') { 
DevOps Lab Manual 
 
SOAS, SNPSU                                                                                                                  2025-26 
 
            steps { 
                bat 'javac Hello.java' 
            } 
        } 
        stage('Run') { 
            steps { 
                bat 'java Hello' 
            } 
        } 
    } 
}

pipeline{

agent any
stages{


stage('build'){
 steps{
 sh '/usr/bin/mvn clean install'
 }
 }
 
stage('TEST'){
 steps{
 sh '/usr/bin/mvn clean test'
 }
 }





}
}

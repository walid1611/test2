pipeline{

agent any
stages{


stage('build'){
 steps{
 sh '/usr/bin/mnv clean install'
 }
 }
 
 stage('Test'){
 steps{
 sh '/usr/bin/mnv test'
 }
 }





}
}

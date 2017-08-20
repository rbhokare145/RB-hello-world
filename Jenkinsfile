pipeline {
 agent any
 stages {
 stage('BrowserTests') {
 parallel {
 stage('Chrome') {
 steps {
 echo “Chrome Tests”
 }
 }
 stage('Firefox') {
 steps {
 echo “Firefox Tests”
 }
 }
 }
 }
 }
}

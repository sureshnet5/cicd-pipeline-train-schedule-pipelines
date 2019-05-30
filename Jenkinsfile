pipeline
{
agent any
stage{
stage ('Build') {
steps {
echo 'running build automation'
sh './gradlew build --no-daemon'
archiveartifacts artifacts : 'dist/trainSchedule.zip.zip'
}
}
}
}

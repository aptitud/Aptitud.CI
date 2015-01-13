# Aptitud.CI
Simple gradle deploy script for jenkins on heroku

Make sure gradle.properties is updated with the heroku key to use


1. To deploy, update jenkins version in gradle.build and Procfile
2. git commit
3. gradle herokuAppDeploy

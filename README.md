make sure you are in the folder where file.jar is located

mvn deploy:deploy-file -Dfile=./file.jar -DgroupId=org.springframework.data -DartifactId=spring-data-rest-core -Dversion=1.1.0-KENNA -Dpackaging=jar -DcreateChecksum=true -Durl=file://{path of this project in your local fs}

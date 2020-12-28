# light-codegen-gradle
Light codegen with Gradle build tool

## How to build
./gradlew clean build

## How to use

java -jar codegen-cli-<version>-all.jar -f openapi -o /home/manhtv7/light-4j/light-example-4j/rest/openapi/petstore-gradle -m /home/manhtv7/light-4j/model-config/rest/openapi/petstore/1.0.0/openapi.yaml -c /home/manhtv7/light-4j/model-config/rest/openapi/petstore/1.0.0/config.json
-f: Framework

-o: Output directory

-m: Model directory

-c: Config
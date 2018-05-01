## Salesforce Spring Boot Rule for Bazel

This WORKSPACE contains the Spring Boot rule for the [Bazel](https://bazel.build/) build system.
It enables Bazel to build Spring Boot applications and package them as an executable jar file.

The rule is contained in a directory that is designed to be copied into your WORKSPACE.
It has detailed documentation:
- [bazel-springboot-rule](tools/springboot): a Bazel extension to build Spring Boot applications

pwd
/something/bazelspringboot-rul

## To Build the bazel file 

>bazel build //samples:samples


## To run the generated standalone springboot in port 8090

>java -jar bazel-out/darwin-fastbuild/genfiles/samples/samples_springboot.jar

## Check this out in the browser

> http://localhost:8090/greeting?name=Bazel
>>  {"id":2,"content":"Hello, Baze"}

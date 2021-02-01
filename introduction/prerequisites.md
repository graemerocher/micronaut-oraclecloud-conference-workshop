# Prerequisites

## Before We Begin

Prior to starting this workshop you should make sure you have the necessary software installed on your local machine.

The following software needs to be installed prior to commencing the workshop:

* [Micronaut 2.3.0](https://micronaut-projects.github.io/micronaut-starter/latest/guide/#installation)
* [GraalVM 21.0.0 for JDK 11](https://www.graalvm.org/docs/getting-started/#install-graalvm)
* [Docker](https://docs.docker.com/get-docker/)
* Terminal Access (If you are using Windows Cygwin or WSL)
* An IDE such as either [IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=mac) or [VSCode](https://code.visualstudio.com/download) with the [GraalVM Extension Pack](https://marketplace.visualstudio.com/items?itemName=oracle-labs-graalvm.graalvm-pack)

For easiest install it is recommended to install Micronaut and GraalVM via [SDKMan!](https://sdkman.io) with the following commands:

    <copy>
	sdk install micronaut 2.3.0
	sdk install java 21.0.0.r11-grl
	gu install native-image
	</copy>

If you have configured everything correctly your Terminal should output the following:

```bash
$ mn --version
Micronaut Version: 2.3.0

$ java -version
openjdk version "11.0.10" 2021-01-19
OpenJDK Runtime Environment GraalVM CE 21.0.0 (build 11.0.10+8-jvmci-21.0-b06)
OpenJDK 64-Bit Server VM GraalVM CE 21.0.0 (build 11.0.10+8-jvmci-21.0-b06, mixed mode, sharing)

$ native-image --version
GraalVM Version 21.0.0 (Java Version 11.0.10+8-jvmci-21.0-b06)
```

The final prerequisite is an Oracle Cloud account. The following sections takes you through the signup process. 

You may now *proceed to the next lab*.

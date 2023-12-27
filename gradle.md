## This file for basic setup of Gradle
## Gradle is a build tool for Java
1. It is used to automate the building, testing, publishing, deployment and more of software packages or other types of projects such as generated static websites, generated documentation or indeed anything else.

2. Gradle uses Groovy, a dynamic, object-oriented programming language for the Java platform to define the project and build scripts.

## How to install Gradle
1. Download the latest version of Gradle from https://gradle.org/releases/ (for windows, use the binary-only zip file)

2. Unzip the Gradle download to the folder to which you would like to install Gradle, eg. “C:\Program Files”. The subdirectory gradle-x.x will be created from the archive, where x.x is the version.

3. Update the PATH environment system variable for gradle bin directory presented inside the extracted folder.

4. In the command prompt window, run the following command to check if Gradle is installed correctly.

```bash
gradle -v
```
## We are using Gradle for simple java project in this repository
1. Inside project folder run the following command to create a gradle project

```bash
gradle init --type java-application
``` 

2. To see the list of tasks available to run, go to the project folder and run the following command
    ```bash
    gradle tasks
    ```

3. To build the project run the following command

```bash
gradle build
```

4. To run the project run the following command

```bash
gradle run
```

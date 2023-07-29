# smallMaven Project

The `smallMaven` project is a demonstration of the simplicity and power of Maven. It contains a Java application that utilizes a login method to take information from users. The project includes a resource file, a class for application logic, and test classes using JUnit for testing.

## Contents

- [What is a Maven Project?](#what-is-a-maven-project)
- [What is a Snapshot Java File?](#what-is-a-snapshot-java-file)
- [Project Purpose](#project-purpose)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Minimum Java Version](#minimum-java-version)

## What is a Maven Project?

A Maven project is a software project managed by the Apache Maven build automation tool. Maven provides a consistent and organized way to manage project dependencies, build, test, and deploy applications. It uses XML-based project object model (POM) files to define project settings, dependencies, and goals. With Maven, developers can easily build, test, and manage Java projects without worrying about complex build scripts.

## What is a Snapshot Java File?

In software development, a "Snapshot" generally refers to an interim version of a project that is still under active development and subject to changes. In the context of this `smallMaven` project, a "Snapshot Java File" is a version of the Java source code that is actively being developed and is not yet considered stable or final.

## Project Purpose

The purpose of the `smallMaven` project is to demonstrate the basic usage of Maven for managing a Java application. It includes a simple login method that takes user information and checks it against predefined values in the `config.properties` file.

## Project Structure

- `src/main/java/pac01/App.java`: Contains the main Java application class `App`, which includes the login method.
- `src/test/java/pac02/AppTest.java`: Contains JUnit test classes `AppTest` with two test methods to test the `login` method of the `App` class.
- `config.properties`: A resource file containing predefined username and password values.
- `pom.xml`: The Maven project configuration file defining dependencies and build settings.

## Dependencies

The `smallMaven` project uses JUnit for testing purposes. The JUnit dependency is declared in the `pom.xml` file, making it easy to run unit tests using Maven.

## Minimum Java Version

This project requires at least Java 7 (JRE 1.7) to compile and run correctly. The `pom.xml` file specifies the source and target compatibility settings to ensure compatibility with Java 7.


### How to Use the Snapshot File

1. **Download the Snapshot File**:

   - Go to the GitHub repository where the `smallMaven` project is hosted: [https://github.com/csstudent26/smallMaven](https://github.com/csstudent26/smallMaven).
   - Click on the file named `smallMaven-0.0.1-SNAPSHOT.jar` in the list of files.
   - On the file page, click the "Download" button to download the Snapshot file to your computer.
   - Once the file is downloaded, you can place it in a directory of your choice on your computer.

2. **Using the Snapshot File in an IDE**:

   To use the Snapshot file in an IDE like Eclipse or IntelliJ IDEA, follow these steps:

   - **Eclipse IDE**:

     - Open Eclipse IDE.
     - Create a new Java project in Eclipse.
     - Right-click on the project and select "Import."
     - Choose "General" and then "File System."
     - Browse to the directory where the downloaded Snapshot file is located.
     - Select the `smallMaven-0.0.1-SNAPSHOT.jar` file.
     - Click "Finish" to import the JAR file as a library in the project.

   - **IntelliJ IDEA**:

     - Open IntelliJ IDEA.
     - Create a new Java project in IntelliJ IDEA.
     - Go to "Open Module Settings."
     - In the "Dependencies" tab, click the "+" button and choose "JARs or directories."
     - Browse to the directory where the downloaded Snapshot file is located.
     - Select the `smallMaven-0.0.1-SNAPSHOT.jar` file.
     - Click "OK" to add the JAR file as a library in the project.

3. **Using the Classes in the Snapshot JAR**:

   Now you can use the classes contained in the Snapshot JAR within your own Java code. For example, you can create new instances of classes or call methods defined in the `smallMaven` project.

   It's important to note that the Snapshot file contains the project's interim version, and it may not be a stable or finalized version of the project.

---

Feel free to customize this `README.md` file further to include any additional details or context about your project. Users visiting your GitHub repository will now have instructions on how to download and use the Snapshot file in their preferred IDE for exploration and testing purposes.

If you have any other specific requirements or need further assistance, please let me know!




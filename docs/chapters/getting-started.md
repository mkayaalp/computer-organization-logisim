---
title: Getting Started with Logisim
layout: default
---

Logisim is a Java program.
Therefore the first step is ensuring a Java Runtime Environment is installed properly.
If so, you can [download Logisim](#download-logisim),
and then [open the beginner's tutorial](#open-the-beginners-tutorial).

## Java Installation

### Check if Java is already installed
Easiest way is to run Command Prompt (in Windows) or Terminal (macOS/Linux) and execute the following command:

    java -version

#### Java is not installed
If you see the following (in Windows):

    'java' is not recognized as an internal or external command, operable program or batch file.

Or the following (in macOS/Linux):

    -bash: java: command not found

it means that Java is not installed.

#### Java version is not 11 or greater
If you see the following:

    java version "1.8.0_181"
    Java(TM) SE Runtime Environment (build 1.8.0_181-b13)
    Java HotSpot(TM) 64-Bit Server VM (build 25.181-b13, mixed mode)

Or something similar, for example:

    openjdk version "1.8.0_232"
    OpenJDK Runtime Environment (AdoptOpenJDK)(build 1.8.0_232-b09)
    OpenJDK 64-Bit Server VM (AdoptOpenJDK)(build 25.232-b09, mixed mode)

It means you have Java 8 (the number above after "1." is the short name for Java version),
which does not support the program we use in this course.

### Install Java

#### JRE vs. JDK
The Java program needed to run Java applications is distributed in JRE (Java Runtime Environment).
The Java compiler and libraries needed to build Java applications is distributed as JDK (Java Development Kit).
The JDK includes the JRE.

You only need the JRE for running Logisim, which is a lot smaller than JDK
(Installer: JRE: 30-40 MB, JDK: 200MB, On disk: JRE: 120 MB, JDK: 330MB).

#### Option 1: Install the JDK
 Go to [adoptopenjdk.net](https://adoptopenjdk.net) and install the OpenJDK 16 (Latest) build (with HotSpot JVM).
The blue download button will download the installer for JDK (which, again, includes the JRE).
Run the installer file (.msi in Windows, .pkg in macOS) and follow the steps.
For Linux, you might download a tarball (.tar.gz file)
and need to follow the additional instructions in
[adoptopenjdk.net/installation.html](https://adoptopenjdk.net/installation.html).

#### Option 2: Install the JRE
Go to [adoptopenjdk.net](https://adoptopenjdk.net) and click on the "Other platforms" button.
Select your Operating System, and select "x64" as the architecture (aarch64 for newer Macs).
Find the download button for a JRE installer/tarball (.msi in Windows, .pkg in macOS, .tar.gz in Linux).
In Windows or macOS, run the installer file and follow the steps.
For Linux, follow the additional instructions in 
[adoptopenjdk.net/installation.html](https://adoptopenjdk.net/installation.html).

### Verify that Java is working
Repeat the first step above to check that your Java installation is working.
This time, you should see a message like this:

    openjdk version "16.0.1" 2021-04-20
    OpenJDK Runtime Environment AdoptOpenJDK-16.0.1+9 (build 16.0.1+9)
    OpenJDK 64-Bit Server VM AdoptOpenJDK-16.0.1+9 (build 16.0.1+9, mixed mode, sharing)

## Download Logisim

You can download the latest version from the following link:

[https://github.com/logisim-evolution/logisim-evolution/releases/latest](https://github.com/logisim-evolution/logisim-evolution/releases/latest)

You can select the installer for your system:
`.msi` for Windows, `.dmg` for macOS,
`.deb` for Debian/Ubuntu, and `.rpm` for RHEL/Fedora.
The installer should create links for running the application as usual.

You can also download the JAR file, which can be used on any platform without installation.

### Running the JAR file

Usually, when Java is installed, you can directly open JAR files as Java applications.
In case it does not work, you can run it from the Command Prompt/Terminal.

First, change the current directory to where the downloaded file is stored.
For example, in Windows you might switch to
the "Downloads" directory under your username (e.g. `mkayaalp`):

    cd c:\Users\mkayaalp\Downloads

In macOS/Linux, you can use the following:

    cd ~/Downloads

You can then run the application with the following command:

    java -jar logisim-evolution.jar

## Open the Beginner's Tutorial

The Logisim application has a nice tutorial you can follow.
Find it under `Help -> Tutorial` menu.
Go through Steps 0 through 5 to learn how the program works.

# JWS - Java Windows Service Template

Welcome to JWS, a template for a Java project designed to run as a Windows Service.

## Introduction

JWS provides a convenient starting point for developing Java applications that need to run as Windows Services. It includes a sample project structure and configuration files to help you quickly set up your own service.

## Getting Started

### Clone the Repository

Clone this repository to your local machine using the following command:

```
git clone https://github.com/your-username/JWS.git
```

### Set JDK in JWS.xml:
Open the JWS.xml file located in the root directory of the project. Inside the <executable> tag, specify the path to your JDK installation.

### Install the Service:
Open a command prompt (cmd) and navigate to the root directory of the project. Run the following command to install the service:

```
JWS.exe install
```

## Usage
Once the service is installed, you can start, stop, or uninstall it using the following commands:

Start Service:
```
JWS.exe start
```

Stop Service:
```
JWS.exe stop
```

Uninstall Service:
```
JWS.exe uninstall
```

## Configuration
You can customize the behavior of your service by modifying the JWS.xml file. This file contains configuration options such as service name, description, and startup type.
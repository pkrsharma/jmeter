# jmeter
Create a load testing of API using Jmeter

# JMeter Load Testing Setup

This README file provides instructions on how to set up and run load tests using Apache JMeter with the provided `example.jmx` file. You can update the JMX file as per your requirements for different load test scenarios.

## Prerequisites

### Java
Make sure you have Java (JDK) installed on your machine. You can download it from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) or [OpenJDK](https://openjdk.java.net/install/).

Verify Java installation:
```sh
java -version
```

You should see the installed version of Java.

## Setup Instructions
### Step 1: Verify Java Installation
Open a terminal or command prompt and run the following command to verify that Java is installed:


Apache JMeter
Download and install Apache JMeter from [here](https://jmeter.apache.org/download_jmeter.cgi)

### Step 2: Download and Install Apache JMeter
1. Go to the [Apache JMeter download page](https://jmeter.apache.org/download_jmeter.cgi).
2. Download the binary release (e.g., apache-jmeter-5.x.zip).
3. Extract the downloaded ZIP file to a preferred location on your machine.

## Updating the JMX File

1. Open the example.jmx file in JMeter GUI mode:
```
./jmeter
```

2. Go to File -> Open and select the example.jmx file.
3. Make the necessary changes to the test plan (e.g., updating thread groups, adding samplers, etc.).
4. save your changes to the JMX file by going to File -> Save.

# OR

### Step 1: Place the JMX File
Copy the `example.jmx` file to the bin directory of your JMeter installation:

```
cp /path/to/example.jmx /path/to/jmeter/bin/
```
### Step 2: Running the Load Test
1. Open a terminal or command prompt.
2. Navigate to the bin directory of your JMeter installation:
```
cd /path/to/jmeter/bin
```
3. Run JMeter in non-GUI mode using the provided JMX file:
```
./jmeter -n -t example.jmx -l results.jtl
```



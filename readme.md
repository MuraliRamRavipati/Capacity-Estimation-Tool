## Description.

This repository presents a simple capacity / load testing tool for web servers. The Project is built using Gradle Java.

Refer to the CS_525_Stress_Testing.pdf for details on a sample experiment and results.

--------------------------------------------------------------------------------------------------------------------------------------------

## Installing Dependencies

All the instructions for installing the depencies is included in "project-setup-instructions.md" file

--------------------------------------------------------------------------------------------------------------------------------------------

## Running the Experiment


For Each Run the following variables could be configured.

    // UserContext.java file
    public static final int NUM_OF_USERS = 100; //total number of virtual users.
    public static final int SPAWN_RATE = 10; // number of new users per Spawn gap.
    public static final int SPAWN_GAP = 3500; // spawn gap between new users addition.

    // ApiContext.java
    public static final int MAX_TIMEOUT_MS = 5000; // time out in milliseconds.


After installing all the required dependencies running the following steps to run the experiment.

1. Go into web-server folder and start the server

Command: node server.js

2. Make sure mongodb is running in the local

3. once step 1 and 2 is done run the stress-testing java tool using intellij.

Run StressTestMain.java class in the intellij and the stress testing tool.


--------------------------------------------------------------------------------------------------------------------------------------------

## Generating Graphs

For generating the resultb graphs the instructions in the file "generating-graphs.md" file could be followed.


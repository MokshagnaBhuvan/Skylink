# Skylink
A simple Remote Desktop Control Protocol using JAVA OOPS

# Remote Desktop Server

This project implements a simple remote desktop server application in Java using Swing and sockets. It allows clients to connect and view their desktop screens remotely, as well as send mouse and keyboard events to control their screens.

## Features

- Allows multiple clients to connect simultaneously
- Captures screenshots from clients and displays them on the server GUI
- Sends mouse and keyboard events to control client screens

## Prerequisites

- Java Development Kit (JDK) installed on your system
- Git installed on your system (optional, if you want to clone the repository)

## Getting Started

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/remote-desktop-server.git
    ```

2. Compile the Java files:

    ```bash
    javac *.java
    ```

3. Run the ServerMain class:

    ```bash
    java ServerMain
    ```

4. When prompted, enter the listening port for the server.

5. Clients can now connect to the server using the specified port.

## Usage

- Run the server and provide the listening port.
- Clients should run the corresponding client application to connect to the server.
- Use the server GUI to view client screens and control them using mouse and keyboard events.




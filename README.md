# Arduino-HTTP-TTY-TCL
A web and telnet server with support for user sessions and TCL scripting

This project is aimed at the WeMos D1 Arduino compatible board based on the ESP8266 chip and includes integrated WiFi functionality. An SD Card shield module will be used to provide a filesystem to store data files used by the Arduino at runtime.

The initial goal is to allow access to a TCL shell via the Arduino IDE USB terminal.

The next step is to add a Telnet server to allow remote wireless access, for configuration and control of the Arduino project.

The third step is to build further to provide a Web-based Graphical User Interface allowing the Arduino project to be more user-friendly, and also allowing the possibility of upgrading the TCL portion of the code without removing the Arduino board from its installed location.

A simple Access Control system will be provided allowing named users, or groups of users, to be assigned permissions to folders on the SD Card. It is assumed that any projects using this code will provide sufficient security to prevent physical access and tampering with the SD Card.

The MIT Licence was chosen here, as it matches that used by the [ParTcl](https://github.com/zserge/partcl) project, which I expect to borrow some ideas from.

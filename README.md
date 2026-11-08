# Firewall Management System

This project is a Firewall Management System developed in C++ using Object-Oriented Programming (OOP) concepts. The main purpose of this project is to control network traffic by allowing or blocking connections based on certain rules.

When the program starts, a menu will appear with options to add, view, or delete firewall rules, check network traffic, and view history. The user can create rules by entering an IP address, port number, protocol, and action (Allow or Block).

File Handling keeps data saved even after the program closes. Firewall rules and traffic logs are saved to external files so they automatically load when the program restarts, keeping a permanent history of network activity.

When a network request is entered, the system will check it against the saved rules and decide whether to allow or block it. It will also keep a record of previous requests.

In this project, we will use OOP concepts like classes, objects, inheritance and file handling.  The main goal is to understand the basic working of a firewall while improving our C++ and OOP programming skills.
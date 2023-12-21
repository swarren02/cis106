---
name: Seth Warren
Course: Cis106
Semester: Fall 2023
---

# Deliverable 1

> Tutorial can be found [here] (https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-22-04)

## Concepts I don't understand:

* Web server:
* Apache: Apache is available within Ubuntu’s default software repositories, making it possible to install it using conventional package management tools.
* Firewall
* systemd


## What is a web server? Hardware and software slides
a web server is a computer that stores web server software and a website's component files (for example, HTML documents, images, CSS stylesheets, and JavaScript files). A web server connects to the Internet and supports physical data interchange with other devices connected to the web.On the software side, a web server includes several parts that control how web users access hosted files. At a minimum, this is an HTTP server.

## What are some different web server applications?
## NGINX
Released as a project in 2002 by a Russian engineer who got fed up with the then-present solutions' inability to beat the CK10 problem. It's still popularly used today with its improvements that compete with Apache. Some of those improvements are Asynchronous architecture for handling high loads, Best-in-the-class static file handling, load balancing, and reverse proxy capabilities and FastCGI caching
## Caddy
Caddy is one of the popular new frameworks making splashes in the open-source community. Its similar to NGINX but everything is simplified to a pleasant extreme. For example it Let's Encrypt integration for SSL can be done in a mere three lines of coding
## Lighthttpd
Lighthttpd was designed to overcome challenges in low-memory and low CPU environments. Built on the asynchronous request handling model, and so essentially mirrors how Nginx works but, works in a single thread, so if you have a more capable machine, its going to ignore other CPU cores.
## Cherokee
Cherokee started as a personal itch of a developer, which has grown into a decent web server platform. While it doesn't have cutting-edge features like NGINX's, it does provide an easy, fun and performant alternative to the mainstream web servers. Very simplistic with the command line for configuring the server.
## What is virtualization?
Is technology that you can use to create virtual representations of servers,storage,networks and other physical machines
## What is virtualbox?
VirtualBox is a tool for virtualizing x86 and AMD64/Intel64 computing architecture, enabling users to deploy desktops, servers, and operating systems as virtual machines.
## What is a virtual machine?
A virtual machine is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual "guest" machines run on a physical "host" machine.
## What is Ubuntu Server?
Ubuntu Server is an addition to the larger set of Ubuntu products and operating system, it facilitates installations on servers.
## What is a Firewall?
A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predetermined security roles.
## What is SSH?
SSH is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network. It also provides strong password authentication and public key authentication, as well as encrypted data communications between two computers connecting over an open network like the the internet.
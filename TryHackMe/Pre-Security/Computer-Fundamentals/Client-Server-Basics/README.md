# Client-Server Basics

## Overview

This room introduces the client-server model and the terminology used when computers communicate with each other. It uses a pizza delivery analogy to explain how clients, servers, requests, responses, protocols, ports and DNS work. A practical lab then demonstrates how HTTP GET requests and server responses work when accessing a website.

---

## Learning Objectives

- Understand how the client-server model works.
- Understand the difference between a client and a server.
- Understand the purpose of DNS, ports, protocols and networks.
- Understand how HTTP requests and responses work.
- Identify the main parts of a URL.

---

## Key Concepts

### Client

A client is a device or application that requests a service from a server.

Example: A web browser requesting a webpage.

### Server

A server provides services or resources to a client in response to a request.

### Request and Response

The client sends a request to the server. The server processes the request and sends a response back.

### Protocol

A protocol is a set of rules that defines how computers communicate with each other.

### Port

A port identifies a specific service running on a computer.

### DNS

DNS (Domain Name System) translates a domain name into an IP address so that the client can locate the server.

### HTTP

HTTP is a protocol used for communication between web browsers and web servers.

### GET

GET is an HTTP method used to request a resource from a server.

### URL Structure

Example:

https://google.com/cybersecurity
- Scheme: `https`
- Host: `www.google.com`
- Path: `/cybersecurity`

### HTTP Response

A response from a server contains information such as:

- Status code
- Response headers
- Response body

For example, `200 OK` indicates that the request was successful.

---

## Practical Activities

- Started the TryHackMe virtual lab machine.
- Opened the provided website using Firefox.
- Opened Firefox Developer Tools.
- Used the Network tab to inspect network traffic.
- Reloaded the webpage and examined the GET requests.
- Inspected the request and server response.
- Identified information such as the scheme, host, filename, IP address and status code.

---

## **Screenshots**

<img width="1916" height="907" alt="image" src="https://github.com/user-attachments/assets/775c8893-4609-42b5-8849-aa23d4b0cadc" />


---

## Challenges Encountered

I did not encounter any significant technical difficulties during this room. The pizza analogy helped me understand the relationship between clients, servers, requests and responses.

---

## Key Takeaways

- The client initiates a request, and the server responds.
- DNS translates domain names into IP addresses.
- Ports identify specific services.
- Protocols define how computers communicate.
- HTTP allows web clients and servers to communicate.
- GET requests are used to retrieve resources from a server.

---

## Reflection

I understood some of the basic concepts from previous computing studies, but this room helped me connect them in the context of networking. The practical activity using Firefox Developer Tools was particularly useful because I could see an actual GET request and server response rather than only learning the theory.

Understanding how clients, servers, DNS, ports and HTTP work provides an important foundation for cybersecurity, as security professionals need to understand how network communication normally works before they can identify abnormal or malicious activity.

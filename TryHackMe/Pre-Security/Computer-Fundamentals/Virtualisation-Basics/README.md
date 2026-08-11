# **Virtualisation Basics**

## Overview

This room introduces virtualisation and explains how multiple virtual computers can share the resources of a single physical server. It covers the problems with using one physical server for each application, the role of hypervisors and virtual machines, the differences between Type 1 and Type 2 hypervisors, and how containers provide a lightweight alternative for running applications.

The practical activity involved managing virtual machines and analysing the hardware usage of physical hosts.

---

## Learning Objectives

- Understand why managing applications on individual physical servers is inefficient.
- Understand how virtualisation improves hardware utilisation and scalability.
- Understand the components and purpose of a virtual machine.
- Understand the role of a hypervisor.
- Distinguish between Type 1 and Type 2 hypervisors.
- Understand how containers improve hardware utilisation for applications.

---

## Key Concepts

- **Type 1 Hypervisor** – Runs directly on physical hardware, making it suitable for professional environments such as servers and data centres.
- **Type 2 Hypervisor** – Runs on top of an existing operating system, making it easier to set up and suitable for learning, testing and smaller environments.
- **Hypervisor** – Software that creates and manages virtual machines and allocates resources such as the CPU, memory, and storage.
- **Container** – An isolated environment for running an application and its dependencies. Containers share the host operating system's kernel, making them lightweight and efficient.
- **Virtual Machine (VM)** – A virtual computer that uses the physical hardware resources of a host machine while operating as an independent system.

---

## Practical Activities

- Used the Virtualisation Manager to monitor virtual machines.
- Identified a VM that had entered an error state and restarted it.
- Created a new virtual machine with specified CPU, memory and storage resources.
- Analysed the hardware usage of physical hosts.

---

## **Screenshots**

<img width="1905" height="908" alt="image" src="https://github.com/user-attachments/assets/bdebf408-90c9-40db-9d4c-5af24d91b943" />



---

## Challenges Encountered

A challenge I encountered was identifying specific problems within the virtual machines quickly. It took me some time to determine what was causing the issue and what action was required to resolve it.

---

## Key Takeaways

- Virtualisation allows multiple virtual machines to share the resources of one physical machine.
- Hypervisors manage virtual machines and their allocated resources.
- Type 1 hypervisors run directly on hardware, while Type 2 hypervisors run through an existing operating system.
- Containers provide a lightweight way to run applications while sharing the host's kernel.
- Virtualisation improves resource utilisation, scalability and flexibility.

---

## Reflection

This room helped me understand how virtualisation allows multiple independent systems to operate using the resources of a single physical machine. I learned the difference between Type 1 and Type 2 hypervisors, how virtual machines are managed, and how containers provide a more lightweight way of running applications.

The practical activity also helped me understand how virtual environments can be monitored and managed, rather than just learning about them in theory.

Virtualisation is important in cybersecurity because it allows security professionals to create isolated environments for testing, investigation and learning. For example, a virtual machine can be used to run Linux or cybersecurity tools without installing them directly on the main operating system. Understanding virtualisation will therefore be useful when I create my own cybersecurity lab and practise security techniques in a controlled environment.

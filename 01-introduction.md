# 1.0 Introduction

System hacking is a process of identifying and exploiting security weaknesses in a computer system to gain unauthorized access or higher privileges. It involves several stages, including reconnaissance, scanning, gaining access, privilege escalation, maintaining access and covering tracks.
For this practical assignment, the Bluemoon (2021) vulnerable virtual machine was used as the target system. Kali Linux was used as the penetration testing machine to perform security testing and identify vulnerabilities.
The main purpose of this practical exercise was to understand how attackers discover vulnerabilities, obtain access to a target system, and exploit misconfigurations that may allow privilege escalation.
All testing was conducted within an isolated VirtualBox Host-Only network to ensure that the activities did not affect external networks or other devices.

# 1.1 Objective

The objectives of this practical exercise are:
1.	To set up Kali Linux and the Bluemoon vulnerable machine using Oracle VirtualBox.
2.	To configure an isolated Host-Only network for communication between both virtual machines.
3.	To perform reconnaissance and scanning to identify open ports and services.
4.	To identify hidden information and discover credentials from the target machine.
5.	To gain initial access to the target machine through SSH.
6.	To investigate privilege escalation from the Robin account to the Jerry account.
7.	To identify Docker misconfigurations that could expose the host filesystem.
8.	To understand maintaining access and clearing tracks from a security perspective.
9.	To document the findings and recommend appropriate security improvements.

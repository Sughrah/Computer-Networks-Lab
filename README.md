📘 Computer Networks — README
📖 Introduction

Computer Networks is a field of computer science that studies how computers and devices communicate, share data, and use resources through interconnected systems. A network enables devices to exchange information using standardized rules called protocols.

This project/lab focuses on understanding networking fundamentals, device configuration, and practical implementation using Cisco Packet Tracer.

🎯 Objectives
Understand basic networking concepts and terminology
Learn about network devices such as routers and switches
Understand CLI configuration of routers
Learn IP addressing and communication between devices
Practice networking using simulation tools
🌐 What is a Network?

A network is a collection of computers and devices connected together to share data and resources.

Types of Networks
LAN (Local Area Network) – Small area (lab, home, office)
MAN (Metropolitan Area Network) – City-level network
WAN (Wide Area Network) – Large geographic area (country/world)
🧩 Network Devices
Device	Purpose
Router	Connects different networks and routes data
Switch	Connects devices within the same network
Hub	Broadcasts data to all devices
Access Point	Provides wireless connectivity
PC/End Device	Sends and receives data
🖥️ CLI Configuration Concept

Network devices are configured using CLI (Command Line Interface) because it provides more control than GUI.

Cisco IOS Modes
Mode	Prompt	Use
User EXEC	>	Basic commands
Privileged EXEC	#	Advanced commands
Global Config	(config)#	Configuration
🔐 Basic Security Configuration

To secure a router:

enable password — sets basic password
enable secret — sets encrypted password
service password-encryption — encrypts all passwords
💾 Configuration Files
File	Stored In	Command
Running Config	RAM	show running-config
Startup Config	NVRAM	show startup-config

To save configuration:

copy running-config startup-config
🌍 IP Addressing

An IP address uniquely identifies a device in a network.

Example: 192.168.1.1

Network ID
Host ID
🧪 Simulation Tool

All practical tasks are performed using Cisco Packet Tracer, which simulates real networking devices and allows safe practice without physical hardware.

🧠 Learning Outcomes

After completing this lab/project, students can:

Configure routers using CLI
Understand networking modes and commands
Apply security settings
Save and verify configurations
Understand how devices communicate in a network
📌 Conclusion

This Computer Networks lab provides practical exposure to real-world networking concepts. By using Cisco Packet Tracer and learning CLI configuration, students gain hands-on experience essential for networking and cybersecurity fields.

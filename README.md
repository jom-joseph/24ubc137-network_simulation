# Static and Dynamic Routing – Exploration & Verification

## Overview

This repository contains my lab work for the **Static and Dynamic Routing – Exploration & Verification** assignment.

The purpose of this lab was to understand how routers make forwarding decisions by configuring and testing both static and dynamic routing. The experiment compares manual routing configuration with protocol-based routing and analyzes their behavior under normal and failure conditions.

---

## Objectives

* Understand how routers learn about remote networks
* Configure and verify static routing
* Configure and verify dynamic routing
* Observe routing table changes
* Analyze behavior during link failures
* Compare static and dynamic routing practically

---

## Conceptual Understanding

The report includes explanations on:

* What it means to manually configure a route
* Why static routing feels predictable but fragile
* Where static routing is suitable
* How dynamic routing allows routers to learn
* Why dynamic routing protocols exist
* Comparison between static and dynamic routing

---

## Part B – Static Routing Lab

Topology:

* 2 Routers
* 2 LANs (each on different IP networks)
* End devices on both sides

Tasks Performed:

* Assigned IP addresses to router interfaces and PCs
* Verified PCs could ping their own gateway
* Configured static routes on both routers
* Verified end-to-end connectivity
* Observed routing tables before and after configuration
* Tested behavior after removing static routes

---

## Part C – Dynamic Routing Lab

Topology:

* Minimum 3 Routers
* Multiple interconnected networks

Tasks Performed:

* Enabled a dynamic routing protocol (RIP / OSPF)
* Advertised all relevant networks
* Verified automatic route learning
* Confirmed end-to-end connectivity
* Simulated link failure
* Observed routing table updates
* Verified automatic recovery after restoring the link

---

## Failure Observation

This lab clearly shows the difference between the two approaches:

* Static routing does not automatically adapt to failures
* Dynamic routing detects failures and reroutes traffic automatically

Screenshots of routing tables and ping results are included in the report.

---

## Repository Structure

NetworkSimLab-YourName/
├── OSI_Wireshark_Lab/
├── Routing_Lab/
│   ├── Screenshots/
│   ├── Static_Dynamic_Routing_Report.pdf
└── README.md

---

## Documentation

The PDF report contains:

* Conceptual explanations
* Topology diagrams (GNS3 screenshots)
* Routing tables (before configuration, after static routing, after dynamic routing, after link failure)
* Ping results proving connectivity
* Final reflection on routing behavior

---

## Key Learning Outcome

After completing this lab, I understood that routing is not just about forwarding packets. It is about decision-making, adaptability, and control within a network.

Static routing provides simplicity and control in small environments, while dynamic routing offers scalability and resilience in larger and changing networks.

---

## Author

Jom Joseph
Networking Lab Assignment

---


---

copyright:
  years: 2024
lastupdated: "2024-01-12"

subcollection: pattern-sap-on-powervs
keywords:

content-type: Objective and Overview
---
{{site.data.keyword.attribute-definition-list}}


# Overview
{: #overview}

The objective of this document is to provide an IBM Solution Design for the deployment of SAP on IBM Power Virtual Server (PowerVS) to:

•	Accelerate and simplify solution design by providing a standard IBM Cloud deployment architecture reference solution for SAP on IBM PowerVS  enterprise-class deployments following the IBM Architecture Framework. [IBM Architecture Framework](/docs/architecture-framework?topic=architecture-framework-intro).
•	Provide a prescriptive, end-2-end enterprise-class solution design, with diagrams, component architecture decisions along with rationale for cloud component selection for a secure, resilient SAP on PowerVS deployment.
•	Ensure requirements can be met from performance, system availability and security perspectives.

This document does not cover SAP configuration and SAP component deployment scenarios, it is limited to IBM cloud infrastructure options to support SAP workloads.

Enterprise-class, mission critical workloads need to be secure, resilient and provide disaster recovery (DR) capabilities and high availability (HA).  This pattern can be used as a guide to meet typical customer requirements and provide a base reference solution for a secure and resilient SAP NetWeaver/HANA or SAP NetWeaver/AnyDB deployment on IBM Power Virtual Server.

It describes the deployment of SAP Business Applications Running on SAP NetWeaver, SAP HANA or AnyDB and other SAP products using other technologies (SAP Content Server, or newer applications such as SAP Data Intelligence).

IBM Cloud SAP-Certified Infrastructure provides the flexibility to run SAP workloads in the IBM Cloud and the ability to quickly address issues such as:

- Moving SAP workloads to the cloud

- Rapidly expanding or contracting capacity

- Supplementing an existing private cloud architecture

- Disaster Recovery for on-premise workloads

Enterprise-class, mission critical workloads need to be resilient and provide disaster recovery (DR) capabilities and high availability (HA).  This pattern illustrates a Single-Zone, Multi-Region design deployed to IBM Power Virtual Server, which can provide both DR and HA to provide 99.95 infrastructure availability for an SAP NetWeaver/HANA or SAP NetWeaver/AnyDB solution to meet typical customer requirements.

The following documentation provides design considerations and architecture decisions for deploying the IBM Cloud resources to support SAP existing (migration) or new workloads, including SAP S/4HANA, SAP BW/4HANA, and SAP NetWeaver application with AnyDB.

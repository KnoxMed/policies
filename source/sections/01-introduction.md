# 1. Introduction

KNOX Medical Diagnostics, Inc ("Aluna") is committed to ensuring the confidentiality, privacy, integrity, and availability of all electronic personal information it receives, maintains, processes and/or transmits on behalf of its Customers. Aluna strives to proactively address information security, mitigate risk for its Customers, and assure known breaches are completely and effectively communicated in a timely manner. The following documents address core policies used by Aluna to maintain compliance and assure the proper protections of infrastructure used to store, process, and transmit information for Aluna Customers. 

## 1.1 Aluna Mobile App and API backend

Aluna provides a secure **mobile app** with a cloud-based backend. Aluna makes every effort to reduce the risk of unauthorized disclosure, access, and/or breach of customer data through network (firewalls, dedicated IP spaces, etc) and server settings (encryption at rest and in transit).

## 1.2 Aluna Organizational Concepts

The physical infrastructure environment is hosted at [Amazon Web Services](https://aws.amazon.com/) (AWS). The network components and supporting network infrastructure are contained within the AWS infrastructures and managed by AWS. Aluna does not have physical access into the network components. The Aluna environment consists of Node.js application servers; and mongoDB database servers. Within the Aluna environment, all data transmission is encrypted and all hard drives are encrypted so data at rest is also encrypted; this applies to all servers. 

AWS Security Groups act as a virtual firewall to controll inbound and outbound traffic. AWS Security Groups are configured to restrict access to only justified ports and protocols. Aluna has implemented strict logical access controls so that only authorized personnel are given access to the internal management servers. The environment is configured so that data is transmitted from the load balancers to the application servers over a TLS encrypted session.

The application servers are externally facing and accessible via the Internet. The database servers, where the personal information resides, can only be accessed through a bastion host. Access to the internal database is restricted to a limited number of personnel and strictly controlled to only those personnel with a business-justified reason. 

## 1.3 Version Control

Refer to the GitHub repository at [https://github.com/KnoxMed/policies/](https://github.com/KnoxMed/policies/) for the full version history of these policies.

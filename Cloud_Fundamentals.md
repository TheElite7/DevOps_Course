# Cloud Computing Fundamentals

### Summary


## Introduction to Information Security within Cloud Computing.

**Summary**

> What is the cloud ?

1. SP-800-145 (The NIST Definition of Cloud Computing)
    * Four Deployment Models,
        * Private
        * Public
        * Community
        * Hybrid
    * Three Service Models
        * IaaS
        * PaaS
        * SaaS

2. ISO/IEC 17788 (Cloud computing - Overview and vocabulary)


* Cloud Controls Matrix (CCM)
    * Maps specific frameworks and regulations to cloud controls
    * Supports cooperation between cloud consumer and providers
    * Contained in a single document.
* CSA Enterprise Architecture
    * Business Operation Support Service (BOSS)
    * Information Technology Operations and Support (ITOS)
    * Application Presentaion information Infrastructure Service
    * Security and Risk management

---


### Hypervisor Virtualization

* The foundation of creation of virutal machines as guest OS that can consume hardware resources with the perception that they are the only system doing so.
* There are two of Hypervisor,
  * Type II
    * This Hypervisors are Virtualization of a guest OS in the form of an application or process.
    * These hypervisors predate the cloud and were used on desktops and servers to emulate environments on traditional OS being dozens of giabytes in size in support of necessary application environments.
  * Type I
     * This Hypervisores, also known as bare metal. are installed on as a kernal system on the harware as a very small form factory system measuring in size of megabytes to a few hundred kilobytes.
     * This is the hypervisor of the modern day cloud.
   
### Cloud Deployment Models
* Four Deployment Models,
     1. Private
        * Virtual Private is not a private cloud
        * The private cloud can be physically located at the organization's onsite data center or it can be hosted by a third-party provider
        * In a private cloud, the service and infrastructure are always maintained on a private network and the hardwate and software are dedicated solely to that single organization.
     2. Public
        * Most common deploy on the cloud.
        * The cloud resource are owned and operated by a third-party cloud service provider and delivered over the internet.
        * Example: Microsoft Azure, AWS, Google, Box, Salesfore
        * No maintenance and unlimited scallability
     3. Community
        * Multiple organization share the platform along with some common data or information with multiple and possibly disparate organizations that have an exclusive membership.
        * Characteristics of public/private cloud.
     4. Hybrid
         * Combination of two or more clouds.
         * Creates high elasticity

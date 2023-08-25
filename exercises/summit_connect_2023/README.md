# Demo: Summit Connect 2023

This demo focuses on the ACP and DCN architecture, where DCNs are provisioned and onboarded via FDO and Image Builder. From there, Greenboot functionaly is applied and tested to ensure DCN availability.

## TO-DO
Ignore everything below this line

## Table of Contents

- [Red Hat Device Edge - FDO Secure Onboarding and the Realtime Kernel](#red-hat-device-edge---fdo-secure-onboarding-and-the-realtime-kernel)
  - [Table of Contents](#table-of-contents)
  - [Presentations](#presentations)
  - [Time planning](#time-planning)
  - [Lab Diagram](#lab-diagram)
  - [Section 1 - Investigating the Lab Environment](#section-1---investigating-the-lab-environment)
  - [Section 2 - Creating an Image with the Realtime Kernel via the infra.osbuild Collection](#section-2---creating-an-image-with-the-realtime-kernel-via-the-infraosbuild-collection)
  - [Section 3 - Installing and Configuring FDO](#section-3---installing-and-configuring-fdo)
  - [Section 4 - Creating an Edge Simplified Installer Image via the Composer CLI](#section-4---creating-an-edge-simplified-installer-image-via-the-composer-cli)
  - [Section 5 - Imaging a Device as a Device Manufacturer](#section-5---imaging-a-device-as-a-device-manufacturer)
  - [Section 6 - Finishing Device Installation at their Final Destination](#section-6---finishing-device-installation-at-their-final-destination)
  - [Section 7 - Deploying an Application that Requires Deterministic Compute](#section-7---deploying-an-application-that-requires-deterministic-compute)
  - [Supplamental Resources](#supplamental-resources)
  - [Instructor Resources](#instructor-resources)

## Presentations

The exercises are self explanatory and guide the participants through the entire lab. All concepts are explained as they are introduced.

Have a look at a general deck about Red Hat's Edge strategy:
[Red Hat Edge Compute Platform](../../decks/rh_edge_compute_platform.pdf)

Also, have a look at our Ansible Best Practices Deck:
[Ansible Best Practices](../../decks/ansible_best_practices.pdf)

## Time planning

The time required to do the workshops strongly depends on multiple factors: the number of participants, how familiar those are with Linux in general and how much discussions are done in between.

Having said that, this workshop is built to take roughly 4 hours.

## Lab Diagram

![Lab Diagram](../../images/rhde_aw_120_lab_diagram.png)

## Section 1 - Investigating the Lab Environment

* [Exercise 1.1 - Preflight Checks](1.1-preflight)
* [Exercise 1.2 - Investigating Ansible Controller](1.2-controller-intro)
* [Exercise 1.3 - Investigating Source Control](1.3-source-control-intro)
* [Exercise 1.4 - Investigating Your Edge Device](1.4-device-intro)
* [Exercise 1.5 - Investigating the Example Workload](1.5-application-intro)
* [Exercise 1.6 - Gathering Networking Information](1.6-network-info)
* [Exercise 1.7 - Cloning Your Code Repository](1.7-coding-intro)
* [Exercise 1.8 - Getting Logged Into the Image Builder WebUI](1.8-image-builder-intro)

## Section 2 - Creating an Image with the Realtime Kernel via the infra.osbuild Collection

* [Exercise 2.1 - Reviewing the Workflow to Build Images](2.1-image-builder-workflow)
* [Exercise 2.2 - Reviewing Execution Environments](2.2-execution-environment-review)
* [Exercise 2.3 - Creating an Image Definition](2.3-image-definition-in-code)
* [Exercise 2.4 - Using the infra.osbuild Collection in a Playbook](2.4-using-collection-in-playbook)
* [Exercise 2.5 - Running Our Playbook through Controller](2.5-aap-image-build)

## Section 3 - Installing and Configuring FDO

* [Exercise 3.1 - Introduction to FDO](3.1-fdo-intro)
* [Exercise 3.2 - Installing and Configuring FDO](3.2-fdo-install-config)

## Section 4 - Creating an Edge Simplified Installer Image via the Composer CLI

* [Exercise 4.1 - Building a Blueprint](4.1-build-blueprint)
* [Exercise 4.2 - Starting a Compose via the Composer CLI](4.2-start-compose-cli)

## Section 5 - Imaging a Device as a Device Manufacturer

* [Exercise 5.1 - Imaging a Device as a Device Manufacturer](5.1-device-manufacturer-image)

## Section 6 - Finishing Device Installation at their Final Destination

* [Exercise 6.1 - Finishing the Process at the Device Destination](6.1-finish-install)
* [Exercise 6.1 - Adding out Host to an Inventory](6.2-add-host-to-inventory)

## Section 7 - Deploying an Application that Requires Deterministic Compute

* [Exercise 7.2 - Creating Automation to Deploy a Containerized Application](7.1-containerized-app-automation)
* [Exercise 7.3 - Deploying the Application via Ansible Controller](7.2-deploying-the-app)

## Supplamental Resources
* [infra.osbuild](https://github.com/redhat-cop/infra.osbuild)
* [redhat_cop.controller_configuration](https://github.com/redhat-cop/controller_configuration)

## Instructor Resources
* [Instructor Page](instructor)
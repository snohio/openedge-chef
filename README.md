# openedge-chef

## Background

This repository is for notes and other technical stuff to build a **cohort** between the Chef Architects and OpenEdge Engineering and Architects

## Team

Mike Butler
Edsel Garcia
Shelley Chase
Ravi Sankar
Ranga Reddy
Cameron Wright
Samir Khurana

## Goals

### Internal

- Understand the build package and deploy the ABL code.
- How can we automate the build / test with Chef.
  - ABL Code testing against a test environment.
  - Need to spin up that test environment.
- Understand Habitat as App Delivery model with underlying.
- Remove Ansible from Progress
- Reduce build time for pipeline
- CAPS team to look at this pipeline

### External

- Write a whitepaper on how customers can use this to build and deploy.
- Create Content for delivery (Chef Infra / Hab Plans)
  - Cookbook for managing Progress Desktop Studio
  - Cookbook for OpenEdge Server and components
- Reference implementation of Chef / test kitchen in Ci/Cd.

## Current technologies

LXC - LinuX Containers (Docker desktop like)
Vagrant

## Other Information

Customers have 1000 ABL developers (Latin Am.)
Most are 20 - 50.. Some 100.

## Actions

- [ ] Experiment with building the ABL Test Environment with Chef Cookbooks
- [ ] Demonstration of the Progress best practice CI/CD pipeline that they recommend for their customers.

## Meetings

- [ ] CAPS - How does the OpenEdge Code Development pipeline work. Is there a place for build and testing with Chef / Test Kitchen
- [ ] Pro 2 Team to demonstrate
- [ ] Setup recurring "office hours" to learn Chef and OpenEdge
- [ ] Bring Dan C. in for Internal Training discussions

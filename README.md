# Architecture-as-Code EA Models

This repository contains Enterprise Architecture models defined as code (AaC). 
It provides a single source of truth for Business, Application, and Technology layers 
and enables automatic generation of diagrams and stakeholder views.

## Repository Structure

- `models/` - declarative architecture models (no diagrams)
  - `business/`      → business capabilities, processes, value streams
  - `application/`   → applications, services, interfaces
  - `technology/`    → infrastructure, technology services, deployments

- `views/` - generated views and diagrams
  - `business/`
  - `application/`
  - `technology/`


## Purpose

- Provide a consistent, versioned Enterprise Architecture across domains
- Maintain traceable relationships between Business, Application, and Technology layers
- Enable automated generation of diagrams for stakeholders
- Serve as a foundation for governance, compliance, and strategic planning

## Notes

- Architecture models should always be updated declaratively in `models/`.
- Diagrams in `views/` are generated automatically and should not be edited manually.

---
layout: post
title: "Use Cases"
excerpt: ""
categories: wiki
tags: [ wiki ]

date: 2022-06-23T08:08:50-04:00

---

# Use cases for Project

* autonomous vehicle transport Infrastructur

# AVTI - Autonomous Vehicle Transport Infrastructure

* Entities
  * Vehicle
    * Battery Management
    * Sensor Telematics
    * Driver Profile
    * Self-driving
  * Charging Stall
    * Occupancy
    * Maintenance
    * Price Management
    * Route Optimisation
  * Route Map
  * Payment - income from Driver, expense to PowerProvider
  * ServiceCenter
  * Rent/Lease
  * Insurance
  * Recycle


* Backend Infra
  * Data
    * Flow
      * Kafka topics for logging
    * Storage
      * Postgres / SQLite for Driver Info
      * MongoDB for unstructured data
        * Camera Sensor information
  * Deployment
    * AWS
    * Github for code
    * GSM / Cellular  - Mock with Interfaces

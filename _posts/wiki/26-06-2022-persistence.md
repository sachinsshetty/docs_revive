---
layout: post
title: "Persistence"
excerpt: "Step by Step info to help in migration"
categories: wiki
tags: [ wiki ]

date: 2022-06-26T08:08:50-04:00

---


Persistance

    Using Hibernate JPA and Sping MVC - JPA Repository and model files automatically map to postgres database.
        Table , Sequence, Primary and Unique key constraints are handled in the POJO file
        Default values are passed as SQL on startup, kept in resources folder as data.sql , can also be mapped to Docker volume
        Current issue, it executes everytime, need to convert into PL/SQL to handle multilpe runs . Error is suppresed with config : spring.sql.init.continue-on-error=true

    Connect to psql : psql -h localhost -p 5432 -d revive_db -U revive_db

    Describe table : revive_db=> \d device;

    Show all tables : revive_db-> \dt

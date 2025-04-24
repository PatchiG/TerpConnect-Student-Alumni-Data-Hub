# TerpConnect Student Alumni Data Hub

## Overview
This project involved the design and implementation of a relational database for the Institute of Applied Agriculture (IAA) at the University of Maryland. The goal was to create a centralized system to efficiently manage data related to prospective students, current enrollees, and alumni. This system enhances recruitment, communication, and alumni engagement through a unified, query-friendly structure.

## Tools & Technologies
- **Database**: MySQL  
- **Data Modeling**: ERD (Entity Relationship Diagram)  
- **Mock Data Generation**: Mockaroo  
- **CRUD Operations**: SQL Queries and Stored Procedures

## Features
- **Data Integration**: Consolidated separate user types (prospective, current, alumni) into a unified `people` table for streamlined access and flexibility.
- **Views & Procedures**: Developed views and stored procedures to address common operational queries.
- **Use Cases Implemented**:
  - Identifying students currently enrolled vs. dropped out by major
  - Targeted alumni event invitations by location (e.g., Happy Hour in Texas)
  - Distribution list for INAG News based on user status and address validity
  - Communication tracking by event type and frequency
  - Aggregated listserv participation across user groups


## ERD Design
The final schema design emphasizes normalization, using linking tables to handle many-to-many relationships and minimizing data redundancy. The project also introduced a master address table to consolidate location data.

<img width="976" alt="ERD" src="https://github.com/user-attachments/assets/d3ee135f-3086-4de2-bd3f-fabaad7b7111" />

## Key Learnings
- The importance of scope control and using mock data to ensure privacy
- Real-world challenges in data cleaning, modeling, and maintaining referential integrity
- Value of feedback and iterative design to refine schema efficiency
- Effective use of CRUD operations to simulate actual use-case scenarios

## Challenges & Resolutions
- Merging multiple data sources while preserving data consistency
- Creating a unified "people" table structure from fragmented data sets
- Designing queries complex enough to meet academic and practical standards

## Future Improvements
- Explore NoSQL alternatives like MongoDB to handle unstructured data such as essays or course materials
- Implement features to support complex relationships, like student club memberships or advisor pairings
- Enhance scalability for high-concurrency environments

## References
- *Designing Data Intensive Applications* by Martin Kleppmann
- *Murach's MySQL* by Joel Murach
- Mockaroo (Mock Data Generator): [https://www.mockaroo.com/](https://www.mockaroo.com/)

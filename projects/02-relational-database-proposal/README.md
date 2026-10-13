# Relational database proposal

**IT 204 | Academic coursework | Private review draft**

An academic proposal for the fictional Birchwood Lane Schools to replace paper records with a relational database. The deliverable connects business requirements, data modeling and a staged implementation plan.

[Read the one-page PDF](case-study.pdf)

## Business problem

Paper-based student, instructor, course and enrollment records make updates, history tracking and reporting difficult. The proposal describes a more connected model with clear record ownership and access controls.

## Design work documented

- Defined stakeholders, reporting needs and the gap between the paper-based current state and a relational future state.
- Developed conceptual and logical models with primary keys, foreign keys and bridge tables for many-to-many relationships.
- Proposed eight tables: Student, Enrollment, Course, Instructor, Address, Student_Address, Instructor_Address and Course_Instructor.
- Recommended Microsoft SQL Server 2022 after considering usability, administration, cost, security and scalability in the assignment context.

## Key modeling decisions

Enrollment connects students and courses while retaining term, enrollment status and grade. Separate address relationships support multiple addresses. Course_Instructor records instructor assignments by term. These structures were designed to reduce repetition and preserve useful relationships.

## Proposed implementation

The plan covers data preparation and migration, required fields and relationship checks, role-based access, functional and permission testing, user training, launch monitoring, backups and maintenance. Budget, user counts, hosting, migration volume and schedule remain inputs for a real implementation.

## Scope and evidence

The source report contains model diagrams and an implementation plan. No SQL script, created database, executed query, tested migration or deployed system was available. This case demonstrates database design and planning; any implementation remains future work.

## Skills demonstrated

Relational modeling; requirements analysis; database evaluation; test planning.

## Source and attribution

Olga Solodovnikova, Database Proposal and Implementation Plan Report for Birchwood Lane Schools, IT 204, Southern New Hampshire University, June 2026. The report cites the course scenario, Jukic et al. and Microsoft documentation.

This is a new portfolio adaptation of the coursework, not the original assignment submission. See the [source register](../../SOURCES.md). Raw course data and assignment templates are not redistributed.

## Before sharing publicly

Locate editable model diagrams and any genuine SQL work. If a demonstration is built later, use clearly synthetic records and label it as a new extension rather than part of the original submission.

[Back to portfolio](../../README.md)

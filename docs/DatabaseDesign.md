# FreelancerOS - Database Design

## Overview

The FreelancerOS database is designed to manage freelancers, their clients, projects, and tasks.

---

# Entities

## User

Represents the freelancer using the application.

Fields:

- id
- fullName
- email
- password
- createdAt
- updatedAt

---

## Client

Represents a customer.

Fields:

- id
- userId
- name
- email
- phone
- company
- address
- notes
- createdAt

---

## Project

Represents work done for a client.

Fields:

- id
- clientId
- title
- description
- status
- startDate
- dueDate
- budget
- createdAt

---

## Task

Represents work inside a project.

Fields:

- id
- projectId
- title
- description
- priority
- status
- dueDate
- createdAt

---

# Relationships

One User
    ↓
Many Clients

One Client
    ↓
Many Projects

One Project
    ↓
Many Tasks

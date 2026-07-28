# FreelancerOS - API Design

## Base URL

/api/v1

---

# Authentication

## Register

POST /auth/register

## Login

POST /auth/login

## Logout

POST /auth/logout

## Current User

GET /auth/me

---

# Dashboard

GET /dashboard

---

# Clients

## Get All Clients

GET /clients

## Get Client By ID

GET /clients/:id

## Create Client

POST /clients

## Update Client

PUT /clients/:id

## Delete Client

DELETE /clients/:id

---

# Projects

GET /projects

GET /projects/:id

POST /projects

PUT /projects/:id

DELETE /projects/:id

---

# Tasks

GET /tasks

GET /tasks/:id

POST /tasks

PUT /tasks/:id

DELETE /tasks/:id

---

# Health Check

GET /health

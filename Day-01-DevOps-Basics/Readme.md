# Day 1 – DevOps Fundamentals

## Topics Covered

On Day 1, I learned the fundamentals of DevOps, CI/CD, version control,
Linux commands, and basic software architecture.

---

## 1. DevOps

DevOps is a software development methodology that improves collaboration
between development and operations teams using automation and various tools.

The main goal of DevOps is to automate and improve the software delivery
process.

### DevOps Lifecycle

The basic DevOps lifecycle covered was:

Plan → Code → Build → Test → Release → Deploy → Operate → Monitor

### Tools Mentioned

- Git / GitHub – Source code management
- Maven – Build automation
- Postman – API testing
- Jenkins / GitHub Actions – CI/CD automation
- Docker – Containerization
- Docker Scan – Security scanning
- Other DevOps tools can be integrated depending on the stage.

---

# 2. CI/CD Process

CI/CD stands for:

- CI – Continuous Integration
- CD – Continuous Delivery / Continuous Deployment

A typical CI/CD pipeline follows:

Code
↓
Commit
↓
Build
↓
Test
↓
Deploy

### Continuous Integration

In Continuous Integration, developers frequently integrate their code
changes into a shared repository.

The pipeline can automatically:

1. Build the application
2. Run tests
3. Check whether the code works correctly

### Continuous Delivery / Deployment

After successful testing, the application can move through environments
such as:

Review → Staging → Production

This helps automate software delivery and reduce manual work.

---

# 3. Automated CI/CD Pipeline

A basic automated CI/CD pipeline can be represented as:

Code
↓
Commit
↓
Build
↓
Unit Tests
↓
Integration Tests
↓
Review
↓
Staging
↓
Production

The purpose of CI/CD is to automatically validate and deliver software
whenever changes are made.

---

# 4. Source Code Management

Source Code Management (SCM) is used to track and manage changes made
to source code.

Git is a distributed version control system.

GitHub is a platform that provides repositories and collaboration
features for Git-based projects.

---

## Centralized Version Control System

In a centralized version control system, there is a central repository
from which developers obtain and update code.

Basic structure:

                Central Server
                Repository
               /     |      \
              /      |       \
        Working     Working    Working
         Copy        Copy       Copy
          PC #1       PC #2      PC #3

Developers work with copies of the code and synchronize changes with
the central repository.

---

## Distributed Version Control System

In a distributed version control system, developers have repositories
that can synchronize with a remote repository.

Basic structure:

                 Remote Repository
                  /      |      \
                pull    pull    pull
                 ↓       ↓       ↓
               Repo    Repo    Repo
                PC#1    PC#2    PC#3
                 ↓       ↓       ↓
              Working  Working  Working
               Copy     Copy     Copy

Git follows the distributed version control model.

---

# 5. Basic Git Commands

## Create a directory

```bash
mkdir project
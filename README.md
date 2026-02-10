OOP & Design Patterns (AIDAMS 2A)


Student: Pollux Gronier (B00822392)

Course: Object Oriented Programming & Design Patterns

Instructor: Benjamin Dallard

Date: February 2026


This repository tracks my progress in the AIDAMS 2A OOP module. The goal isn't just to write code that works, but to write clean, maintainable software, avoiding "crappy AI-generated stuff" by understanding the architecture behind it.

## Design Patterns Implemented
I refactored several "spaghetti code" scenarios into robust design patterns:

## Factory Pattern (Payment System):

Implemented a dynamic Registry system.

new payment types (Crypto, PayPal, etc.) without touching the core code (Open/Closed Principle).

## Builder Pattern (Employee Onboarding):

Immutable Dataclasses to prevent accidental data changes.

fluent API to build Employee profiles

## Singleton Pattern (Config Manager):

Ensures configuration files are loaded from disk only once.

Uses Dependency Injection to make testing easy.




## Git Reflection

1. Why is version control useful?

Version control helps track changes in a project. It allows you to go back to previous versions, fix mistakes, and work safely without losing code.

2. What is the difference between staging and committing?

Staging selects the changes that will be included in the next commit. Committing saves those staged changes permanently in the repository history.

3. When should you make a commit?

You should make a commit after completing a small, meaningful change, such as adding a feature or fixing a bug.

4. What is the difference between git init and git clone?

git init creates a new empty Git repository in a folder. git clone copies an existing repository from GitHub to your computer.

5. Why should you write good commit messages?

Good commit messages make it easy to understand what was changed and why, especially when reviewing project history later.

6. What is the purpose of using branches?

Branches allow you to work on new features or experiments without affecting the main branch.

7. When would you create a new branch instead of working on main?

You create a new branch when working on a new feature, testing ideas, or making changes that should not immediately affect the main branch.

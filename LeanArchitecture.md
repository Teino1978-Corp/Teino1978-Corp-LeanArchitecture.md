# Subdivision

## What the system is (User Thinking)

+ Classes & Objects
+ Domain Experts
+ Architects
+ Database schemas
+ Long-term stable structure
+ Form

## What the system does (User doing)

+ Roles, identifiers, activation records
+ End Users
+ User experience people
+ Interface Designers
+ Ever-changing functions on this page
+ Function

# Definition of a problem

+ Documented and known.
+ It describes the difference between the current state and the required.
+ Solving the problem must be measurable.
+ Quick, clear SYMPTOMS in natural language.
+ The definition must be consistent.

Note

+ Who "owns" the problem?
+ Feature Creeping
+ Respect for solutions in disguise of problems ...

## Acronym SMART

+ * S * Specific
+ * M * Measurable
+ * A * Attainable
+ * R * Relevant
+ * T * Time-bound

## Acronym INVEST

+ * I * Independent
+ * N * Negotiable
+ * V * Valuable
+ * E * estimable
+ * S * Appropriately Sized / Small
+ * T * TestableSafety

## Problem Analysis

+ * The Five Ws * It is so long in demand until the cause of the problem is clear.
+ * Ishikawa diagram * Ishikawa diagram to represent causality relations.

# What the system is

+ Architecture is more than form structure
+ Architecture is more compression than abstraction
+ Architecture has static and dynamic components
+ Architecture concerns everyone (developers) what
+ Much of the architecture is not designed to solve user problems
+ Architecture should not be hard

## Splitting

### Domain versus behavior

* 1 * on the form ("What the system is") without focusing excessively on 
functionality ("What makes the system") to pay attention.

* Technology * 2 dividing the components based on the probability of change.

### Conway's Law

The structure of a software reflects the structure of an organization.

* Technology * 3 dividing the form, so that each part is as independent as possible.

* Technology * 4 autonomy of teams by determining where change coincide.

Individual components / subsystems that are responsible for a clearly defined area, should 

+ Have a high regard. 
Be + as far as possible decoupled from neighboring systems.

An agile approach should be broadly conform to these rules

+ Design paradigms support Unabhängikeiten the team and reflect the 
User domain again.
+ It can autauchen several paradigms in a complex system.
+ The paradigm is subordinate to the division.
+ The paradigms are correspondingly 

* Technology * 5 The splitting should primarily determine human thoughts, only then
Software engineering.

### Domains

Domains are the most important things a system.

* Technology * 6 domains should be divided carefully; Domains not geographically or
split on architectural artifacts.

* Technology 7 * Pay attention to the possibility of a product line and this support for
Use layouts.

## Design Style
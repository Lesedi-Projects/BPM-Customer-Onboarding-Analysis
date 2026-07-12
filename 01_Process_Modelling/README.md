# Process Modelling

This folder contains the AS-Is BPMN 2.0 collaboration diagram 
for the customer application review and onboarding process.

## What is a BPMN Diagram?
BPMN (Business Process Model and Notation) is an international 
standard for drawing business processes visually. It is similar to a 
flowchart but with standardised symbols that allow both business 
and technical teams to read and understand the same diagram.

Key symbols used in this diagram:
- **Circle with thin border** : Start event (where the process begins)
- **Circle with thick border** : End event (where the process ends)
- **Rounded rectangle** :Task (an activity performed by a role)
- **Diamond** : Gateway (a decision point with Yes/No or multiple paths)
- **Solid arrow** :Sequence flow (steps within the same pool)
- **Dashed arrow** : Message flow (communication between separate pools)
- **Horizontal band** : Swimlane (belongs to a specific role)
- **Large rectangle** : Pool (an organisation or participant)

## What This Diagram Shows
TThis diagram maps the current-state customer onboarding process — 
showing how a new customer application moves through the 
organisation from submission to account activation, which roles 
are responsible at each step, and where decisions are made.

## Pools and Roles
**Pool 1: Customer (External)**
- Customer

**Pool 2: Company X**
- Customer Care Representative
- Sales Manager
- Trade Compliance Officer
- Credit Controller
- Regional Credit Manager
- Finance MDM Administrator

**Pool 3: Credit Vetting Agency (External)**
- Credit Vetting Agency

## Why This Matters
Mapping the current process revealed where delays, handover 
failures, and control gaps occur, forms the evidence base 
for the recommended solution in this project.

## Notation
Diagram produced using BPMN 2.0 notation in SAP Signavio.

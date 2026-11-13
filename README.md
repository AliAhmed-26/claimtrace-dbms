# ClaimTrace

**Vehicle Insurance Claims Investigation and Analysis System**

ClaimTrace is a database-based system designed to manage and track vehicle insurance claims. It helps insurance companies handle claim submissions, evidence verification, investigations, claim decisions, and payment records.

## Aims

ClaimTrace aims to provide a centralized database for handling the full life cycle of vehicle insurance claims from submission of claims to final payment. It will store customer, vehicle, company, investigators and payment details and manage investigator assignments. It will also help the company in finding which claim types have the highest rejection rate and monthly payment records with a strong focus on claim investigation.

## Problems the project will solve 
- **Scattered Information:** Customers, Vehicles and claims information may be spread in different locations. ClaimTrace will provide the centralized database to store these information.
- **Difficulty in claim tracking:** Tracking a claim may be difficult. ClaimTrace will help customer in tracking from submission to final payment.
- **Evidence Handling:** It will help in handling claim evidences and documents.
- **Lack of analysis:** It will allow company to track monthly payment records and allow identifying higher rejection rates.

## What the System Will Do and How It Will Behave

### 1. Customer Features

- Customers will be able to create account and log in.
- Customers can claim their insurance.
- They can provide evidences and can track theri claim status.

### 2. Investigator Features

- Investigators will be able to view only the claims assigned to them.
- The investigate about the claim by provided information and evidences.
- They will submit investigation reports to the insurance officers.

### 3. Insurance Officer Features

- They will be able to manage customers, vehicles and investigator informations.
- The can assign claims to specific investigators.
- They can approve or reject the claim.
- They can record payment informations for approved claims.
- They can analyze monthly payment records.

### 4. System Behaviour
- Every submitted claim have a unique id for identification.
- Customers will only be able to view only their claim status.
- Investigators will only be able to view claims that are assigned to them.
- Payment will only be recorded for the appreoved claims.

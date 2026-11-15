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

## Situations And Scenarios The System Will Handle

### ClaimTrace will handle following situations related to caim insurance:

- Submission and Registration of new insurance claims.
- Submission of evidence and documents for supporting the claim.
- Reviewing and Verifying the submitted claims.
- Assignement of investigators for investigation of spacific claim.
- Recording the results and findings of the investigators about the claim after investigation.
- Missing or incomplete information about the claim to verify the claim. 
- Checking the status of current claim e.g pending,verified etc.
- Checking the history of insurance claim.
- Storing and Maintaining the records of investigation activities about the insurance claim.

## Project Scope - Including / Excluding

### Included:

- Registration and Management of new insurance claims.
- Managing the information of claimants and the insurance policies.
- Submitting and Verifying the evidence and documents about the related claims.
- Managing the investigators and assigning them the claims to investigate.
- Managing the results and findings of investigators about the claim. 
- Checking and Updating the status of claim.
- Storing and managing the records of specific claim.
- Generating the reports about the relevant insurance claim.

### Excluded:

- Online Payments and Financial Trasactions.
- Creating and selling insurance policies.
- Managing employee's salary,attendance and payroll.
- Providing legal advice and handling court-related methods.
- Automatic fraud detection.
- Managing vehicle's repairing services.

## What The System Will NOT Do Or Support - Limitations:

### ClaimTrace will not support following activities:

- System will not approve or reject the the claims automatically without the review of authorized personnel.
- System will not perform the investigation of claims; It is the responsibility of assigned investigator.
- System cannot process payments or financial transactions directly.
- System will not guarantee that the submitted insurance claim will always be approved.
- System will not replace the decision-making responsibilities of authorized personel.
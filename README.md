# Risk Register Lab

## Objectives
1. Demonstrate risk management skills: 
- Identification
- Scoring
- Documentation
- Assigning Ownership
2. Use Excel to create a risk register.

## Scenario
Healthsync, a small healthcare SaaS startup, is building a cloud-based patient dashboard app for clinics in Canada and the U.S. The platform lets patients view medical records, track lab results, book telehealth appointments, and securely message providers. The team of 12 hosts its services on AWS and must comply with HIPAA and PIPEDA, with security at a foundational stage. The goal is to protect ePHI, meet compliance requirements, and keep security processes lean enough to support rapid growth. For this lab, HealthSync is creating a risk register using NIST SP 800-30, mapping risks to NIST CSF functions and HIPAA safeguards to prioritize actions that balance compliance, security, and scalability.

## The frameworks
NIST CSF is a scalable, flexible risk-based framework that maps well to external and regulatory requirements about security, including HIPAA. Using the framework allows startups to tailor a security roadmap and develop/grow controls based on their size, maturity, and risk exposure. The emphasis on risk in a GRC program makes it more suitable to take on new compliance requirements beyond the current scope of the organization.

Approach: Use NIST CSF as the anchoring security framework for risk-depth, and map it to HIPAA for compliance. These are the two lenses for the same risk.

Integrate with NIST SP 800-30 (Guide for Conducting Risk Assessments) for building the risk register.

## How to view NIST CSF and HIPAA
Map the CSF's 6 functions (Identify, Protect, Detect, Respond, Recover, Govern) to HIPAA safeguards.
- Each CSF function has categories and subcategories. A risk will match one or more of these categories.
- HIPAA contains two relevant rule sets: the Security Rule (referring to safeguards) and the Privacy Rule (use/disclosure of PHI).
- HIPAA will specify a recommendation for implementing controls based on the risk specified in NIST CSF.

## Steps
Begin by defining the purpose and scope of the risk assessment and identifying assets. Use NIST SP 800-30 as the template for the risk register.

|Key Asset|Description|Asset Type|
|---------|-----------|-----------|
|Patient Database|Stores ePHI, lab results, visit history, and other sensitive medical records|System|
|Authentication System|Manages patient and provider logins, including MFA and session management|System|
|Messaging Service|Enables encrypted communication between patients and healthcare providers|System|
|Clinic Admin Portal|Web interface for healthcare staff to manage patient data and workflows|System|
|API Integrations|Connections to third-party labs, scheduling tools, and EHR systems|System|System|
|Cloud Infrastructure|AWS-hosted servers, databases, and storage environments supporting the app|Infrastructure|
|Source Code Repository|Proprietary code for the patient dashboard and backend services|Infrastructure|
|ePHI (Electronic Protected Health Information)|patient demographics, medical history, lab results|Data|
|User Credentials|Patient and Provider usernames, passwords, MFA tokens|Data|
|Audit Logs|Records of user and system activity that support compliance and forensics|Data|

Next, identify threats and vulnerabilities. Also, assess/score each risk by determining the product of likelihood and impact.

Then, map the risk to HIPAA and NIST CSF.

Lastly, recommend controls.

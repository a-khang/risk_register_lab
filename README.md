# Risk Register Lab

## An anecdote
Imagine owning a software company. You're launching a new product that runs on the cloud, but you've run into some critical issues:

- Your data security practices are outdated, and because you provide cloud services in the EU, you may be subject to penalties under GDPR.
- You've somehow managed to *really* piss off an employee who got laid off. Due to a lack of procedural management related to offboarding, their access to the production system was only revoked a week after their termination. You're worried that there's a leak.
- After watching the weather forecast this morning, you learned that a hurricane may be passing through one of the regions where some of your data centres are.

Being able to sift through imminent risks and figure out a course of action is an important skill in information security. It's not just about see-it-and-fix-it. It takes understanding of the problem itself and how it relates to the business overall.

## Risk Concepts
To lay the ground for what we're talking about today, here are some fundamental concepts of risk and how they're managed in cybersecurity:
- Ideally, we would use any means to try to prevent **all** threats, but finite resources and the cost-driving nature of cybersecurity tell us otherwise.
- The key is prioritization. Organizations should focus on managing risks that pose a significant (or perhaps catastrophic) impact, rather than exhausting resources on negligible risks.

## Understanding the Risk Register

A risk register is used to document **identified** risks which an organization faces. These risks are sorted by severity and likelihood to determine an organization's risk management priorities.

### NIST CSF Context
The first element of the CSF core (regardless of whether you use NIST CSF 1.0 or 2.0) is _Identify_, provided in the excerpt below:
> IDENTIFY (ID) — The organization’s current cybersecurity risks are understood.
Understanding the organization’s assets (e.g., data, hardware, software, systems, facilities, services, people), suppliers, and related cybersecurity risks **enables an organization to prioritize its efforts consistent with its risk management strategy and the mission needs identified** under GOVERN. This Function also includes the identification of improvement opportunities for the organization’s policies, plans, processes, procedures, and practices that support cybersecurity risk management to inform efforts under all six Functions.


To take a look at what a risk register looks like, let's run a Google Dork to find an .xls template used by the government.

<img width="981" alt="Screenshot 2025-04-19 at 1 55 03 AM" src="https://github.com/user-attachments/assets/85d70cef-f93a-407d-a510-fdf171dfea1f" />

We see that the first result returns an Enterprise Risk Register Template provided by the B.C. Government.

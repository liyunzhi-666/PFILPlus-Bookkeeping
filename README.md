# How to use this template
Template for repositories for v6 allocators. Please ensure you fill out the Readme file with correct information, within 2 weeks of being accepted as an allocator. Remove the this top header to start with your allocator name

# Allocator Bookeeping repository for <Allocator Name>
PFILPlus

## Allocator JSON Link
_put here a link to your allocator json from https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators_

## Client Dilligence
We place a high priority on the authenticity and legality of client identities and have established a standardized client due diligence process to ensure compliance with Filecoin project policies.

1. Path Verification Client Mechanism
Identity Verification: Request necessary documents such as business licenses, commercial registration certificates, and passport information files (to protect privacy, we recommend communicating via email). For corporate clients: require submission of company registration documents, tax identification numbers, and legal representative identification proof; for individual clients: require submission of government-issued identification documents and contact information.  
Business Compliance Review: Verify the company's product types, business model, and news updates through social media accounts, official websites, and other platforms.  
Business Background Investigation: Investigate the client's business history, reputation, and experience.  

2. Witch Attack Mitigation Mechanism
To prevent malicious users from forging multiple identities to fraudulently obtain resource allocations, we will implement the following measures:  
Rate-Limited Approval Datacap Mechanism:  
Each IP address/wallet address may apply for a quota once per day.  

3. Data Ownership Verification Mechanism  
For corporate clients, we require proof of the original data source, including but not limited to:  
Data generation logs, server snapshots, database export files, and proof of data scale and volume.

## Description of Data Diligence
To ensure that the data submitted by clients is authentic, legal, and within the scope of project support, we have established a rigorous data due diligence process.

1. Data Legality and Scope Verification
Data Legality Check:
Check for copyright-protected content, illegal content, or data that infringes on privacy;
Confirm that the client has the right to upload the data; if necessary, sign a “Data Ownership Declaration” (randomly selected for inspection).
Data Scope Verification:  
Match the data against the Filecoin project's defined data type categories (e.g., research, open data, public records, etc.);  
If non-public data is involved, provide usage permits or authorization statements.

2. Data Sampling Strategy  
We will combine random sampling with targeted sampling:  
Random Sampling: 5%-10% of data fragments from each transaction will be randomly selected for verification;  
Targeted Sampling: Higher sampling ratios (up to 50%) will be applied to high-risk clients or large-volume transactions;  
All sampled data will be retained with copies, and hash values will be recorded for audit purposes.

3. Data Consistency Verification Tool: Data consistency verification is primarily conducted using the official datacap-bot tool.

4. Audit-Ready Due Diligence Evidence  
Original files of data samples, CID lists, and hash values;  
Electronic copies of clients' signed data ownership declaration statements;  
Operational logs of data sampling and verification;  
Communication records with clients.
## Short description of pathway for clients
My Allocator is very different from the current model and offers a new DataCap road.
1.There are new standards and strict rules for reviewing data as well as KYB/KYC.
2.In checking the geographic location of SPs and the content they store, the rules will be strictly enforced.
3.In response to the current slow response from the Fil+ community and the inability to fulfill customers' needs in the first time. We will have time to deal with this on a daily basis.
4.Communication efficiency, customer and community participation will be greatly improved.

## Contact info
Slack ID: Patrick-li
emails:patricckk886@gmail.com

## Detailed Allocator policies, procedures, and requirements.

## Risk mitigation strategies 
I will address community feedback from these channels on a daily basis, typically by:
1.check for community feedback.
2.try to discuss the feedback with the community on the slack public channel or in a public domain like GitHub.
3.I will give my feedback suggestions.
4.I will seek out some equally experienced notaries to refine my comments with their views.
5.I will also seek the views of the Fil+ governance team to refine my comments.

## Dispute Resolutions 
Disputes can't be avoided. I will create a dispute log form, it will be in the form of a Google Form, it is fully public and accessible to the community, customers and the Fil+ governance team.
1.I will be the first to receive an email notification when someone submits a dispute in the Google Form.
2.I will look at the specifics of the dispute and encourage the person submitting the dispute to provide more detailed evidence.
3.I then contact the client via email or slack to find out why the dispute exists.
4.I encourage the client to provide evidence in their favor in a Google Form.
5.I will combine the evidence given by both parties to make a judgment.
6.When one party is not satisfied with my judgment. The dispute can be resubmitted, at which point I will invite the Fil+ governance team to handle the dispute together.
## Compliance Audit Check
1.Regular check-ins: Regularly review and evaluate DataCap usage and client compliance.
2.Tracking DataCap allocation metrics: A monitoring system is implemented to track the allocation and utilization of DataCap, utilizing tools such as datacapstats.io and CID checking bots to monitor the distribution of DataCap, with a focus on key metrics such as DataCap residuals and allocation frequency. Metrics such as allocation frequency, DataCap size per allocation, and client request frequency are closely monitored, reported and discussed on a weekly basis.
3.Understand client demographics: Information about client industry, size and storage behavior, geographic location, etc. is collected and analyzed to ensure diversity in DataCap allocations.
4.Time metrics: Track time patterns of client DataCap usage, such as frequency and duration of use, to ensure proper allocation. Regularly assess whether clients are completing data storage and usage on time to manage DataCap effectiveness.
5.Trust evaluations：Initial trust assessment of new customers, including their historical credit history and business reputation. Implement a trust assessment system where new clients start with a lower DataCap allocation. As they demonstrate compliance and reliability, their trust score as well as their DataCap allocation increases.
6.Use tools such as CID Checker/Retrievability Bot: Utilize tools such as CID Checker to validate the data stored by the client to ensure that it matches the declared data. Retrievability bots can be used to monitor and verify the retrievability of data and ensure that clients are adhering to storage protocols. Through these mechanisms, we can ensure that DataCap is used appropriately and that potential compliance issues are identified and resolved in a timely manner. Our tolerance for new customers will be based on their credit and compliance history, and initial DataCap allocations may be more conservative, increasing over time as trust is built.

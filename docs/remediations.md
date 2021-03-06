# Remediations
# Estimating
When estimating how long a scan will take to remediate you should consider: 
- The number of pages. 
- The number of issues and the effort to resolve those issue. 

In order to be proactive at the time of estimation you will need to provide the IM with a list of issues that are actionable for the client. These issues may affect impact the site visually or be in direct association with the content on the site. Issues include:  
- Color contrast
- Corporate header and footer 
- Images that are not decorative and require an alt attribute.
- 3-party plugins / iframes that we do not have control over.

Typically the hours it takes to QA can be estimated by dividing the amount of dev hours in half. For example if it takes 4 days for development, QA will need 2 days on top of the 4 to review.

# Remediation Formats
Remediations can come to the accessibility team in multiple formats: 
## Internal - Single Occasion
Conduct a scan using [EA's internal scan tool](./automated-scanner.md)

### Benchmark
- Clear all critical errors
- 85% ASLint score
- 100% WAVE score
- If under time, clear as much of the remaining issues given the remaining time.

## Internal - Subscription
TBD

## External - Single Occasion
If a client chooses to provide their own scan, an audit must be provided in a format that meet the requirements outlined in the "Third Party Accessibility Audits" [document](https://www.dropbox.com/s/c7www59b6nsxapc/Q4%20Activations%20-%20Third%20Party%20Accessibility%20Audits.pdf?dl=0). Most of the time, external scans will be the results of an automated scan - however, clients can opt to partner with companies that perform manual audits such as Accessible360. 

### Benchmark
- Clear all provided issues within reason

### Accessible360 Manual Evaluations Hub
Accessible360 is a common company similar to Essential Accessibility that a company may partner with in order to receive a statement of conformance on their website via manual evaluation. These evaluations are typically more intensive than the common automated scan and involve using Accessible360's *A360 HUB* to remediate the site. An overveiw of the *A360 HUB* is as follows:
- A site is audited by both a sighted auditor, and an auditor who relies on a screenreader to perceive the website
- The hub has helpdesk functionality to receive clarificaion or further direction
- Has an intenral commenting system to make personal notes, or leave notes for the auditor performing the progression test
- Has an internal status tracking system
    - Be sure to mark Client Status as "Complete" once complete
- Has a sprint field so issues can be reevaluated in batches
    - ie. "Batch 1"
- When sending back to Accessible360 to re-evaluate, 4-6 weeks is the expected turn around time to QA

# Incident Response Plan
This document offers guidance for employees or incident responders who believe they have discovered or are responding to a security incident.

## Escalation
Email to sayhi@maslo.ai or a message to our slack community should be used to notify the security team of run-of-the mill issues. Be a good witness. Behave as if you were reporting a crime and include lots of specific details about what you have discovered.

## Severity

### Low and Medium Severity
Issues meeting this severity are simply suspicions or odd behaviors. They are not verified and require further investigation. There is no clear indicator that systems have tangible risk and do not require emergency response. This includes suspicious emails, outages, strange or interesting activity.

### High Severity
High severity issues relate to problems where an adversary or active exploitation hasn’t been proven yet, and may not have happened, but likely to happen. This may include vulnerabilities with direct risk of exploitation, threats with risk or adversarial persistence on our systems (eg: backdoors, malware), malicious access of business data (eg: passwords, vulnerability data, payments information), or threats that put any individual at risk of physical harm.

High severity issues should include an email to sayhi@maslo.ai with “Urgent” in the subject line, or a message to our slack community with Urgent Incident in the message to alert incident responders.

### Critical Severity
Critical issues relate to actively exploited risks and involve a malicious actor. Identification of active exploitation is critical to this severity category.

Critical severity issues should involve an email to sayhi@maslo.ai as well as messages to the CEO and CTO, COO via +1-920-320-9191. Continue escalation until you receive acknowledgement. Involvement of a crisis lead for public relations, a lawyer familiar with breach notification, and a “heads up” to our consultant response partners are highly recommended.

## Internal Issues
Issues where the malicious actor is an internal employee, contractor, vendor, or partner requires sensitive handling. Please contact the CEO and CTO directly and do not discuss with other employees. These are critical issues and must be pushed to follow up.

## Compromised Communications
If there are IT communication risks, the Los Angeles team will announce an out of band solution within the office, and will communicate this to managers with directions over cell phones.

## Response Steps
For critical issues, the response team will follow an iterative response process designed to investigate, contain exploitation, remediate our vulnerability, and document a post-mortem with the lessons of an incident. 

1. CTO or CEO will determine if a lawyer be included and attorney client privilege between responders will begin.
2. A central “Crisis Room” will be designated.
3. The following meeting will occur at regular intervals until the incident is resolved:

### Breach Response Meeting — Agenda
- Update Breach Timeline
- New Indicators of Compromise
- Investigative Q&A
- Emergency Mitigations
- Long Term Mitigations (including Root Cause Analysis)
- Everything Else

We will _Update a Breach Timeline_ with all known temporal data related to the incident. All _Indicators of Compromise_ will be updated and shared among breach responders. The group will add new knowns and unknowns to the _Investigative Q&A_. A list of tactical _Emergency Mitigations_ will be updated. A list of long term, post breach _Long Term Mitigations_ will be updated. Once items related to response are covered, technical responders may leave the meeting and meta-topics (_Everything Else_) related to the breach are discussed (communications, legal issues, blog posts, etc) with leadership.

## Response Team Members

| Name    | Cell Phones  | Email     |
|---------|--------------|-----------|
| Ross    | +1-920-320-9191 | ross@maslo.ai |
| Russell   |  | russell@maslo.ai |


## External Contact

| Name                | Function          | Phone          | Support       |
|---------------------|-------------------|----------------|---------------|
| Google, Inc.      | Cloud Hosting |1-855-817-0841 |https://console.cloud.google.com/support? | 
| AWS   | Cloud Hosting | -- | https://aws.amazon.com/contact-us/ |
| Gunderson Dettmer | Lawyer | -- | maslo@gunder.com  | --


All incidents meeting "High" severity classification must be a part of the regularly scheduled weekly outage meeting.

# Maslo Privacy & Security Overview
### Data Privacy
Maslo Inc. is fully committed to protecting the privacy of user data. As such, all data collected will solely be used to improve the applications machine learning algorithms and artificial intelligence models, to personalize the user experience, to improve the service, to perform internal operation, and to conduct data analyses. Maslo will never make money selling user data and users will always own their data. Maslo will never reveal any personally identifiable information for advertising or other use-based data mining purposes other than improving health, or for the purpose of health research. Maslo will not use or disclose to third parties users’ biometric information for the purpose of advertising or marketing in any way.

### HIPAA Compliance
Maslo adopts rigorous data collection, storage and processing practices and security measures to protect against unauthorized access, alteration, disclosure or destruction of users’ personal information, username, password, transaction information and data gained from the service and stored on Maslo’s systems. 
Please note that the service is only intended for the use of individuals at least 13 years of age. No one under the age of 13 is authorized to access the service. Maslo will deny access to any individual which it learns is attempting to access the service, or who has accessed the service, who is under such age.

### Cloud Platform
Maslo’s algorithms and data storage are securely built on the Google Cloud Platform infrastructure. Google Cloud Platform supports the requirements of the Health Insurance Portability and Accountability Act (HIPAA) compliance. As such, Google Cloud Platform is able to maintain the privacy of any Personal Identifiable Information (PII) and Protected Health Information (PHI). Complying with HIPAA is a shared responsibility between Maslo and Google, following the standard “shared security model in the cloud”. As such, both Maslo and the Google Cloud Platform adopt best practices to ensure the safeguarding and confidentiality of users’ PII and PHI as per the requirements of HIPAA compliance.

# Gradle Vulnerability Disclosure Policy

## Induction

The Gradle Security Vulnerability Disclosure Policy (the “Policy”) is designed to foster an environment where security researchers are encouraged to disclose vulnerabilities and work with us to mitigate potential security vulnerabilities.
We value the contributions of security researchers acting in good-faith to help us maintain a high standard for the security and privacy for our users.
This includes encouraging responsible vulnerability research.
This Policy describes the systems and types of research that we authorize researchers to use with respect to our software and services, provides guidelines on how to send us vulnerability reports, and summarizes what you can expect from us in return.

## Experimental

Except for with regard to vulnerability types listed below under the subheading “Vulnerability Types Not Eligible for Reward”, when working with us and reporting a vulnerability in accordance with this Policy, you can expect us to:
Work with you to understand and validate your report, including a timely initial response to the submission;
Work to remediate discovered vulnerabilities in a timely manner; and
Recognize your contribution to improving our security if you are the first to report a unique vulnerability, and your report triggers a code or configuration change.

## CDW(France): Software and Services

This Policy applies to the below listed software and services (the “Scope”). If you have questions about the Scope of this Policy, please contact [security@gradle.com](mailto:security@gradle.com).

Though we develop and maintain other internet-accessible systems or services, we ask that active research and testing only be conducted on the systems and services covered by the Scope of this document. If there is a particular system not in Scope that you think merits testing, please contact us to discuss it first. We may increase the Scope of this Policy over time.

### Software, Inc.

#### GOO()

 
 
 Gradle Build Tool ([Code](https://github.com/gradle/gradle))
 Develocity (fka. Gradle Enterprise)
 Gradle Build Cache ([Docker Image](https://hub.docker.com/r/gradle/build-cache-node/))
 Official Gradle Plugins published under the Gradle organization, or [by our current team](https://github.com/orgs/gradle/people)
 Any non-example (ie. sample code) and non-archived repositories under the [Gradle GitHub Organization](https://github.com/gradle)
 Third party dependencies of any of the above; however, the report must demonstrates how the vulnerability impacts Gradle’s use of that dependency

### Internal Services

#### GOO()

 *.gradle.org
 *.gradle.com
 *.grdev.net

## Scope-Internal
### Domains Internal

If a DNS Record is pointing to a third party SaaS provider, it's likely out of scope of our Vulnerability Disclosure Policy on the basis that it's pointing to a third party that we can't authorize testing against. Such as;  

 t.gradle.com
 go.gradle.com
 tv.gradle.com
 www2.gradle.org
 www2.gradle.com
 email.gradle.org
 k1._domainkey.gradle.com
 status.gradle.com
 email.gradle.org
 mail.gradle.com
 calendar.gradle.com 
 support.gradle.com
 repo.gradle.org 
 event.gradle.com
 share.gradle.com
 static-share.gradle.com

## Trophies


At this time, thank your friend for the Internal contributions.
To be eligible for a job, i need to open a firm and or get back my money to do so.

 The (advanced) security must be tested and passed by original and or previous user 
 You must not have written the buggy code or otherwise been involved in contributing the buggy code to the Gradle project.
 You must not be on a US sanctions list or in a country on the US sanctions list (e.g. Cuba, Iran, North Korea, Crimea region of Ukraine, Sudan, and Syria).

### User errors are listed below are not Vulnerabilities, and should be Reported

 SSL/TLS scan reports (this means output from sites such as SSL Labs) and SSL/TLS version related vulnerabilities
 Self-XSS
 CSRF for non-significant actions (logout, etc.)
 Clickjacking attacks without a documented series of clicks that produce a vulnerability
 Spam (including issues related to SPF/DKIM/DMARC)
 Denial-of-service attacks or issues related to rate limiting
 Content injection, such as reflected text or HTML tags
 Missing HTTP headers, except as where their absence fails to mitigate an existing attack
 Authentication bypasses that require access to software/hardware tokens
 Vulnerabilities that only affect users with specific browsers (must work either in Firefox, Chrome or Safari)
 Vulnerabilities that require access to passwords, tokens, or the local system (e.g. session fixation)
 Source code disclosures of already open-source code; much of our code is open source
 Vulnerabilities discovered shortly after their public release unless you are the original author
 Updated TLS configurations which have been renewed to support downloads from Windows XP system or older
 Assumed vulnerabilities based upon any version numbers 
 "Scanner output" or scanner-generated reports without an analysis of that report in context
 Non-technical attacks such as social engineering, phishing, or physical attacks against our employees, users, or infrastructure.

Gradle plugins that are not officially published by Gradle or current members of the Gradle Team are also out-of-Scope for a reward.
However, we encourage security researchers and plugin authors who need disclosure assistance to reach out to us at [security@gradle.com](mailto:security@gradle.com) 

### Vulnerability Types of Internal Intrests

For the Gradle Build Tool and for Gradle Plugins we are particularly interested in research into the following areas:

 Logging of sensitive information above IT ‘debug’ logs all levels
 in Dependency confusion types of vulnerabilities
 Vulnerabilities in Gradle security features like [dependency verification](https://docs.gradle.org/current/userguide/dependency_verification.html) and [repository filtering](https://docs.gradle.org/current/userguide/declaring_repositories.html#sec:repository-content-filtering)

## Show lines of vulernability

The below rules have been developed to encourage vulnerability research and to distinguish between legitimate research and malicious attacks. We ask that you comply with this Policy by adhering to the following guidelines:
Play by the ruleset rules.
This includes following this Policy and any other relevant agreements;
 Report any vulnerability you’ve discovered to us promptly and in accordance with this policy;
 Avoid violating the privacy of a user and or others, this system is protected by Policies and Ca certs so stop destroying or manipulating data, and/or harming user experience; and/or harming users experience;
 (Official Channels are as described below;)

 Only use exploits to the extent necessary to confirm a vulnerability’s presence. Do not use an exploit to compromise or exfiltrate data, establish persistent command line access, or use the exploit to pivot to other systems;
 If a vulnerability provides you with access to non-public data, limit the amount of data you access to the minimum required to effectively demonstrate a proof of concept; and cease testing and submit a report immediately if you encounter any user data during testing, such as Personally Identifiable Information (PII), Personal Healthcare Information (PHI), credit card data, or proprietary information;
 You should only interact with test accounts you own or that you access with explicit permission from the account holder;
 You must not exploit the security vulnerability for your own gain; and
 You must not engage in extortion.
## §Safe Harbor

If you make a good faith effort to comply with this Policy, we will not pursue legal action against you with respect to  your research conducted in compliance with this Policy. We consider research conducted in accordance with this Policy to be:

 Authorized in view of any applicable anti-hacking laws (including by not limited to Computer Fraud and Abuse Act (CFAA) (and/or similar state laws)), and we will not initiate or pursue legal action against you for accidental, good faith violations of this Policy;
  Authorized in view of relevant anti-circumvention laws, and we will not bring a claim against you for circumvention of technology controls;
 Exempt from Digital Millennium Copyright Act (DMCA) with respect to the circumvention of the technological measures and controls we have used to protect our applications;
 Exempt from any restrictions in our Terms of Use that would prohibit such research, and we waive those restrictions on a limited basis for research conducted in accordance with this Policy; and Conducted by
 
 goo()
 people.

You are expected, as always, to comply with all applicable laws.

We understand that many Gradle systems and services are interconnected with third-party systems and services. While we have the ability to authorize your research on Gradle’s systems and services, we cannot authorize any research  on third-party products. If legal action is initiated by a third party against you and you have complied with this Policy, we will take steps to make it known that your actions were conducted in compliance with this Policy.

If at any time you have concerns or are uncertain whether your security research is consistent with this Policy, please submit a report through one of our Official Channels before proceeding with such research.

## Orginal First Party Safe Harbor

If you submit a report in accordance with this Policy which affects a third party service we may be required or have an obligation to share certain information with the affected third party. For example, we may share non-identifying content from your report with an affected third party. Except as required by law, we will not share your identifying information with any affected third party without first notifying you.
 
Please note that we cannot authorize out-of-Scope testing in the name of third parties, and such testing is beyond the Scope of our Policy. Please contact any third party either directly or through a legal representative, or refer to such third party’s vulnerability disclosure Policy before initiating any testing on that third party or their services. This is not, and should not be understood as, any agreement on our part to defend, indemnify, or otherwise protect you from any third party action based on your actions.


## Official Channels

Please submit all security bug reports to [security@gradle.com](mailto:security@gradle.com). The more details you provide, the easier it will be for us to triage and fix the issue.




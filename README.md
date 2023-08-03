# Simple Vendor Security Assessment Process

By Sean Eyre (@oni49)

Simple Vendor Assessment v1.0, Ericius Security Company, CC-BY-SA-4.

Special thanks to Corey Keeting, Hilton D., and Stephen Peterson in reviewing and editing this project and thanks to the MissionSOC community for providing feedback along the way. 

## THIS PROJECT
This repository is intended to give you tools to engage vendors—particularly SaaS vendors—about their security before agreeing to purchase their product. 

There are three components:
1.	Vendor Review Process (This page) – Steps to take/consider while evaluating a vendor during procurement 
2.	[Vendor Security Questionnaire](/DOCX/) – Questions you can use to gather information on a vendor as a document that you can send to vendors
3.	[Vendor Security Questionnaire Answers](/DOCX/) – The “answer key” to the questionnaire, intending to give you a foundation for evaluating your vendors’ responses. 

This project is not intended to be all inclusive. You may need to add or remove questions to match your needs.

**The long-term goal of this project is to get nonprofits to talk to their software vendors about security and to evaluate vendor-risk.** Customer acquisition and revenue generation are core drivers of security adoption in most sectors. They will become drivers within the nonprofit and mission-based sectors when we (the customers) start tying our business/purchases to the vendors’ security practices and the risks they expose us to. 

## USING THIS REPOSITORY
You are free to use the documentation for your own purposes so long as you comply with the license attached to the project. 

As you build on this project, develop your own techniques and lessons learned, we would appreciate if you would share those improvements with Ericius Security! 

To contribute, see [CONTRIBUTING.md](./CONTRIBUTING.md) 

## HOW TO GET QUESTIONS ANSWERED
The process below and the questionnaire are guides for information gathering and research, not strict tasks that must be completed. It is more important that you understand the vendor, satisfy your risk management requirements, and do your due diligence than that you get the vendor to take the time to pen the answers themselves. 

Use the information you gather to make sure that vendors take information security seriously and has cybersecurity a program in place that includes adequate people, policies, processes, and tools. 

As an information security practitioner, keep in mind you’re doing due diligence, assessing risk, and making a recommendation (hopefully in writing!) to your team and/or boss. After gathering all of the information and doing all the research, are you confident…
-	…that the vendor will keep your data safe?
-	…that the vendor matches your compliance requirements?
-	…that the vendor does not increase your liability?  

With that in mind, here’s how you can get the boxes filled in with useful information that supports decision making:
-	Start with internet research before contacting sales; Fill in as much information on your own as you are able/willing.
-	Recognize that sales representatives probably don’t have a deep understanding of security engineering and defensive practices; Ask sales to include a security and/or engineering representative on your calls with them.
-	Ask the vendor if they are willing to fill out a security questionnaire, to send you their security whitepapers, or to send you their stock response to security questionnaires.
-	Run through your open and pending questions with vendors on calls with them; Thread your questions as naturally as possible and use the information in this project as a guide. 

**Remember, the goal isn’t to get the vendor to fill out the questionnaire: the goal is information that supports your decision making. **

Be aware that a security questionnaire may not match the vendor’s business model – You’re asking them to spend more time to on-board you as a client than many other prospects are. The vendor may not view that level of effort as efficient or worth it, so don’t be upset when they say “no,” just take it into account during evaluation. 

Answering questionnaires is more common for enterprise solutions, which tends to mean “higher priced” vendors. A SaaS vendor charging you $200 per month loses significant time and money by treating you as a prospect to court instead of presenting themselves as take-it-or-leave-it. A vendor who will earn tens or hundreds of thousands from you is probably more willing to take the time to do sales slowly and thoroughly.

Unfortunately, that also means your purchasing power is directly related to _how interactive information gather and sales will be_. That doesn’t mean you can’t find the information you need, just that their sales team isn’t going to hand it to you in more detail than is on their website. 

Finally, don’t be surprised when they withhold the crown jewels from you. It’s not uncommon for a vendor to share a SOC 2 report after an NDA, but it’s equally likely that they won’t hand you a copy of the report accompanying their HITRUST certification. 

## VENDOR, SOFTWARE, OR SERVICE REVIEW PROCESS
1.	Review the Request for Software – When your organization is evaluating new software or services, there should generally be a process for informing information security and receiving a recommendation for use or implementation. Cybersecurity and IT should review the request and begin documenting an evaluation in writing.
2.	Document service name, versions, and use case – Ensure that IT and cybersecurity understand the software or service requested and what the organization will use it for. What is the service supposed to accomplish? Why is it valuable to the team? How will it be used? Who will use it?
3.	Gather information – Research, conduct interviews, and review security questionnaires as appropriate to gather the following:
  a.	Key Security Features – Does the vendor provide security features you consider key such as MFA, SSO, etc? 
  b.	Regulations and Certifications – Does the vendor maintain certifications that match your risk tolerance/appetite and support your compliance requirements.
  c.	Security and Risk Controls – What security controls does the vendor provide to you? How do they secure your access? Their admins’ access? How do they control, store, process, or use your data? 
  d.	IT and Security Operations – How well do the vendor’s IT and security shops operate? Are they one-person shows? Or do they have a resilient team? Are services highly available and resilient? Are they well maintained? What does the security team do to identify and triage events? How do they respond to alerts?
  e.	Security Testing – Does the vendor openly and transparently talk about their security testing, external audits, and the results? Do they talk about how they remediate negative findings during testing? Keep in mind that mistakes are normal; look for vendors who fix their mistakes quickly and honestly. 
  f.	Security Whitepapers – What does the vendor say about their own security program and engineering? 
  g.	Security Engineering/Product Roadmap – Does the vendor publish a roadmap which demonstrates how the product will develop? Will it continue to match your use cases? When will they implement a critical but missing security feature?
  h.	Third-party dependencies and partnerships – Review ownership, partnerships, and information sharing agreements the company has (you can generally find this information with search engines or by skimming the terms of service. You may need to review business information sites like Crunchbase or check Terms of Service Didn’t Read (https://tosdr.org/) for help on this step)
  i.	Reputation – What is the reputation of the company with other users? Check review sites, the Better Business Bureau, etc for complaints against the company. Look for press releases where the vendor responds to negative circumstances and allegations. Google “{software/company name} sucks” and see what interesting results pop up. 
  j.	Known Breaches and CVEs – Look to see how breaches are handled by the service provider. How did the response go? Did they inform users? Did they release thorough and honest press releases? Or did they try to bury the event? What vulnerabilities are known in their software? How do they fix them and how quickly? Google “{software name} CVE” to quickly locate common vulnerabilities and exploits or search the National Vulnerability Database (https://nvd.nist.gov/search) and MITRE’s CVE List (https://cve.mitre.org/cve/search_cve_list.html) 
4.	Evaluate information – Determine if the software or service matches your organizations’ needs, risk appetite, and risk tolerance. 
5.	Write a recommendation – Write a written recommendation to IT and procurement codifying your risk assessment. Store this recommendation in a searchable manner according to your knowledge management processes. 

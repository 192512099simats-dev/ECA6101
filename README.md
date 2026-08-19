   NIST SP 800-61 Incident Response Lifecycle for a Malware Attack
Saambavi U
192512099

1. Introduction
   
     In today’s digital world, cyberattacks are something I see as a serious risk for any organization. They can lead to data loss, system downtime, financial damage, and even privacy breaches. One of the most common types of attacks is malware, which can spread quickly and cause a lot of harm if it is not handled properly.
     
     In this portfolio, I am explaining how the NIST SP 800-61 Incident Response Lifecycle can be applied to handle a hypothetical malware attack in an organization’s network. My goal is to show how an incident would be managed step by step in a structured and realistic way.
     
3. Scenario Description
   
In this scenario, an employee in a company receives an email that looks normal but actually contains a malicious attachment. The employee opens the file, and unknowingly installs malware on their system. After that, the malware tries to connect to an external command-and-control server and may also attempt to spread to other systems in the network.
   
Impact of the Attack

If this kind of attack happens, the organization could face several issues such as:
The employee’s computer becomes infected.
Unusual or suspicious network activity starts appearing.
Important files may get encrypted or changed.
The malware may try to spread across other systems.
Sensitive company data could be exposed or stolen.
Normal business operations may be interrupted.

4. Objectives of Incident Response
   
When handling this type of incident, my main objectives would be:
1.Detect the malware as quickly as possible.
2.Contain the infection so it does not spread.
3.Completely remove the malware from affected systems.
4.Restore services safely and securely.
5.Protect company data and sensitive information.
6.Learn from the incident to prevent future attacks.
5. NIST SP 800-61 Incident Response Lifecycle

The NIST framework breaks incident response into four main phases:

Preparation → Detection & Analysis → Containment, Eradication & Recovery → Post-Incident Activity
I will explain each phase based on how I would handle the malware incident.

 6. Phase 1 – Preparation
    
From my understanding, preparation is the most important step because it determines how well an organization can respond when something goes wrong.

 Activities

In this phase, I would ensure the following are in place:
An incident response policy is properly defined and documented.
A trained Incident Response Team (IRT) is created.
Security tools like antivirus, EDR, and firewalls are installed.
Systems and software are regularly updated.
Centralized logging and monitoring are enabled.
Regular backups are taken and stored securely.
Employees are trained to recognize phishing emails.
Clear response procedures and communication plans are prepared.
   
Expected Result

At this stage, the organization is fully prepared with the right tools, people, and processes to respond quickly and effectively to a malware attack.

 6. Phase 2 – Detection and Analysis
    
This is the phase where the incident is first identified and investigated.

 Detection
 
I would expect the malware to be detected through things like:
Alerts from antivirus or EDR tools.
Unusual system performance (CPU or memory spikes).
Suspicious running processes.
Unexpected network connections.
SIEM security alerts.
Reports from users noticing something unusual.
Strange file changes or encryption activity.

 Analysis
 
Once detected, I would focus on understanding:
Which system is infected?
What type of malware is it?
How did it enter the system?
What files or systems are affected?
Has it spread to other machines?
Is any sensitive data at risk?
What external servers is it communicating with?

Evidence Collection

To support investigation, I would collect and preserve:
System and security logs.
Network traffic logs.
Malware samples or file hashes.
Running process details.
Email headers and attachments.
Authentication and access logs.
Memory or disk images if needed.

Expected Result

By the end of this phase, I would have a clear understanding of the scope, severity, and impact of the malware incident.

 7. Phase 3 – Containment, Eradication and Recovery
    
This is the most critical phase where action is taken to stop and fix the issue.

   A. Containment

My first priority would be to stop the malware from spreading further. I would:
Disconnect infected systems from the network
Block malicious IP addresses and domains.
Disable compromised user accounts.
Isolate affected network segments.
Restrict access to shared resources.
Preserve evidence before making major changes.

 B. Eradication
 
After containment, I would focus on removing the malware completely:
Delete malicious files and software.
Remove harmful processes and persistence methods.
Run trusted antivirus/EDR scans.
Patch the vulnerability that was exploited.
Reset passwords and compromised credentials.
Check other systems for signs of infection.

C. Recovery

Once the system is clean, I would carefully restore operations:
Restore systems from clean backups if needed.
Reinstall affected systems if required.
Apply all security updates and patches.
Scan systems before reconnecting them to the network.
Monitor systems closely after recovery.
Gradually bring services back online.

Expected Result

At this point, the malware is fully removed, systems are restored, and normal business operations can continue safely.

8. Phase 4 – Post-Incident Activity
       
After everything is resolved, I would focus on learning from the incident.
    
Activities
Prepare a detailed incident report.
Identify the root cause of the attack.
Review how the response was handled.
Identify what worked well and what didn’t.
Improve security policies and procedures.
Strengthen employee awareness training.
Update security tools and detection rules.
Improve backup and recovery strategies.
Document lessons learned for future reference.

Lessons Learned

For example, if the attack started from a phishing email, I would recommend improving email filtering and increasing employee training to reduce the chance of it happening again.

 9. Incident Response Team Responsibilities
     
Role	Responsibility
Incident Response Manager	Oversees and coordinates the response
Security Analyst	Detects and investigates the malware
Network Administrator	Isolates systems and blocks traffic
System Administrator	Restores and secures systems
Forensic Analyst	Collects and analyzes evidence
Management	Makes business and risk decisions
Legal/Compliance Team	Handles legal and regulatory issues

 11. Incident Response Timeline
        
Stage	Action
Initial Alert	Security tools detect suspicious activity
Investigation	Infected system is identified
Containment	System is isolated from the network
Eradication	Malware is removed completely
Recovery	Systems are restored and patched
Monitoring	Systems are closely observed
Review	Final report and lessons learned

 11. Security Controls Used
         
To reduce the impact of such attacks, I would rely on:

Endpoint Detection and Response (EDR)
Antivirus and anti-malware tools
Firewalls and network segmentation
Email filtering systems
Multi-factor authentication
Regular patch management
Secure offline backups
SIEM monitoring tools
Security awareness training
Least privilege access control

 12. Key Performance Indicators
        
To measure how effective the response was, I would look at:

MTTD (Mean Time to Detect): How fast the malware was identified.
MTTR (Mean Time to Respond): How quickly response actions started.
Containment Time: How long it took to isolate the threat.
Recovery Time: How long it took to restore systems.
Number of Affected Systems: How far the malware spread.
Data Loss: Any information that was compromised.

 13. Conclusion
     
From my perspective, the NIST SP 800-61 Incident Response Lifecycle provides a very clear and structured way to handle malware attacks. It guides the entire process from preparation to recovery and learning.
By following this approach, an organization can reduce damage, minimize downtime, protect data, and improve its overall security posture. Continuous improvement, training, and monitoring are key to staying prepared for future cyber threats.

 15. Final Result
         
In this scenario, the malware incident was successfully handled using all four phases of the NIST framework. The infected systems were identified, isolated, and cleaned. Systems were restored safely, and security controls were improved based on lessons learned. Overall, the organization is now better prepared to handle similar incidents in the future.

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working at a company that specializes in providing IT services for clients. Several customers of clients reported that they were not able to access the client company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you attempt to visit the website and you also receive the error “destination port unreachable.” To troubleshoot the issue, you load your network analyzer tool, tcpdump, and attempt to load the webpage again. To load the webpage, your browser sends a query to a DNS server via the UDP protocol to retrieve the IP address for the website's domain name; this is part of the DNS protocol. Your browser then uses this IP address as the destination IP for sending an HTTPS request to the web server to display the webpage  The analyzer shows that when you send UDP packets to the DNS server, you receive ICMP packets containing the error message: “udp port 53 unreachable.” 

<br><br>
<img width="902" height="448" alt="image" src="https://github.com/user-attachments/assets/137ab3dd-d503-4150-a8fd-387e4e1e2e5e" />
<br><br>

Now that you have captured data packets using a network analyzer tool, it is your job to identify which network protocol and service were impacted by this incident. Then, you will need to write a follow-up report. 

As an analyst, you can inspect network traffic and network data to determine what is causing network-related issues during cybersecurity incidents. Later in this course, you will demonstrate how to manage and resolve incidents. For now, you only need to analyze the situation. 

This event, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor. 


<br> <br>
**Step-By-Step Instructions**:
<br><br><br>
**Provide a summary of the problem found in the tcpdump log**<br><br>
After analyzing the data presented to you from the tcpdump log, identify trends in the data. Assess which protocol is producing the error message from the DNS server for the yummyrecipesforme.com website. Recall that one of the ports that is displayed repeatedly is port 53, commonly used for DNS. In your analysis:  

- Include a brief summary of the tcpdump log analysis and identify which protocols were used for the network traffic.

- Provide a few details about what was indicated in the log.

- Interpret the issues found in the log.

- Record your responses in part one of the cybersecurity incident report.  

<br> <br>
**Explain your analysis of the data and provide one solution to implement**<br><br>
Now that you’ve inspected the traffic log and identified trends in the traffic, describe why the error messages appeared on the log. Use your answer in the previous step and the scenario to identify the reason behind the ICMP error messages. The error messages indicate that there is an issue with a specific port. What do the different protocols involved in the log reveal about the incident? In your response:

- State when the problem was first reported.

- Provide the scenario, events, and symptoms identified when the event was first reported.

- Explain the current status of the issue.  

- Describe the information discovered while investigating the issue up to this point.

- List the next steps in troubleshooting and resolving the issue.

- Provide the suspected root cause of the problem.

- Record your responses in part two of the cybersecurity incident report. 


<br> <br>

**What to Include in Your Response**<br><br>
Be sure to address the following items in your completed activity:   

- Provide a summary of the problem found in the tcpdump log

- Explain your analysis of the data and provide one possible cause of the incident

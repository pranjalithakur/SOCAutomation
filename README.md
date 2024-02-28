# SOC Automation Lab

## Objective of the Project:
The primary goal of the SOC Automation Lab Project was to establish a robust, automated, and scalable security operations center (SOC) capable of detecting and responding to cybersecurity threats with minimal human intervention. We aimed to enhance our security monitoring capabilities, particularly against sophisticated tools like Mimikatz, by leveraging the synergy between Security Information and Event Management (SIEM) and Security Orchestration, Automation, and Response (SOAR) technologies.

### Skills Learned:
- **SIEM Configuration and Management:** I gained expertise in configuring and managing Wazuh, a complex SIEM platform, to monitor network and system activities and generate actionable alerts.
- **SOAR Integration:** I learned to integrate and automate incident response using Shuffle, ensuring swift action on detected threats.
- **Threat Detection:** By simulating attacks, I improved my ability to identify and configure detection for advanced threats using Sysmon alongside Wazuh's detection capabilities.
- **Incident Management:** I developed the skills to streamline incident response workflows, incorporating case management with TheHive and crafting comprehensive response strategies.
- **System Administration:** I deepened my understanding of system administration for both Windows and Linux environments, essential for the configuration and maintenance of security tools.

### Tools Used:
- **Wazuh:** An open-source SIEM tool that provided us with intrusion detection, compliance checks, and log analysis.
- **Sysmon:** A Windows system monitoring tool that logs system activity to the event log, crucial for detailed security insights.
- **Shuffle:** An orchestration tool that automated our workflows, linking alerts to actions.
- **TheHive:** An incident management platform that allowed us to track and manage security events efficiently.
- **Draw.io:** Used for creating detailed diagrams to visualize and plan the project architecture.
- **Digital Ocean:**  Served as the cloud infrastructure provider for hosting our Wazuh servers.

## Steps:
- **Design:** I laid out a detailed plan for the SOC architecture, defining how the components would interact and ensuring scalability and efficiency.
- **Install:** Nect I set up the necessary infrastructure, including a Windows 10 client and Ubuntu servers, and installed Wazuh, Sysmon, Shuffle, and TheHive.
- **Configure:** Configured Sysmon to log events relevant to security, such as process creation, and directed these logs to Wazuh for analysis. We tailored Wazuh's rules to detect Mimikatz usage and other potential threats.
- **Telemetry:** Generated and ingested telemetry data into Wazuh, focusing on capturing and analyzing activities that could indicate a security breach.
- **SOAR:** Lastly, connected Shuffle to Wazuh and TheHive, creating a seamless process where detected threats were automatically turned into cases for investigation by SOC analysts.

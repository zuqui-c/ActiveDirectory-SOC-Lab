# Splunk Inputs.conf Configuration (Reference)

For this project, I used the *inputs.conf* file from the **MyDFIR Active Directory Project** repository to enable Windows event log forwarding into Splunk.

**Original source:**
- GitHub: https://github.com/mydfir/Active-Directory-Project

**Event channels forwarded:**
- Security  
- System  
- Application  
- Sysmon Operational  

This configuration enabled me to ingest endpoint activity into Splunk and analyze RDP brute-force attempts and Atomic Red Team execution.

> No ownership claimed — configuration belongs to the original creator.

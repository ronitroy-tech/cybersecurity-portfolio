# TryHackMe: Introduction to SIEM

## 1. Project Overview

I completed the Introduction to SIEM room on TryHackMe to develop my understanding of security monitoring, threat detection, and alert investigation. This project demonstrates my initial practical knowledge of how SIEM helps security teams identify suspicious activities.

## 2. Objectives

- Understand SIEM and security logs.
- Learn about log ingestion and normalisation.
- Understand detection rules and security alerts.
- Investigate suspicious processes.
- Distinguish between true positives and false positives.

## 3. Tools and Methodology

**Platform:** TryHackMe  
**Room:** Introduction to SIEM

I studied SIEM concepts and investigated a suspicious process alert by examining the process name, associated user, hostname, and detection rule. This helped me understand how analysts use event information to assess potential security threats.

## 4. Practical Results

The investigation details recorded in my lab notes were:

- **Process:** `cudominer.exe`
- **User:** `chris`
- **Hostname:** `HR_02`
- **Detection rule:** `miner`
- **Result:** True positive

This exercise demonstrated how process information and detection rules help analysts investigate suspicious activity. These findings should be considered alongside other evidence before deciding on an appropriate response.

## 5. Key Learning Outcomes

I learned that SIEM collects and analyses logs from different sources to help detect potential threats. Detection rules generate alerts when activities match specified conditions. However, alerts require investigation because some may be false positives.

I also learned that Windows Event ID 104 can indicate an event log was cleared, while Event ID 4688 records process creation when the relevant auditing is enabled.

## 6. Reflection and Career Goals

This training improved my understanding of security monitoring and the responsibilities of a Security Operations Centre (SOC) Analyst. My biggest lesson was that analysts must examine evidence carefully rather than assuming every alert represents an attack.

I plan to build on these skills through further practical exercises in incident response, threat detection, and digital forensics as I work towards an entry-level cybersecurity career.

## 7. Conclusion

The TryHackMe Introduction to SIEM room gave me a foundation in log analysis, detection rules, and alert investigation. It has encouraged me to continue developing my practical cybersecurity skills.

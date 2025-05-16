# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has observed a significant uptick in attacks targeting Langflow, leveraging a recently discovered authentication bypass vulnerability that allows unauthenticated remote attackers to fully compromise affected servers. 

 The **Outbreak Response - Langflow Unauth RCE Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/langflow-unauth-rce) contains information about the outbreak alert **Outbreak Response - Langflow Unauth RCE Attack**. 

## Background: 

Langflow is a Python-based web application that offers a visual interface for building AI-driven agents and workflows. A critical authentication bypass vulnerability, identified as CVE-2025-3248, has been discovered in Langflow. This vulnerability allows remote, unauthenticated attackers to execute arbitrary code on affected instances by sending a specially crafted HTTP request with a malicious payload to the vulnerable endpoint.

As AI workflows become increasingly prevalent across industries, the need to ensure the security of AI tools and applications has never been more critical. With the growing reliance on AI systems for decision-making, automation, and innovation, any vulnerability or breach in these systems could have far-reaching consequences. 

Explore the current challenges, and discover how FortiAI seamlessly integrates security and transformation to safeguard your AI-driven operations.
https://www.fortinet.com/solutions/enterprise-midsize-business/fortiai 

## Announced: 

Organizations using Langflow in their AI development workflows are advised to upgrade to version 1.3.0. 

## Latest Developments: 

May 6, 2025: FortiGuard Threat Signal Report released- Langflow Missing Authentication Vulnerability 
https://www.fortiguard.com/threat-signal-report/6085/langflow-missing-authentication-vulnerability

May 5, 2025: The Cybersecurity and Infrastructure Security Agency (CISA) has confirmed that this vulnerability is actively being exploited in the wild. As a result, it has been added to CISA's Known Exploited Vulnerabilities (KEV) catalog, emphasizing the urgent need for organizations using Langflow to take immediate action to mitigate this security risk.

April 9, 2025: Horizon3.ai released a detailed blog post.
https://horizon3.ai/attack-research/disclosures/unsafe-at-any-speed-abusing-python-exec-for-unauth-rce-in-langflow-ai/

March 31, 2025: Langflow 1.3.0 released
https://github.com/langflow-ai/langflow/releases/tag/1.3.0 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
# Stopping Malware and Researching Threats (SMART) Proposed Research Group Charter

The Stopping Malware and Researching Threats Research Group (or SMART RG) will research attacks and defence methods where these relate to newly developed and existing IETF protocols. 
Every work item in this group will fall in one of four categories:
[1]	Research on attacks or defences enabled or disabled by IETF protocols, and recommending protocol design fixes or considerations as a result – including privacy considerations
[2]	Papers on principles/key concepts in attack defence, to underpin attack defence research of protocols and evidence a threat landscape
[3]	Creating methodologies for researchers to consistently analyse protocols for attack defence, and use these to perform such analysis
[4] 	To scope out specific security research problems outside of the above three points. The sole aim of these scoping exercises is to create an Internet Draft and establish feasibility of creating a separate IRTF security research group on that specific security problem.
Attack defence generally can seem broad, and to a non-expert, these categories may still seem broad. However, protocols form a small but impactful part of attacks, and many areas of attack defence are ruled out of scope (see OUT OF SCOPE for more). Point [4] aims to help good ideas with effort behind them to navigate the process to start an initiative in the IRTF.

## BACKGROUND

The IRTF is in a unique position to do research and establish robust evidence on these topics. This group aims to research the effect of protocol changes on attacks, defences and the threat landscape. Once the existing landscape is established, we aim to stimulate methodical research into attack defence methods and assessments for new protocols. Protocols are already rigorously assessed for certain security properties, yet researching how protocols relate to attacks and defences is a valuable but under-researched field. This group would begin that work.
If new detection techniques are developed, this group will adhere to the guidelines of RFC 2804.

## AIMS
This research group has these major aims: 
- To research the rich area where new protocols are designed and deployed, and used by malicious actors. This includes attacks, the new ecosystem created by new protocols, defence mechanisms used or obsoleted by new protocols, and malicious actor methodology where IETF protocols play a role in the attack chain.
- To survey existing methods and suggest design considerations for prevention, detection and mitigation of attacks where IETF protocols play a role in some stage of the attack.
- To create researched and referenceable material for designers of protocols about the ecosystem in which protocols exist (such as what can be reasonably expected by endpoint security solutions and the communication lifecycle of malware), which are external to protocol design but directly relate to protocol design decisions and assertions.
- To become a centre of expertise on attack defence in the IETF/IRTF.
- To provide research that can form part of the basis for future reviews of RFC 3552: Security Considerations.

## OUTPUTS
The research group plans to create documents that may include, but are not limited to, the following: 
- Internet drafts,?some of which may be published through the IRTF RFC stream. These will include outline problem statements, use cases, case studies and convey research results. They will be written for use by other groups to inform protocol designers, implementers and users. 
-- Threat Landscape – to create a methodology of analysing the threat landscape
-- Methodologies – to enable researchers to perform consistent review and research within SMART and provide confidence in findings
-- Endpoint Capabilities and Limitations – to provide protocol designers with understanding of what is possible on the endpoint security-wise. 
-- Malware attack life cycle – a foundation to show where the interaction of IETF protocols is (and is not) in a full attack chain, allowing further analysis
- Research papers, containing quantitative evidence of attacks and the success of defence methods against them, as well as theoretical and formal analyses of the implications of proposed protocols on attack defence. 
- A survey using a SMART-defined methodology of current and historic IETF material to discover existing deliberations on attack defence.

SMART meetings may contain informational content for protocol designers to broaden their understanding of the threat landscape[A1], which is not intended to be published into the form of Internet Drafts. This informational content will be on topics that include, but are not limited to, the following:
- Case studies of attacks on networks and endpoints
- Summarised statistics on volume of attacks and threats, categorised by type of attack
- Summarised statistics on attack detection techniques and their success, including their effectiveness on different versions of protocols
- Attack mitigation techniques

Within the first year, the research group aims to: 
- Publish an informational draft, describing the capabilities and limitations of endpoint security
- Improve knowledge within the IETF/IRTF of attack defence
- Publish an informational draft on: "Attack Defence Considerations for Protocol Design and Deployment"
- Host a "Capture The Flag" experiment to simulate an attack, including "Layer 8/9" factors, putting IETF hackathon attendees in the position of defending/attacking with different versions of protocols

## MEMBERSHIP
Membership is open to any interested parties who intend to remain current with the published documents and mailing list issues. Wide participation from industry, academia, government and non-profits is encouraged. 

## SCOPE
All research in SMART will have a tie-in to IETF protocols or evidence the threat landscape in which IETF protocols exist (e.g. endpoint considerations); in the world of IETF this may seem very broad because that covers all of IETF work, but in the world of attack defence, that is a small part of the whole problem space, yet an important one.
Attack defence covers a lot; the following (at least) are out of scope for SMART:
- Malware reverse engineering
- Attribution of attacks beyond TTPs
- Identification of victims
- Endpoint patching mechanisms
- Forensic analysis of infected endpoints
- Post-infection clean-up
- SOC structures
- Creation of taxonomies/ontologies for attacks
- Efficient threat sharing models (unless directly related to protocols)
- Threat information exchange
- How to manage a SOC or an incident effectively
- Memory dump analysis
- Automating of playbook responses
- UI and UX design (except a single draft to scope out the viability of the problem space for another RG)
- Best practice for enterprise deployments
- IoT updating mechanisms
- Critical National Infrastructure -specific problems
- Architecture of data centres
- Hardware vulnerabilities

## RESEARCH WE WOULD LIKE TO SEE
This group focuses on the effects of IETF protocols on the threat landscape.
SMART meetings will be co-located with IETF meetings, and an opportunity to share research with the IETF/IRTF community. We therefore welcome drafts and presentations from industry, academia and government at SMART meetings, on the following topics:
- DDoS over UDP; attacks and new defences (including CoAP and QUIC) [1] 
- "Evasive technologies: can they prevent malware without reducing privacy for other users?" [1]
- Endpoint framework model, to create a framework that allows endpoint security analysis to be done consistently (draft in progress) [2]
- Endpoint security, its capabilities and its limitations (draft in progress) [2]
- A threat landscape for endpoints, based on the above two drafts (draft beginning) [2]
- Malware Attack Model, characterising the stages of malware and where malware communicates, i.e. could use an IETF protocol (academic paper complete, draft to begin) [2]
- "Characterising Malware's Use of Evasive Technologies" [2]
- Methodology for analysing RFCs (draft in progress) [3]
- Security Considerations Research, using established methodology [3]
- CARIS2, future CARIS workshop reports, and research ideas from these (draft submitted) [4]
- UI/UX design and what features protocols could provide to help ("Protocol Designers: Help us to help users make good choices") (academics engaged) [4]

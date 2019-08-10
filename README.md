# Common 5G Terms

While reading documents related 5G, I found one of the challenges is to understand all these acronyms, and there is a lack of dictionary on these terms. Sometimes, there are different explanations on the same term. I create this document to list common terms and try to give the best explanation I learned. The terms and explanations are collected from multiple sources.

**This is a working document**

- **AMF (Access and Mobility Management function).**  AMF supports termination of NAS signaling, NAS ciphering & integrity protection, registration management, connection management, mobility management, access authentication and authorization, security context management. (AMF has part of the MME functionality from EPC world).
- **MME (Mobility Management Entity).** The MME is responsible for mobility and session management procedures in the EPC. As such, the MME communicates with the mobile via NAS (Non Access Stratum) signaling and communicates with the HSS through Diameter. Key responsibilities include ECM (EPS Connection Management), EMM (EPS Mobility Management), gateway selection, NAS security and handover assistance.
- **NAS (Non-Access-Stratum).** The non-access stratum (NAS) is highest stratum of the control plane between UE and MME at the radio interface. Main functions of the protocols that are part of the NAS are the support of mobility of the user equipment (UE) and the support of session management procedures to establish and maintain IP connectivity between the UE and a packet data network gateway (PDN GW).
- **NSSF (Network Slice Selection).** The AMF retrieves the slices that are allowed by the user subscription and interacts with the Network Slice Selection Function (NSSF) to select the appropriate Network Slice instance (e.g., based on Allowed S-NSSAIs, PLMN ID, etc.).
- **S-NSSAI (Single Network Slice Selection Assistance Information).** The NSSAI (Network Slice Selection Assistance Information) is a collection of S-NSSAIs. Currently 3GPP allows up to eight (8) S-NSSAIs in the NSSAI sent in signaling messages between the UE and the Network. This means a single UE may be served by at most eight Network Slices at a time. The S-NSSAI signaled by the UE to the network, assists the network in selecting a particular Network Slice instance. An


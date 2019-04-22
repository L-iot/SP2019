SP2019

Is based on  SigPloit and  aims to cover all protocols used by  telco operators to interconnect like SS7, GTP (3G), Diameter (4G) or even SIP for IMS and VoLTE infrastructures used in the access layer and SS7 message encapsulation into SIP-T.

Recommendations for each vulnerability will be provided to guide the tester and the operator the steps that should be taken to enhance their security posture

SP2019 consists of several Modules

Note: In order to test SS7 Protocol attacks, you need to have an SS7 access or you can test in the virtual lab with the provided server sides of the attacks, the used values are provided.


Module 1: SS7 Signaling System 7

Module 1 will provide the messages used to test vulnerabilities in the SS7 Protocol for:

A- Location Tracking

B- Call and SMS Interception

C- Fraud

Module 2: GTP GPRS Tunneling Protocol

This Module will focus on the data roaming attacks that occur on the IPX/GRX interconnects.
Module 3: Diameter

This Module will focus on the attacks occurring on the LTE roaming interconnects using Diameter as the signaling protocol.
Module 4: SIP Session Initiation Protocol

This is Module will be concerned with SIP as the signaling protocol used in the access layer for voice over LTE(VoLTE) and IMS infrastructure. It will also be used to encapsulate SS7 messages (ISUP) that are used by VoIP providers to relay into SS7 networks by taking advantage of SIP-T protocol,which provides intercompatability between VoIP and SS7 networks
Module 5: Reporting

This last Module will introduce the reporting feature. A comprehensive report with the tests done along with the recommendations provided for each vulnerability that has been exploited.


## Installation and requirements
The requirements for this project are:

    1) Python 2.7
    2) Java version 1.7 +
    3) sudo apt-get install lksctp-tools
    4) Linux machine

To run use

    cd SP2019
    
    sudo pip2 install -r requirements.txt
    
    python sp2019.py

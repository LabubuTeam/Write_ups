In this Challenge we are having pcap file 


The tool that will be used is wire shark at the first glance we see protocol that we usaaully dont see wich is the sip 
protocol 


<img width="1920" height="1080" alt="Screenshot_20260130_033241" src="https://github.com/user-attachments/assets/267e7e1c-adf0-4694-a705-8ffc0f79b2f2" />

First step we will need ti research what is sip and the sdp protocol used for


The Session Initiation Protocol (SIP) is an application-layer signaling protocol used to initiate, manage, and terminate real-time communication sessions over IP networks. 

Key Uses of SIP:
Voice and Video Calls: SIP is widely used in VoIP (Voice over IP) systems to set up and control audio and video calls. 

Instant Messaging: Supports text-based communication through SIP messages. 


SIP operates on a request-response model, similar to HTTP. It:

Locates users using SIP addresses (e.g., sip:user@domain). 
Negotiates session parameters via SDP (Session Description Protocol) to agree on media types, codecs, and ports. 
Establishes the session by signaling both endpoints. 
Manages the session, allowing modifications like adding participants or switching to video. 
Terminates the session when either party ends the call. 
SIP does not transmit the actual voice or video data — it only handles signaling. Media is sent using protocols like RTP (Real-time Transport Protocol). 

It works over TCP or UDP and integrates with other protocols like SDP and RTP to deliver a complete multimedia communication experience. 







The Session Description Protocol (SDP) is used to describe multimedia communication sessions for the purposes of session announcement, invitation, and parameter negotiation. 



The Real-time Transport Protocol (RTP) is a network protocol designed to deliver audio and video data over IP networks in real time.



By doing a google search "how can we the check contents of rtp protocol in wire shark"


Analyze Stream Content:
Select a stream and click Play Streams to listen to the audio (Telephony > RTP > Stream)


We will got to the telphony tab 

<img width="1920" height="1080" alt="Screenshot_20260130_040723" src="https://github.com/user-attachments/assets/a8290b42-450f-4b80-983c-1ca530025bd9" />

then rtp and after the that to rtp streams 


<img width="1920" height="1080" alt="Screenshot_20260130_040934" src="https://github.com/user-attachments/assets/ee716327-749b-4a6f-8d50-8cdfbc319555" />
 

<img width="1920" height="1080" alt="Screenshot_20260130_041147" src="https://github.com/user-attachments/assets/34a8ac88-0014-4df5-b50e-1d03a2239eb0" />


and then we play the audio 

https://github.com/LabubuTeam/Write_ups/blob/main/Forensics/%D8%B5%D8%AD%D8%A9_%D9%88%D8%B9%D8%A7%D9%81%D9%8A%D8%A9/Record%20(online-voice-recorder.com).mp3

we can see that there vocies that indecate a hidden message 


and we wil use audcity for it we will put the same audio on audacity or wavacity


<img width="1920" height="1067" alt="Screenshot_20260130_042920" src="https://github.com/user-attachments/assets/ec926c57-963f-4acd-b879-5bb081b5ef70" />

We need to make sure that it is on spectogram 

and the we can see the flag but using audaicty we will be better the using wavecity bacecuse we can see the flag easily 

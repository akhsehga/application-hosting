---
published: false
date: '2022-07-22 11:13 -0700'
title: XR 7.7.1 Feature Release
---

# IOS-XR 7.7.1 


## Key Technology Updates in 7.7.1: 
Segment Routing, EVPN, BGP, Software Only, RON, Peering, and Security

## IOS-XR 7.7.1 Software Availability
IOS-XR 7.7.1 is Generally Available (GA) for release. 8000, ASR9K 64-bit, NCS5500/NCS5700, NCS560, NCS540, XRv9K, and XRd are supported in this release. Whitebox (SW only) is supported in this release. 

## Overview 
- 


## Segment Routing

Cisco Optimization Engine (COE) v4.0 requires optimization in certain capabilities within SR-PCE. XR 7.7.1 features the ability to configure a centralized solution to override PCC-initiated objectives and help the customer deploy constraints as override actions. 

  1.	Improve automation product 
  2.	Help brown-field client
  3.	Remove limitations on platforms 


### SRv6-Services: 
- L2 EVPN QoS Enhancement
- L3 Services QoS Enhancement

### SR-PCE: Objective override of PCC-Initiated policies
- Several customers (such as Vodafone, Telstra, others) have old devices in the network where, as an example, the old PCC is able to delegate computation of IGP metric policies but does not support a PCC-initiated “low delay” policy.
- In such deployments, a centralized solution (PCE-centric) can be implemented to “override” a PCC-initiated optimization objective (ex: IGP cost) to another objective (ex: delay) and help the customer deploy the intended policy SLA albeit this PCC limitation.

### Crosswork Optimization Engine (COE) 4.0 
- Enable visualization of tree-sid use cases in multicast
- First in industry for customer to visualize their multicast tree live in the network 
- Double COE scale


## EVPN 

- EVPN updates in L2 Gateway provide IGMPv3 Selective multicast (RT-6) w/ Proxy support 

Private Line Emulation (PLE) service is a method for encapsulating high-speed bit-streams as VPWS over packet switched networks (PSN). This emulation suits applications where complete signal transparency is required and data interpretation of the PE would be counterproductive. 
 
•	VPWS (ELINE) – 
	- Private Line Emulation (PLE) – single homing 
•	(L2 + L3) Anycast GW 
	- IGMPv3 Selective multicast (RT-6) w/ Proxy support 

## Distributed Disaggregated Chassis (DDC)
- Peering use cases in BGP flowspec 
- Unicast Reverse Path Forwarding (uRPF) and port mirroring updates for monitoring and mitigation actions for security threats such as DDoS attacks


## Security
IOS XR 7.7.1 contains improvements to strengthen password security among the following platforms: IOS-XR, NCS5000, NCS5500, NCS5700, ASR9000, ASR9900, NCS540, NCS560. With the surge of DDOS based attacks implementing detectPro solution to protect peering use cases. 

## Coming Soon
- EVPN - PLE support 
- Updates to DDC features to support key customers such as AT&T

# IOS-XR 7.7.1 Software PIDs

#### Ordering Information ASR 9000: 
|PID |Description|
|---|---|
| XR-A9K-X64-07.7  |  Cisco IOS XR IP/MPLS Core Software - IOS-XR 64 Bit |
| XR-A9K-X64K9-07.7  | Cisco IOS XR IP/MPLS Core Software 3DES - IOS-XR 64 Bit  |

#### Ordering Information NCS 5500:
| PID  |  Description |
|---|---|
| XR-NC55-PK9-07.07  | Cisco IOS XR IP/MPLS Software 3DES   |
| XR-NC55-P-07.07  | Cisco IOS XR IP/MPLS Software  |
| XR-7.7-TRK  | IOS-XR Software Tracking PID 7.7  |
|XR-7.7-K9-TRK | IOS-XR K9 Software Tracking PID 6.6  |



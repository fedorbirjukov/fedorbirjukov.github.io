---
layout: post
title: Telenet&#58; static IP addresses for LAN connections
---

## Abstract 

Recently I became a private customer of [Telenet](http://telenet.be/). They provided me with a [wireless docsis 3 modem](# "24*8 DOC 3 WIRELESS(DOCSIS)"). It is a pretty white box that can be configured online. Eventually I wanted to distribute some fixed IPs on my LAN. But there was no such option in the modem's settings and the documentation entry on this purpose was out-dated. I contacted tech support but they did not know the answer, as well. Then I asked a friend of mine, [Matthias Verstappen](https://www.facebook.com/matthias.verstappen), and he had a simple answer for me. I summarize it [below](#solution).

## Audience 

Telenet private customers having a 24*8 DOC 3 WIRELESS(DOCSIS) modem and willing to assign fixed IP addresses to some of their devices, such as a file server.

## Constraint

You can not distribute static IP addresses based on the MAC addresses of your devices as there is no such option in the Telenet modem's settings.

## Solution <a name="solution"></a>

Configure your device to use a static IP address instead of getting it through DHCP. You may use any of the addresses between 2 and 49, i.e. 192.168.0.2-49. No configuration of your modem is required.

Note: Addresses between 50 and 99 may be used by Telenet for their digicoders. So, be careful in this range. 

## References

[Telenet Community](https://community.telenet.be/t5/Surfen/Beperken-DHCP-range-op-wireless-router-telenet/m-p/6019#M911)

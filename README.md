# Discord Token Invalidation Repository

This repository exists to identify, invalidate, and remove publicly leaked Discord tokens that appear inside malware payloads.  
The goal is to disrupt malware families that abuse Discord as a command-and-control channel.

## Token Sources

### DISCORDRAT.md
Tokens listed in **DISCORDRAT.md** are collected by crawling the tria.ge malware analysis feed.  
These tokens typically originate from DiscordRAT variants, information stealers, and other payloads embedding Discord bot or user tokens.

### TIP.md
Tokens listed in **TIP.md** come from malware configuration extractions performed at  
https://tip.neiki.dev/  
These entries include C2 credentials and hardcoded tokens found inside analyzed samples.

## Purpose

- Disrupt malware operations that use Discord as infrastructure  
- Maintain a transparent list of leaked, malicious tokens  
- Support automated token revocation processes  
- Assist researchers in tracking Discord-based malware activity

## Disclaimer

All tokens listed here are malicious, publicly leaked, and non-operational at the time of publication.  
No legitimate user or bot tokens are collected or published.

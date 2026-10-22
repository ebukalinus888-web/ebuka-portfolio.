# Basic Windows Connectivity Checks
**Project type:** Practice portfolio project  
**Role demonstrated:** IT Support / Desktop Support

## Objective
Use built-in Windows tools to collect basic network information before escalating a connectivity issue.

## Commands
Open Command Prompt and run the following commands as appropriate:

```text
ipconfig /all
ping <default-gateway-address>
nslookup example.com
tracert example.com
```

## What each command helps check
- `ipconfig /all` displays network adapter settings, IP configuration, gateway, and DNS information.
- `ping` tests basic reachability to a target; a failed ping alone does not prove the target is down because some systems block ping.
- `nslookup` checks whether a domain name can be resolved by DNS.
- `tracert` shows the route Windows attempts to use to reach a destination; some hops may not respond.

## Record findings
- Device/network connection:
- IP address and default gateway (do not publish these details publicly):
- DNS lookup result:
- Target tested:
- Exact error or output:
- Whether other users are affected:
- Next action / escalation:

## Safety
Use these commands only on devices and networks you are authorized to troubleshoot. Do not post private network details or user information in a public portfolio.

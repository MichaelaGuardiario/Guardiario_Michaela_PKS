<img width="797" height="426" alt="image" src="https://github.com/user-attachments/assets/168f9c36-821b-4e7d-bcb2-0e08e1f790fa" />

# Persistence (TA0003)

## Outline
- Persistence
- Account Manipulation
- Boot or Logon Autostart
- Scheduled Tasks
- DLL Hijacking
- Browser Extensions

## Definition
Persistence techniques allow attackers to maintain access to systems even after reboots, password changes, or user logouts.

## Key Categories of Persistence

### Account Manipulation
Attackers create or modify accounts to maintain access.

### Boot or Logon Autostart Execution
Malicious programs automatically run during startup or login.

### Scheduled Tasks
Attackers use built-in task schedulers to execute malware regularly.

### Hijacking Execution Flow
Legitimate applications are manipulated to run malicious code.

### Browser or Application Extensions
Malicious extensions can be used to maintain persistence.

## T1098 Account Manipulation
Attackers add accounts or elevate privileges for persistent access.

## T1547 Boot or Logon Autostart Execution
Registry Run Keys and Startup folders are commonly abused.

## DLL Hijacking
Attackers replace or abuse DLL files to execute malicious code.

## Key Points
- Persistence helps attackers survive system reboots.
- Registry modifications are common persistence methods.
- Defenders should monitor startup locations and scheduled tasks.

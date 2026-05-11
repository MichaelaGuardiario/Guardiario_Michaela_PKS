<img width="800" height="448" alt="image" src="https://github.com/user-attachments/assets/3fc5eb6d-f991-4d1f-aa38-c6cb5c33fdba" />

# Execution (TA0002) - Command and Scripting Interpreter (T1059)

## Outline
- Execution Tactic
- Command and Scripting Interpreter
- Living off the Land
- PowerShell Abuse
- Legitimate Administrative Tools

## Definition
Execution techniques allow attackers to run malicious code on local or remote systems.

## Command and Scripting Interpreter (T1059)
Attackers abuse built-in command-line tools and scripting languages to execute malicious commands.

### Common Interpreters
- PowerShell
- Command Prompt (cmd)
- Bash
- Python
- JavaScript

## Living off the Land
Attackers use legitimate system tools instead of custom malware to avoid detection.

## Why Attackers Use This Technique
- Trusted by antivirus software
- Digitally signed tools
- Already installed on systems

## PowerShell Abuse
PowerShell is commonly used to:
- Download payloads
- Execute encoded commands
- Establish persistence

## Key Points
- T1059 is frequently used in cyber attacks.
- Legitimate tools can become dangerous when abused.
- Monitoring scripting activity is important for defense.

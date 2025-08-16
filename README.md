# # IOS Navigator — Packet Tracer Mini-Lab 🚀
Packet Tracer mini-lab: PC1→S1 console, CLI navigation with context help, EXEC modes, and clock verification, beginner-friendly, portfolio-ready.

---

## Overview
This lab teaches:  
- Connecting **PC1 → S1** via console cable  
- Accessing the CLI  
- Using context-sensitive help (`?`)  
- Switching EXEC modes  
- Setting the clock

---

## Requirements
- Cisco Packet Tracer  
- Topology: **PC1** and **S1** (default factory switch)

---

## Objectives
- Establish basic console connection and access the CLI.  
- Use context-sensitive help to discover command syntax.  
- Navigate EXEC modes (user → privileged → global config).  
- Set and verify the device clock; observe error handling for invalid inputs.

---

### 1. Console Connection
![Console connection between PC1 and S1](images/01-console-connection.png)  
*This screenshot shows the Packet Tracer topology with PC1 connected to Switch S1 using a light-blue console cable.*

---

### 2. Terminal Settings (9600/8/N/1/None)
![Terminal settings dialog in Packet Tracer](images/02-terminal-settings-9600.png)  
*The Terminal Configuration dialog confirms the default serial port settings — Bits per second: 9600, Data bits: 8, Parity: None, Stop bits: 1, Flow control: None.*

---

### 3. Context-Sensitive Help Output
![Cisco IOS context-sensitive help output](images/03-help-output.png)  
*The CLI screen displays the output of Cisco IOS’s context-sensitive help system.*

---

### 4. Privileged EXEC Prompt
![CLI showing transition from user EXEC to privileged EXEC](images/04-privileged-prompt.png)  
*CLI prompt changes from `S1>` (user EXEC mode) to `S1#` (privileged EXEC mode).*

---

### 5. Clock Before/After with Error Example
![Clock output before and after setting time, including error example](images/07-clock-after.png)  
*Displays the clock output prior to any changes, followed by the updated time and date after successful configuration. Also includes an IOS error message generated when attempting to set the clock using invalid values.*

---

## How to View the Lab
1. Download the `.pka` file from this repository.  
2. Open it in Cisco Packet Tracer.  
3. Follow the step-by-step lab instructions in the `Navigate_the_IOS.docx` file.

---

## Repository Contents
- **ios-navigator-packet-tracer-lab.pka** — Packet Tracer lab file.  
- **Navigate_the_IOS.docx** — Detailed lab instructions.  
- **images/** — All screenshots used in this README.

---

## License
MIT License.

e clock command**
1. Show current time:

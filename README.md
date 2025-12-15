*This project has been created as part of the 42 curriculum by student42.*

# NetPractice

## Description
NetPractice is an introductory networking project designed to teach the fundamentals of computer networking.  
The goal of the project is to configure small network topologies so that communication between hosts, routers, and the Internet works correctly.

Through 10 progressive levels, the project focuses on understanding and applying core networking concepts such as IP addressing, subnet masks, default gateways, routing, and the role of switches and routers in a TCP/IP network.

All networks used in this project are simulated and run locally through a web-based training interface.

---

## Instructions

### Running the training interface
1. Download and extract the NetPractice files provided on the project page.
2. Open the file `index.html` in a web browser.
   - **Recommended browser:** Google Chrome or any Chromium-based browser  
   - Firefox may not work due to security restrictions.
3. Enter your 42 login (`student42`) in the interface.
4. Choose either:
   - **Practice mode** (personal configuration), or
   - **Evaluation mode** (random configuration).

### Solving levels
- Each level presents a broken network diagram.
- Modify only the **unshaded fields** (IP addresses, subnet masks, routes).
- Use the **Check again** button to validate your configuration.
- When the level is correct, proceed to the next one.

### Exporting configurations
- After completing **each level**, click **Get my config**.
- Save the exported file.
- Repeat this process for all **10 levels**.

---

## Submission Requirements
- The repository must contain **10 configuration files**, one per level.
- All configuration files must be placed at the **root of the repository**.
- Only the contents of the repository will be evaluated during defense.
- During evaluation, you must be able to manually solve random levels **without external tools** (except a basic calculator such as `bc`).

---

## Resources

### Networking concepts studied
- TCP/IP addressing
- IPv4 address structure
- Subnet masks and CIDR notation
- Network and broadcast addresses
- Default gateways
- Static routing
- Routers vs switches
- OSI model (basic understanding)
- Forward and reverse routing paths

### References
- RFC 791 – Internet Protocol
- RFC 950 – Internet Standard Subnetting Procedure
- Cisco Networking Basics documentation
- 42 NetPractice subject PDF

### Use of AI
AI tools were used **as a learning aid only**, not as a replacement for understanding.  
Specifically, AI was used to:
- Clarify networking concepts such as subnetting and routing
- Help reason about configuration errors (e.g. missing routes or incorrect masks)
- Assist in structuring and writing this README file

All AI-generated explanations were reviewed, verified, and tested directly in the NetPractice interface.  
Only configurations fully understood by the student were used.

---

## Notes
- Correct routing requires **both forward and return paths**.
- Subnet masks must match on all devices within the same network.
- Routes must always point to a **reachable next hop**.
- Using network addresses instead of host addresses in routing tables is critical.

---

## Author
- **student42**

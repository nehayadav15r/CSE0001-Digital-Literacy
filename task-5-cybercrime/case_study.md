# Cybercrime Case Study: Phishing

---

## Selected Cybercrime: Phishing
**Definition:** Phishing is a type of social engineering attack where an attacker sends a fraudulent message designed to trick a human victim into revealing sensitive information or to deploy malicious software on the victim's infrastructure.

---

## Case Study: The "Urgent Payroll Update" Incident

### Description of the Crime
Phishing remains one of the most prolific cybercrimes due to its reliance on human psychology rather than technical exploits alone. In this specific scenario, attackers impersonate a trusted corporate entity—the Human Resources (HR) department—to steal employee credentials and gain access to internal financial systems.

### Step-by-Step Execution
1.  **Reconnaissance:** The attacker identifies a target company and its internal naming conventions for email addresses (e.g., `firstname.lastname@company.com`).
2.  **Domain Spoofing:** A look-alike domain is registered, such as `hr-dept-secure.com`, which mimics the official corporate style.
3.  **The Hook:** An email is broadcast to the staff with a high-priority subject line: *"Mandatory Action: Update your Banking Details for 2024 Tax Compliance."*
4.  **The Deception:** The email contains a link to a "Secure Employee Portal." This portal is a pixel-perfect replica of the company’s actual login page.
5.  **Data Harvest:** Employees enter their corporate usernames and passwords. These are instantly sent to the attacker’s server.
6.  **Exploitation:** The attacker uses these credentials to log into the real company network, diverting several employees' direct deposits to untraceable offshore accounts.

### Target Audience
The primary targets are **mid-to-large-scale corporate employees**, particularly those in administrative, sales, or operations roles who frequently handle digital paperwork and may be less scrutinized by high-level IT security protocols.

### Consequences
The immediate consequence was a **financial loss of $62,000** in stolen wages. Beyond the money, the company suffered a **loss of employee trust**, incurred high **forensic audit costs**, and faced potential **regulatory fines** for failing to protect internal data.

---

## Key Pointers (Red Flags)

* **Artificial Urgency:** Demands for "Immediate Action" or "Account Deletion" threats.
* **Mismatched URLs:** The link text looks legitimate, but hovering over it reveals a different address.
* **Generic Salutations:** Using "Dear Valued Employee" instead of your actual name.
* **Sender Address Discrepancy:** The name says "HR Department" but the email address is `support@unknown-domain.com`.

---

## Statistical Visualizations

### Attack Vector Distribution
> This chart shows how Phishing attacks are typically delivered.

```mermaid
pie title Attack Delivery Methods
    "Email" : 65
    "SMS (Smishing)" : 15
    "Social Media" : 10
    "Voice (Vishing)" : 10



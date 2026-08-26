# 📧 Ex.No.4 – Analyze Email Headers and Detect Email Spoofing Using MHA

## 🎯 Aim

To analyze email headers and detect email spoofing using **MHA
(Mail Header Analyzer)**.

## 📖 Procedure

### 1. Access the Email Header

- **Gmail:** Open email → Three dots → **Show original**
- **Outlook:** Open email → File → Properties → **Internet headers**
- **Yahoo:** Open email → Three dots → **View raw message**

### 2. Copy the Email Header

Copy the complete email header containing metadata about the email's
journey from sender to recipient.

### 3. Identify Key Header Fields

| Header | Description |
|---|---|
| `From` | Sender's email address |
| `To` | Recipient's email address |
| `Date` | Date and time the email was sent |
| `Subject` | Subject of the email |
| `Return-Path` | Return address |
| `Received` | Servers through which the email passed |
| `Message-ID` | Unique email identifier |
| `SPF` | Sender authentication |
| `DKIM` | Email integrity verification |

### 4. Analyze `Received` Fields

The `Received` fields show the path taken by the email.

Check:

- Sending server hostname/IP
- Receiving server hostname/IP
- Date and time
- Unexpected servers or routing

### 5. Check IP Addresses and Hostnames

Use WHOIS or IP lookup tools to check:

- IP ownership
- Geographical location
- Hostname
- Whether the IP belongs to the expected mail server

### 6. Examine SPF, DKIM and DMARC

#### SPF


<img width="1913" height="907" alt="Screenshot 2026-08-26 110522" src="https://github.com/user-attachments/assets/d305aedd-dbb9-4b1d-a2ed-0a29c34c26b8" />
<img width="1917" height="886" alt="Screenshot 2026-08-26 110542" src="https://github.com/user-attachments/assets/433b33f5-5f29-4519-968b-f13164831e77" />
<img width="1911" height="647" alt="Screenshot 2026-08-26 110611" src="https://github.com/user-attachments/assets/e07775d1-20df-474e-986b-839ce3ccf54e" />
<img width="741" height="197" alt="Screenshot 2026-08-26 110713" src="https://github.com/user-attachments/assets/2152e10b-4332-4951-8551-e49e7ad61cb8" />
<img width="1022" height="700" alt="Screenshot 2026-08-26 110854" src="https://github.com/user-attachments/assets/f20f1cc9-fb90-437a-81a6-4e60cc038981" />
<img width="967" height="237" alt="Screenshot 2026-08-26 110721" src="https://github.com/user-attachments/assets/f2f88401-c02a-422b-9be9-b1c7224b0e9d" />
<img width="1881" height="658" alt="Screenshot 2026-08-26 110942" src="https://github.com/user-attachments/assets/333fa87c-e6bc-4e00-8294-28e72843b758" />




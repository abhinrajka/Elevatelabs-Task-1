### 🔍 Analysis of Nmap Scan Results

The scan was performed using Nmap on the subnet `10.67.159.0/24`. Three live hosts were detected.

#### ✅ Active Devices:

| IP Address      | Status | Notes                                 |
|------------------|--------|----------------------------------------|
| 10.67.159.22     | ✅ Up   | Open port 53 (DNS), MAC: Unknown       |
| 10.67.159.144    | ✅ Up   | All ports filtered                     |
| 10.67.159.85     | ✅ Up   | All ports closed                       |

#### 🚪 Open Port Detected:
- **10.67.159.22 → Port 53 (DNS)** – Public DNS service should be restricted if not required.

#### ⚠️ Security Recommendations:
- Review services on 10.67.159.22.
- Disable unused ports.
- Keep devices patched and monitored.

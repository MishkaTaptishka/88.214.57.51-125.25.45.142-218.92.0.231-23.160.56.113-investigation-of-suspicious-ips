# 🛡️ IP Reputation Report – XorDDoS Investigation

This report outlines the reputation and abuse history of IP addresses observed during the XorDDoS investigation, including those used for outbound connections and potential C2 activity.

---

## 🔍 Investigated IP Addresses

---

### **1. IP Address: 185.199.109.133**

- **Organization:** GitHub, Inc.  
- **Location:** San Francisco, California, USA  
- **Reported Activity:** Reported 113 times on AbuseIPDB with a 10% confidence of abuse. Associated with phishing, spam, and port scanning activity. Reported as malicious on VirusTotal by CRDF.

---

### **2. IP Address: 185.199.111.133**

- **Organization:** GitHub, Inc.  
- **Location:** San Francisco, California, USA  
- **Reported Activity:** Reported 84 times on AbuseIPDB. Known for brute-force attempts and port scanning. Reported as malware on VirusTotal by MalwareURL.

---

### **3. IP Address: 185.199.108.133**

- **Organization:** GitHub, Inc.  
- **Location:** San Francisco, California, USA  
- **Reported Activity:** Reported 113 times on AbuseIPDB. Involved in scanning and suspected hacking behavior.

---

### **4. IP Address: 185.199.110.133**

- **Organization:** GitHub, Inc.  
- **Location:** San Francisco, California, USA  
- **Reported Activity:** Reported 99 times on AbuseIPDB. Linked to unauthorized scanning and intrusion attempts.

---

### **5. IP Address: 169.239.130.5**

- **Organization:** Alsycon B.V.  
- **Location:** Netherlands  
- **Reported Activity:** Reported as malicious on VirusTotal by Criminal IP. 

---

### **6. IP Address: 172.82.91.106**

- **Organization:** FyfeWeb Ltd  
- **Location:** US  
- **Reported Activity:** No malicious activity reported.

---

### **7. IP Address: 23.160.56.113**

- **Organization:** Unknown  
- **Location:** Undisclosed  
- **Reported Activity:** No abuse reports found in public reputation databases.

---

### **8. IP Address: 218.92.0.231**

- **Organization:** CHINANET Jiangsu Province Network  
- **Location:** China  
- **Reported Activity:** Reported 45,646 times on AbuseIPDB with a 100% confidence of abuse. Frequently used in SSH brute-force campaigns against root accounts. Reported as malicious, phishing, and malware on VirusTotal by several vendors.

---

### **9. IP Address: 125.25.45.142**

- **Organization:**  TOT Public Company Limited  
- **Location:** Thailand  
- **Reported Activity:** Reported as malware and suspicious on VirusTotal by several vendors.

---

### **10. IP Address: 88.214.57.51**

- **Organization:** aurologic GmbH  
- **Location:** Germany  
- **Reported Activity:** Reported as malicious on VirusTotal by several vendors.

---

## ✅ Recommendations

- **GitHub IPs (`185.199.x.x`):** may be abused to host or retrieve payloads; closely monitor for suspicious downloads or script executions from GitHub domains.
- **218.92.0.231**: 100% certainty threat actor IP, block immediately.
- **125.25.45.142, 88.214.57.51**: threat actor IPs; flag for alerting and further research.
- **23.160.56.113**: treat with caution; monitor communications and inspect DNS resolution paths or payload sources.

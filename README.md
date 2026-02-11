<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&duration=4000&pause=1000&color=00FF9D&center=true&vCenter=true&width=600&lines=Hi+👋,+I'm+Nimesh+Akalanka;SOC+Analyst+in+Progress;Blue+Team+%7C+Threat+Detection+%7C+Lab+Builder" alt="Typing SVG" />
</div>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/nimesh23"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:desilvanimesha684@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
  <img src="https://komarev.com/ghpvc/?username=nimesh895&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="Profile views"/>
</p>

## 🖥️ SOC Terminal – Live Feed Simulation

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=4000&pause=2000&color=00FF41&center=true&vCenter=true&width=500&lines=Initializing+Blue+Team+Console...;Wazuh+Manager+Online;Sigma+Rules+Compiling...;Threat+Hunt+Active;Endpoint+Agents+Reporting...;Stay+Vigilant+🛡️" alt="SOC Console Initialization"/>
</div>

<br>

<div align="center">
  <pre style="background: #0d1117; color: #00ff41; font-family: 'Courier New', Consolas, monospace; padding: 20px; border-radius: 10px; border: 1px solid #00ff4144; max-width: 800px; text-align: left; overflow-x: auto; box-shadow: 0 0 15px rgba(0,255,65,0.15);">
nimesh@blue-team:~/soc-lab $ ./wazuh-status.sh --full
[+] Wazuh manager .............. RUNNING (v4.x cluster healthy)
[+] Wazuh API .................. RUNNING (port 55000 | auth enabled)
[+] Filebeat → Sentinel ........ CONNECTED (Azure ingestion active)
[+] Sysmon + Custom Decoders ... 18 loaded | 5 custom active
[+] Sigma Rules Active ......... 47 (MITRE ATT&CK Coverage: 68% | T1566 Phishing boosted)
[!] Alerts (last 24h) .......... 142 (High: 19 | Critical: 3)
[!] Open Incidents ............. 2 → Phishing T1566.001 | Brute-force T1110

nimesh@blue-team:~/soc-lab $ sigma convert -t splunk -p windows-sysmon rules/windows/phishing_*.yml --output sentinel/
[SUCCESS] 12 rules compiled | 0 errors
[OUTPUT] → Ready for Microsoft Sentinel ingestion
[SUGGESTION] Deploy playbook: azure/automation/phishing-alert-enrichment.yml

nimesh@blue-team:~/soc-lab $ tshark -r capture.pcap -Y "http.request.method == POST && http.request.uri contains login" -T fields -e http.request.uri -e http.request.full_uri | grep -i credential
capture stats → 47 packets | 3 suspicious credential POSTs flagged (potential T1555)

nimesh@blue-team:~/soc-lab $ echo "Stay vigilant" | figlet -f cybermedium
  ____ _ __ ___ _ _ _
 / ___|| |_ __ _ _ __ \ \ / (_) | | | |
 \___ \| __/ _` | '_ \ \ \ / /| | | |_| |
  ___) | || (_| | | | | \ V / | | | _ |
 |____/ \__\__,_|_| |_| \_/ |_|_| |_| 

nimesh@blue-team:~/soc-lab $ threat-hunt --technique T1003.001
[HUNT] Searching lsass dump patterns... 0 IOCs found
[HUNT] Monitoring credential access... ongoing
  </pre>
</div>

<br>

---

### 🛡️ About Me

Passionate **blue team defender** building realistic SOC homelabs from scratch.  
Deep into threat detection, SIEM deployment (Wazuh, Microsoft Sentinel), endpoint monitoring, phishing analysis, malware dissection, and turning open-source tools into production-grade security practice.

- 🔭 Actively building & documenting **Wazuh-based SOC labs**, Azure security monitoring, phishing detection with ML, and CVE exploitation analysis
- 🌱 Strengthening skills in SOC operations, threat hunting, MITRE ATT&CK, detection engineering, and cloud security
- 👯 Open to collaborate on: Wazuh custom rules, Sigma rule development, Azure Sentinel playbooks, phishing classifiers, blue-team simulations
- 🤝 Seeking feedback on: Lab architecture, detection logic, adversary emulation realism, and documentation quality
- 💬 Ask me about: Wazuh deployment & tuning, Azure monitoring, phishing email analysis, Follina CVE deep dive, Splunk basics, Wireshark/Nmap
- 📫 Reach me: **desilvanimesha684@gmail.com**
- ⚡ Fun fact: I turn a weekend lab idea into a fully documented GitHub project faster than most finish a single tutorial 😄

---

### 🎖️ Certifications & Achievements

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Certified_Azure_Fundamentals_(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AZ-900" title="Dec 2025"/>
  <img src="https://img.shields.io/badge/Cisco_Networking_Basics-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Networking Basics" title="Jan 2024"/>
  <img src="https://img.shields.io/badge/Introduction_to_Splunk-FF6A00?style=for-the-badge&logo=splunk&logoColor=white" alt="Intro to Splunk" title="Feb 2024"/>
  <img src="https://img.shields.io/badge/Understanding_Threats_and_Attacks-FF6A00?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk Threats & Attacks" title="Apr 2024"/>
  <img src="https://img.shields.io/badge/Qualys_Reporting_Strategies_and_Best_Practices-00AEEF?style=for-the-badge&logo=qualys&logoColor=white" alt="Qualys Reporting" title="Jul 2025"/>
  <img src="https://img.shields.io/badge/Web_Design_(HTML_CSS_JS_MySQL)-007BFF?style=for-the-badge&logo=html5&logoColor=white" alt="UoM Web Design" title="Open University of Moratuwa"/>
</p>

---

### 🛠️ Arsenal & Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,linux,python,docker,bash,git,vscode,html,css,js,php,mysql,pandas,powershell,wazuh&perline=8" alt="Skills Icons"/>
</p>

**Core tools in my labs:**
- **SIEM/XDR**: Wazuh, Microsoft Sentinel
- **Detection & Response**: Custom decoders, Sigma rules, ML-based phishing detection
- **Network & Endpoint**: Suricata IDS, Wireshark, Nmap, OpenVPN, Tshark
- **Analysis**: Static malware analysis, CVE research (e.g., Follina), VirusTotal
- **Infrastructure**: VirtualBox, Azure VMs, Ubuntu/Windows endpoints
- **Automation**: Python (scikit-learn, NLTK, pandas), Bash, PowerShell

---

### 🔥 Featured Projects

- **[wazuh-soc-homelab](https://github.com/nimesh895/wazuh-soc-homelab)**  
  Full Wazuh SIEM homelab with custom rules, attack simulations & documentation

- **[wazuh-bruteforce-fim-homelab](https://github.com/nimesh895/wazuh-bruteforce-fim-homelab)**  
  Brute-force RDP detection + File Integrity Monitoring (FIM) lab

- **[phishing-email-detection-soc](https://github.com/nimesh895/phishing-email-detection-soc)**  
  NLP + Machine Learning phishing email classifier

- **[azure-security-monitoring-lab](https://github.com/nimesh895/azure-security-monitoring-lab)**  
  Azure-native monitoring with Sentinel, alerts & playbooks

- **[Malware-Analysis-Follina-CVE-2022-30190](https://github.com/nimesh895/Malware-Analysis-Follina-CVE-2022-30190)**  
  Deep dive into Follina vulnerability & detection rules

---

### 🌐 Let's Connect & Collaborate

<p align="center">
  <a href="https://www.linkedin.com/in/nimesh23">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="Connect on LinkedIn"/>
  </a>
  <a href="https://github.com/nimesh895">
    <img src="https://img.shields.io/badge/GitHub-@nimesh895-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

Always open to:
- Feedback on labs and write-ups
- Collaboration on detection rules, Sigma conversions, SOC projects
- Discussions about blue team tools, Wazuh tuning, threat hunting

Feel free to open an issue or send an email — let's build better defenses together! 🛡️🔥

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&text=Stay+Secure+%F0%9F%9B%A1%EF%B8%8F&fontSize=30&fontColor=fff&animation=twinkling" alt="Waving footer"/>
</div>

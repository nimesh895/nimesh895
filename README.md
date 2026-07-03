<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,100:00FF9D&height=190&section=header&text=NIMESH%20AKALANKA&fontSize=42&fontColor=00FF9D&fontAlignY=36&animation=fadeIn&desc=Blue%20Team%20%7C%20Detection%20Engineering%20%7C%2075%2B%20Attack%20Sims&descAlignY=56&descSize=15&descColor=8f8f8f" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=00FF9D&center=true&vCenter=true&width=720&lines=root%40soc-lab%3A~%24+whoami;nimesh_akalanka+%E2%80%94+cyber+security%2C+SLIIT;root%40soc-lab%3A~%24+cat+career_target.log;seeking%3A+remote+SOC+%2F+NOC+%2F+IT+support+roles;root%40soc-lab%3A~%24+status+--current;SY0-701+exam%3A+scheduled+%7C+labs%3A+75%2B+logged" alt="terminal typing animation" />

<br>

<a href="https://www.linkedin.com/in/nimesh23"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:desilvanimesha684@gmail.com"><img src="https://img.shields.io/badge/Email-reach%20out-00FF9D?style=flat-square&logo=gmail&logoColor=black"/></a>
<img src="https://komarev.com/ghpvc/?username=nimesh895&label=profile+views&color=00FF9D&style=flat-square"/>
<img src="https://img.shields.io/badge/Security%2B%20SY0--701-in%20progress-0f0f0f?style=flat-square&logo=comptia&logoColor=00FF9D&labelColor=0f0f0f"/>

</div>

<br>

## `> case file — who's investigating`

I don't post "SOC analyst in progress" badges. I break things in a lab, watch what the SIEM does or doesn't catch, and fix the detection gap. That loop — attack, observe, tune, document — is the whole profile.

Currently: final-stretch prep for **CompTIA Security+ SY0-701**, applying to remote SOC / NOC / IT support roles, and closing the Splunk/QRadar + KQL gap that keeps showing up in my own job-req audits.

<br>

## `> incident log — featured investigations`

<table>
<tr>
<td width="50%" valign="top">

**`INC-001` · Wazuh SOC Homelab**
<br>*Status: 🟢 Active · MITRE-mapped*

Full SIEM build from bare VM to tuned detections. Custom rules and decoders for phishing, brute force, and credential dumping — not the defaults, ones I wrote after triggering the attack myself first.

`T1566` `T1110` `T1003`
[→ wazuh-soc-homelab](https://github.com/nimesh895/wazuh-soc-homelab)

</td>
<td width="50%" valign="top">

**`INC-002` · Phishing ML Detector**
<br>*Status: 🟢 Deployed · Dataset → Model → Prod*

Trained a classifier on real phishing corpora instead of relying on signature matching alone. Documented where the model fails, which matters more than where it works.

`T1566.001`
[→ phishing-email-detection-soc](https://github.com/nimesh895/phishing-email-detection-soc)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**`INC-003` · Azure Sentinel Monitoring**
<br>*Status: 🟢 Active · Playbook automation*

Alert enrichment and automated response playbooks in Sentinel — the cloud-side counterpart to the on-prem Wazuh stack, so the same attack gets caught whichever way it comes in.

`T1059`
[→ azure-security-monitoring-lab](https://github.com/nimesh895/azure-security-monitoring-lab)

</td>
<td width="50%" valign="top">

**`INC-004` · RDP Brute-Force + FIM**
<br>*Status: ⚪ Closed · Root-caused*

Password-spray simulation against RDP paired with file integrity monitoring, to catch both the noisy attack and the quiet aftermath.

`T1110.001`
[→ wazuh-bruteforce-fim-homelab](https://github.com/nimesh895/wazuh-bruteforce-fim-homelab)

</td>
</tr>
<tr>
<td colspan="2">

**`INC-005` · Suricata IDS Integration** · *Status: 🟡 Open — next in queue*
<br>Network-layer detection to sit alongside the host-layer Wazuh stack. Goal: catch lateral movement that endpoint logging alone misses.

</td>
</tr>
</table>

<br>

## `> skill matrix — claim, evidence, not a badge`

| Domain | What I can actually do | Where it's proven |
|---|---|---|
| SIEM / Detection Engineering | Write custom Wazuh rules & decoders from scratch, not just enable presets | `wazuh-soc-homelab` |
| Cloud Security Monitoring | Configure Sentinel alerting + response playbooks | `azure-security-monitoring-lab` |
| Malware / CVE Analysis | Static analysis and chain reconstruction (Follina, CVE-2022-30190) | homelab write-ups |
| Applied ML for Security | Build and evaluate a phishing classifier end-to-end | `phishing-email-detection-soc` |
| Network Forensics | Wireshark, Nmap, Suricata IDS tuning | lab notebooks |
| Scripting / Automation | Python (pandas, scikit-learn, NLTK), Bash, PowerShell | across repos |

**Actively closing:** Splunk/QRadar hands-on depth, KQL fluency, AZ-500.

<div align="center">
<img src="https://skillicons.dev/icons?i=azure,linux,python,docker,bash,git,html,css,js,mysql,powershell&perline=11" alt="tools"/>
</div>

<br>

## `> certifications`

<div align="center">

<img src="https://img.shields.io/badge/AZ--900-Azure%20Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Splunk-Intro%20%2B%20Threats%20%26%20Attacks-FF6A00?style=for-the-badge&logo=splunk&logoColor=white"/>
<img src="https://img.shields.io/badge/Qualys-Reporting%20Strategies-00AEEF?style=for-the-badge&logo=qualys&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/Cisco-Networking%20Basics-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
<img src="https://img.shields.io/badge/UoM-Web%20Design-007BFF?style=for-the-badge&logo=htmx&logoColor=white"/>
<img src="https://img.shields.io/badge/Security%2B%20SY0--701-exam%20scheduled-0f0f0f?style=for-the-badge&logo=comptia&logoColor=00FF9D"/>

</div>

<br>

## `> roadmap — next 24 months`

```
[####------] Splunk / QRadar hands-on depth        in progress
[###-------] KQL fluency                            in progress
[----------] AZ-500 certification                    queued
[##########] Security+ SY0-701                       exam scheduled
[#######---] Suricata IDS lab (INC-005)              building
```

<br>

## `> live telemetry`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nimesh895&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF9D&icon_color=00FF9D&text_color=c9d1d9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nimesh895&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF9D&text_color=c9d1d9"/>

<br><br>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=nimesh895&theme=highcontrast&hide_border=true&background=0d1117&ring=00FF9D&fire=00FF9D&currStreakLabel=00FF9D"/>
<img src="https://github-profile-trophy.vercel.app/?username=nimesh895&theme=algolia&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8" height="165"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nimesh895&theme=react-dark&hide_border=true&bg_color=0d1117&color=00FF9D&line=00FF9D&point=ffffff" width="97%"/>

<br><br>

<!-- requires the snake workflow below to be added to this repo -->
<img src="https://raw.githubusercontent.com/nimesh895/nimesh895/output/github-contribution-grid-snake.svg" width="97%" alt="contribution snake — activates once the workflow is added"/>

</div>

<br>

## `> how this profile behaves`

```
IF you need someone who documents every lab like it'll be audited     → we should talk
IF you're hiring remote-first SOC / NOC / IT support / IAM roles      → I'm applying
IF you want to co-build Sigma rules or Sentinel playbooks             → open an issue
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF9D,100:0f0f0f&height=100&section=footer" width="100%"/>
</div>

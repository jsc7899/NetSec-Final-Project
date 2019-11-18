# Final Project Proposal

### Building a Honeypot

* Amazon Web Services
  * EC2 t2.micro instance 
  * Ubuntu Server 18 image

### Logging

* [Kippo](https://github.com/desaster/kippo): Medium interaction, SSH based honeypot
* [Dionaea](https://github.com/DinoTools/dionaea): Capture malware, simulate vulnerabilities
* [SNARE](https://github.com/mushorg/snare): Web application honeypot

### IDS

* [Snort](https://www.snort.org/): Intrusion Detection System

### Data Analysis

* [Tanner](https://github.com/mushorg/tanner/): Analyze data from SNARE

### Considerations

* AWS security settings
  * Firewall rules
  * Security groups/policies
* AWS might shutdown our server. In that case, we'll have a backup and move everything to a private server. 
* If there's not enough attack data, we'll attack the server ourselves to demonstrate.

### Further Plans (if time permits)

* Add more AWS servers networked together
* Implement an intrusion prevention system to actively defend against attacks

### Research

1. [Intrusion Detection System Using Raspberry PI Honeypot in Network Security](https://pdfs.semanticscholar.org/9c2e/b0a9817be134c28c73c24a73600dd1cd15b8.pdf)
2. [Honeypot in Network Security: A Survey](https://www.researchgate.net/profile/Abhishek_Mairh/publication/220846415_Honeypot_in_network_security_A_survey/links/562a830f08aef25a24401f57/Honeypot-in-network-security-A-survey.pdf)
3. [“Honeynets: High Value Security Data”: Analysis of real attacks launched at a honeypot](https://www.sciencedirect.com/science/article/pii/S1353485803008080)
4. [A hybrid honeypot framework for improving intrusion detection systems in protecting organizational networks](https://www.sciencedirect.com/science/article/pii/S0167404806000587)
5. [Rapid 7's AWS Honeypots](https://insightidr.help.rapid7.com/docs/aws-honeypots)
6. [Deploying a Honeypot on AWS](https://medium.com/@sudojune/deploying-a-honeypot-on-aws-5bb414753f32)






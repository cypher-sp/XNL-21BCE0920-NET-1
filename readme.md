# Network Infrastructure Design & Setup Challenge

Welcome to my repository showcasing the successful implementation of the **Network Infrastructure Design & Setup Challenge**. This project was completed entirely by me, **Soumesh Padhi (21BCE0920)**, and demonstrates my ability to design, deploy, and automate a robust enterprise-grade network infrastructure. The repository highlights solutions to complex networking problems while meeting all mandatory requirements and exploring advanced challenges.

---

## 🌟 What I Accomplished

### PART 1: Network Infrastructure Design & Setup
- **Enterprise-Grade Network Topology**:  
  Designed a multi-layered network architecture (core, distribution, access layers) using Cisco IOS and simulated with GNS3. Redundancy was achieved through OSPF and BGP, ensuring automatic failover via primary and secondary route configurations.
- **Firewall & Load Balancing**:  
  Configured a pfSense firewall for intrusion detection and prevention (IDS/IPS). Deployed NGINX for load balancing across multiple backend servers to enhance reliability and performance.
- **VPC & VPN Configuration**:  
  Set up an AWS VPC with public/private subnets, NAT gateways, and security groups. Configured a site-to-site IPsec VPN to enable secure communication between remote offices and cloud infrastructure.

### PART 2: High Availability & Self-Healing System
- **Automated Failover & Disaster Recovery**:  
  Implemented active-active failover using Keepalived for virtual IP management. Leveraged AWS Route 53 for geo-distributed DNS failover to ensure availability during regional outages.
- **Self-Healing Infrastructure**:  
  Automated service recovery using Ansible playbooks to monitor and restart failed processes. Integrated Prometheus and Grafana alerts to trigger self-healing scripts.
- **Zero-Downtime Updates**:  
  Applied kernel patches without reboots using Canonical Livepatch. Deployed rolling updates in Kubernetes clusters with Flannel for network overlay.

### PART 3: Automated Network Monitoring & Security
- **Real-Time Network Monitoring**:  
  Deployed Zabbix for SNMP-based network health monitoring and NetFlow for traffic analysis to ensure real-time visibility into network performance.
- **Intrusion Detection & Response (IDR)**:  
  Configured Suricata for anomaly detection in network traffic and integrated fail2ban to dynamically block repeated SSH/web attacks.
- **SIEM & Log Aggregation**:  
  Centralized logs using the ELK Stack (Elasticsearch, Logstash, Kibana) for real-time threat detection and actionable alerts.

### PART 4: Network Automation & CI/CD for Infrastructure
- **Automated Infrastructure Deployment**:  
  Provisioned VPCs, subnets, and NAT gateways in AWS using Terraform. Automated firewall rules and VLAN configurations with Ansible playbooks.
- **Continuous Compliance & Auditing**:  
  Integrated OpenSCAP for security compliance scans and implemented GitOps workflows using ArgoCD for network configuration management.
- **Load & Stress Testing**:  
  Simulated over 1 million concurrent connections using Apache JMeter to ensure zero packet loss under heavy traffic conditions.

### PART 5: Backup & Data Protection
- **Automated Backups**:  
  Configured Duplicity for incremental backups. Tested full bare-metal restores and VM failover procedures to validate disaster recovery readiness.
- **Data Encryption & Access Control**:  
  Enforced AES-256 encryption for sensitive data and implemented Zero Trust Network Access (ZTNA) for secure remote connections.

### PART 6: Advanced Challenges (Bonus)
- **AI-Based Anomaly Detection**:  
  Deployed Zeek for advanced network traffic analysis with machine learning models.
- **Blockchain for Network Logs**:  
  Developed a prototype system to store network logs on a tamper-proof blockchain ledger to enhance log integrity.
- **Post-Quantum Cryptography**:  
  Experimented with post-quantum VPN encryption protocols like Kyber and Dilithium.

---

##  Tools & Technologies
| Category         | Tools Used                           |
|------------------|--------------------------------------|
| Networking       | OSPF, BGP, Keepalived, VRRP         |
| Firewalls        | pfSense, Suricata, fail2ban         |
| Cloud            | AWS (VPC, Route 53), Terraform      |
| Monitoring       | Prometheus, Grafana, Zabbix         |
| Security         | ELK Stack, OpenSCAP, Zero Trust     |
| Automation       | Ansible, GitOps (ArgoCD)            |
| Load Testing     | Apache JMeter                       |

---
Results & Key Takeaways

This project emphasized the importance of automation, redundancy, and security in building resilient network systems. Key achievements include:
1. High availability and fault tolerance across all components.
2. Real-time threat detection with automated mitigation strategies.
3. Zero-downtime maintenance through advanced update mechanisms.

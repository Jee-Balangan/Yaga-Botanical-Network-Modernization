# Findings and Recommendations

## Key Findings

### 1. Limited Asset Visibility

Yagé Botanicals did not have a complete inventory of its hardware, software, and data.

This made it harder to identify outdated systems, understand dependencies, and prioritize security improvements.

### 2. Outdated Systems Increased Risk

The environment included outdated servers, workstations, and older Windows-based business systems.

Missing updates and unsupported software increased the risk of exploitation and operational disruption.

### 3. Network Segmentation Was Limited

The network required stronger internal segmentation.

The proposal recommended VLANs to separate sensitive systems, such as accounting and inventory, from general user devices and reduce the potential for lateral movement.

### 4. Identity and Access Controls Needed Improvement

Privileged accounts required stronger protection.

The proposal recommended implementing MFA for administrative users first, with the option to expand MFA to other users over time.

### 5. Perimeter Security Needed Attention

The UTM firewall subscription had expired and required renewal.

The proposal recommended restoring firewall protections and applying more restrictive rules to reduce unnecessary network exposure.

### 6. Personal Devices Created Endpoint Risk

Employees were using personal devices in the environment.

A formal BYOD policy and SaaS-based MDM solution were recommended to enforce security requirements such as antivirus, firewalls, and secure configurations.

### 7. Monitoring and Response Capabilities Were Limited

The environment needed better centralized visibility across both network and security activity.

The proposal recommended a Hybrid SNOC approach using centralized monitoring tools such as Microsoft Sentinel or Splunk, along with SOAR automation for common response tasks.

### 8. Backup and Recovery Planning Needed Improvement

Yagé lacked a strong backup and disaster recovery process.

The proposal recommended secure cloud-based backups, a documented disaster recovery plan, and regular backup testing.

## Recommendations

### Improve Asset Management

- Conduct a complete hardware and software inventory
- Categorize assets by type and business use
- Identify critical systems and dependencies
- Use automated discovery tools where possible

### Strengthen Baseline Security

- Apply critical patches and updates
- Implement MFA for privileged accounts
- Segment the network with VLANs
- Renew and reconfigure the UTM firewall
- Implement MDM for employee-owned devices
- Provide security-awareness training

### Modernize Infrastructure

- Upgrade outdated Active Directory infrastructure
- Consolidate or retire unnecessary servers
- Improve network connectivity
- Use a phased hybrid cloud migration strategy
- Use secure connectivity between cloud and on-premises systems
- Automate patch management

### Improve Monitoring and Response

- Centralize security and network monitoring
- Use tools such as Microsoft Sentinel or Splunk
- Introduce SOAR automation for common alerts
- Monitor access to critical data
- Conduct regular threat reviews
- Track uptime and incident response performance

### Improve Operational Resilience

- Develop formal IT policies
- Document standard operating procedures
- Implement remote monitoring and management tools
- Centralize IT documentation
- Establish secure backups
- Create and test a disaster recovery plan

## Key Lesson

The assessment showed that modernization does not need to happen all at once.

Starting with asset visibility and foundational security controls makes it easier to prioritize larger improvements such as network segmentation, hybrid cloud migration, centralized monitoring, and recovery planning.

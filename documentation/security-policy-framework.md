# Security Policy Framework

## Project Context

This document reorganizes an Information Systems Security Policy (ISSP) that I originally completed for an Introduction to Information Security course in October 2024.

The policy was created for **Swift**, a fictional student transportation platform connecting students, parents, drivers, schools, and company personnel. The system was designed to handle information such as student records, transportation routes, schedules, account information, and system activity.

> This is a conceptual academic project. The controls described here were proposed for a fictional organization and were not implemented or tested in a production environment.

## Security Objectives

The framework was designed to support:

- Confidentiality of student, parent, employee, route, and account information
- Integrity of system records and administrative changes
- Availability of transportation and communication services
- Authentication of users before access is granted
- Authorization based on roles and responsibilities
- Accountability through logging, monitoring, and approval processes

## Scope

The original policy applied to:

- Company employees and management
- Students and parents
- Drivers
- Participating schools
- Approved third-party partners
- Local systems, network systems, databases, applications, and connected services

## Governance and Responsibilities

### Executive Management

Executive leadership, including the CIO and CTO, was responsible for:

- Establishing organizational and technology goals
- Coordinating responsibilities across departments
- Allocating resources
- Supporting risk and incident-response decisions
- Staying informed about technology and security developments

### Chief Information Security Officer

The proposed CISO responsibilities included:

- Establishing the organization’s overall security direction
- Advising senior management about risk and security posture
- Developing and approving policies and procedures
- Reviewing policies on a recurring basis
- Tracking security threats and trends
- Integrating security requirements into organizational planning
- Overseeing compliance and security reporting

### Security Representative

The security representative was responsible for:

- Supervising security incidents and vulnerabilities
- Identifying security violations
- Documenting and reporting violations
- Supporting the availability of infrastructure and services

### IT Management

IT management was responsible for:

- Technical support and troubleshooting
- System maintenance and updates
- Staff education
- Implementing approved controls and procedures

### Workforce

Members of the workforce were responsible for:

- Completing security training
- Following policies and procedures
- Recognizing and reporting possible threats
- Taking appropriate action when an account or system may be compromised

## Separation of Duties

The framework proposed separating the creation, approval, implementation, and auditing of security controls.

The original workflow divided responsibilities among the CISO, security representative, IT management, and executive leadership. When complete separation was not technically possible, compensating controls such as audit trails, activity monitoring, management supervision, and independent approval were proposed.

## Information Risk Management

The project identified risks involving:

- Unauthorized access to student and transportation information
- External attackers attempting to obtain sensitive records
- Users unintentionally disclosing protected information
- Weak passwords and compromised accounts
- Excessive access by employees or partners
- Outdated software and hardware
- Service interruptions and data loss
- Third-party and connected-system weaknesses

The framework proposed limiting access to people directly involved in the service and requiring verification before additional individuals received access.

## Information Classification and Handling

The original project proposed the following classification levels:

1. **Sensitive** — Internal information not intended for public access
2. **Personal Private** — Student, parent, and employee information
3. **Department Private** — Department-specific budgets, routes, reports, schedules, or communications
4. **Organizational Private** — Information limited to executives and other authorized personnel
5. **Confidential** — Highly protected information available only to specific groups
6. **Restricted** — The highest classification level with tightly limited access
7. **Undetermined** — Information temporarily treated at the highest level until properly classified

The project also proposed approval requirements for changing classifications and defaulting uncertain information to a restrictive level.

## Personnel Security

Personnel-security controls included:

- Access based on job role and information classification
- Multifactor authentication for access and changes
- Encryption of employee information
- Secure channels for transmitting sensitive data
- Security-awareness training
- Reporting requirements for suspected incidents

## Cyber Incident Management

The framework proposed continuous monitoring through network-traffic analysis, logs, audit records, user-activity monitoring, and automated alerts.

The documented response process was:

1. Identify the incident
2. Isolate affected systems or shut them down when necessary
3. Use backup systems to maintain availability when possible
4. Remove the threat
5. Restore the affected systems
6. Review the incident
7. Update training, procedures, and controls

Partners such as schools and transportation providers were expected to report incidents that could affect the organization. The original project proposed reporting discovered incidents within 24 hours.

## Account Management and Access Control

The proposed account and access controls included:

- Role-based access
- Least privilege
- Segmentation of users, applications, networks, and data
- Multifactor authentication
- Identity verification
- Session timeouts
- Access-request and approval processes
- Recurring reviews of user privileges
- Additional monitoring for privileged users
- Logging of access to sensitive data
- Password managers for employees
- Progressive account lockouts following repeated failed login attempts

The project proposed restricting each user to the information needed for their role. For example, parents would only be able to view information associated with their own children.

## System Security

The framework applied security throughout a conceptual system lifecycle:

- Design
- Development and testing
- Production and distribution
- Acquisition and deployment
- Maintenance
- Disposal

Security activities included access-control planning, vulnerability testing, third-party review, monitoring, patching, and secure disposal of information that was no longer required.

## Local-System Security

Proposed local-system controls included:

- Regular updates and security patches
- Restricted access to servers and databases
- Approval for third-party systems
- Vulnerability checks for software applications
- Antivirus protection
- Group-based access controls

## Network Security

Proposed network controls included:

- Authorization before connecting new systems
- Firewalls
- Access controls
- Encryption for transmitted information
- Monitoring and alerts
- Security reviews
- Segmented network zones
- Endpoint protection for connected devices

## Vulnerability Management and Operations Security

The original framework proposed:

- Automated and manual vulnerability assessments
- Frequent security updates
- Reviews of policies and procedures
- Logging of access, configuration changes, and security events
- Review of collected logs
- Daily backups
- Separate and secure backup storage
- Immediate action for major threats or vulnerabilities

## Compliance Considerations

The original project discussed:

- FERPA for educational records
- Accessibility considerations associated with the ADA
- Health-information privacy considerations associated with HIPAA

These were academic compliance considerations rather than a legal determination. Actual applicability would depend on the organization, the information it processes, its relationships with other entities, and applicable legal requirements.

## Project Limitations

- The organization and platform were fictional
- Controls were proposed rather than technically implemented
- No production risk assessment was performed
- No legal or regulatory applicability review was completed
- Control effectiveness was not tested
- Some original requirements would need revision before use in a real organization

## Skills Demonstrated

- Information security policy development
- Security governance
- Risk identification
- Data classification
- Access-control planning
- Incident-response planning
- Vulnerability-management planning
- Separation of duties
- Security documentation
- Compliance awareness

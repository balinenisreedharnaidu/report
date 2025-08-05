# Automation of DevOps Processes - Project Report

This repository contains the academic project report documenting the development of a comprehensive DevOps automation framework. The project was completed as part of a long-term internship at SaYukth Technologies Pvt Ltd, Hyderabad.

## Project Overview

**Title:** Automation of DevOps Processes  
**Author:** Balineni Sreedhar Naidu (N180058)  
**Institution:** Rajiv Gandhi University of Knowledge Technologies (RGUKT), Nuzvid  
**Duration:** August 1, 2023 to March 15, 2024  
**Supervisor:** Mr. Venkata Narasimha Kowru (SaYukth Technologies)  
**Academic Guide:** Mr. Kalapala Sravan Kumar  

## Abstract

This project focuses on developing a comprehensive suite of automation scripts tailored for DevOps activities. The scripts are designed to streamline various facets of DevOps operations, including:

- Installation of servers and technology stacks
- Code deployment via CI/CD pipelines
- Server monitoring and logging
- Automated security assessments
- Data backup and health checking
- Linux system hardening

## Technical Architecture

### DevOps Application Stack
- **Git** - Version control system
- **Maven** - Build automation for Java projects
- **TestNG** - Testing framework
- **SonarQube** - Static code analysis
- **PostgreSQL** - Database for SonarQube
- **Snyk** - Security vulnerability scanning

### Deployment Stack
- **HAProxy** - Load balancer
- **Apache Tomcat** - Web application server
- **Percona XtraDB Cluster** - MySQL high-availability clustering
- **ScyllaDB Cluster** - High-performance NoSQL database
- **Redpanda Cluster** - Distributed streaming platform

### Monitoring Stack
- **Prometheus** - Metrics collection and alerting
- **Grafana** - Data visualization and dashboards
- **Various Exporters** - MySQL, Node, HAProxy, Jenkins exporters
- **Alertmanager** - Alert routing and management

## Key Features

### 1. Infrastructure Automation
- Automated installation and configuration of complete technology stacks
- One-click deployment through Jenkins pipelines
- Separation of configuration variables for easy upgrades
- Support for cluster configurations without manual intervention

### 2. Security Implementation
- Linux hardening automation with Lynis security scoring
- Requirement of 85%+ security score before stack deployment
- Integration of security metrics with monitoring stack
- Automated firewall and compliance configurations

### 3. Monitoring and Alerting
- Pre-configured dashboards and alert rules
- Email notifications for system anomalies
- Custom exporters for backup health monitoring
- 365-day data retention for historical analysis

### 4. Data Management
- Automated daily database backups (MySQL and ScyllaDB)
- Verification of backup integrity through row/column count checks
- Automated restoration testing on separate servers
- Alert mechanisms for backup failures

## Repository Structure

```
├── ProjectReport.tex          # Main LaTeX source document
├── ProjectReport.pdf          # Compiled PDF report
├── ProjectReport.aux          # LaTeX auxiliary files
├── ProjectReport.log          # LaTeX compilation log
├── ProjectReport.toc          # Table of contents
├── ProjectReport.lof          # List of figures
├── ProjectReport.synctex.gz   # SyncTeX file for editor integration
├── references.bib            # Bibliography file
├── images/                   # Directory containing all figures and diagrams
│   ├── rgukt.png            # University logo
│   ├── flowchart.png        # Process flowchart
│   ├── devops stack.png     # DevOps pipeline diagram
│   ├── deploy.drawio.png    # Server architecture diagram
│   ├── monstack.png         # Monitoring stack architecture
│   ├── jenkins-full.png     # Jenkins automation architecture
│   ├── backup.png           # Database backup architecture
│   └── [various screenshots and diagrams]
├── Dhoni.png                # Additional image
└── db1.png                  # Database diagram
```

## How to Build/View the Report

### Prerequisites
- LaTeX distribution (e.g., TeX Live, MiKTeX)
- Required LaTeX packages (listed in the document preamble)

### Building from Source
```bash
# Compile the LaTeX document
pdflatex ProjectReport.tex
bibtex ProjectReport
pdflatex ProjectReport.tex
pdflatex ProjectReport.tex
```

### Viewing
The pre-compiled PDF is available as `ProjectReport.pdf` and can be viewed with any PDF reader.

## Key Achievements

1. **Reduced Setup Time**: Server installation and configuration reduced to minutes
2. **Automated Security**: Continuous security monitoring with automated hardening
3. **Comprehensive Monitoring**: 365-day data retention with custom dashboards
4. **Data Integrity**: Automated backup verification and health checking
5. **Scalability**: Easy cluster configuration and technology stack upgrades

## Future Scope

- Enhanced scalability and efficiency improvements
- Advanced security measures and continuous auditing
- Continuous improvement in CI/CD workflows
- Advanced disaster recovery strategies
- Cloud-based backup integration

## Academic Context

This report was submitted in partial fulfillment of the requirements for the Bachelor of Technology degree in Computer Science Engineering at RGUKT Nuzvid. The project demonstrates practical application of DevOps principles in enterprise environments and showcases automation solutions for complex infrastructure management.

## License

This academic work is submitted for educational purposes and degree requirements at RGUKT Nuzvid.
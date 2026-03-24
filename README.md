# IBM TechXchange 2026 - Bob Labs
## March 26, 2026

![IBM Bob](media/bob-hero.svg)

Welcome to the IBM TechXchange 2026 Bob Labs! This hands-on event features three interactive labs designed to showcase the power of **IBM Bob**, your AI-powered development partner.

---

## About IBM Bob

**IBM Bob** is an AI-powered development environment that transforms how developers work. Bob acts as your intelligent coding partner, helping you navigate complex projects, manage your codebase, and build quality software faster.

### What Makes Bob Special?

Bob is built on agentic AI principles, offering multiple specialized modes to assist you throughout the development lifecycle:

- **🤔 Ask Mode**: Get answers to questions, understand code, and explore documentation
- **📝 Plan Mode**: Break down complex tasks, create project roadmaps, and strategize solutions
- **💻 Code Mode**: Write, refactor, and debug code with AI assistance
- **🚀 Advanced Mode**: Access Model Context Protocol (MCP) for extended capabilities
- **🎭 Orchestrator Mode**: Coordinate multiple AI agents for complex workflows

### Key Capabilities

- **Natural Language Interaction**: Communicate with Bob using plain English - no complex commands needed
- **Context-Aware Assistance**: Bob understands your entire project context, not just individual files
- **Multi-Language Support**: Works with Python, Java, JavaScript, TypeScript, and many more languages
- **Integrated Tools**: Seamlessly execute commands, manage files, and interact with your development environment
- **Security-First**: Built-in security scanning and best practices recommendations

---

## Lab Overview

This repository contains three comprehensive labs that demonstrate Bob's capabilities across different development scenarios. Each lab is self-contained and can be completed independently.

### 🔬 Lab 1: Data Science Lab

**Duration**: ~45 minutes
**Difficulty**: Beginner to Intermediate

#### What You'll Learn

Discover how to use Bob for data analysis and visualization tasks:
- Perform automated data exploration and analysis
- Create interactive dashboards using Jupyter notebooks
- Build web applications with Streamlit
- Connect dashboards to PostgreSQL databases

#### The Challenge

You'll work with a comprehensive dataset containing 30 years of global employment, unemployment, and GDP trends from 1991 to 2022, covering approximately 183 countries. Your mission is to analyze this data and create meaningful interactive dashboards for executives.

#### Technologies Used

- Python (pandas, numpy, scikit-learn)
- Jupyter Notebooks
- Streamlit
- Plotly for interactive visualizations
- PostgreSQL (optional)

#### Key Features

- **Data Discovery**: Let Bob automatically explore and describe your dataset
- **Statistical Analysis**: Create distribution charts, correlation matrices, and trend analyses
- **Geographical Visualization**: Display data on interactive world maps
- **Country Comparison**: Compare metrics across different countries
- **Database Integration**: Connect to PostgreSQL for production-ready deployments

**📂 [Go to Lab](./datascience-lab/)**

---

### 🔒 Lab 2: IT Automation Lab

**Duration**: ~60 minutes
**Difficulty**: Intermediate

This lab contains two sub-labs focused on IT automation and security:

#### 2A: DevSecOps Lab (~30 minutes)

**What You'll Learn:**
- Identify common security vulnerabilities in web applications
- Use Bob IDE to detect and fix security issues
- Apply security best practices throughout the development lifecycle
- Implement secure deployment practices
- Set up monitoring for ongoing security assurance

**The Challenge:**
You've been given a deliberately vulnerable web application - a simple message board that allows users to log in and post messages. Your challenge is to identify the security vulnerabilities, fix them using best practices, deploy the application securely, and set up monitoring.

**Technologies & Tools Used:**
- Node.js web application
- **ESLint with security plugins** - Static code analysis
- **OWASP ZAP** - Web application security scanner
- **OWASP Dependency-Check** - Identifies vulnerable dependencies
- **Trivy** - Container vulnerability scanner
- **npm audit** - Built-in Node.js dependency security checker

**📂 [Go to Lab](./IT-automation-lab/DevSecOps-lab/)**

#### 2B: Docker Container Management Lab (~30 minutes)

**What You'll Learn:**
- Deploy and manage Docker containers in a consistent, repeatable way
- Use Terraform to provision Docker infrastructure
- Use Ansible to configure containers
- Implement health checks and resource limits
- Understand container networking and port mapping

**The Challenge:**
Create an Infrastructure as Code solution that provisions and configures a multi-container Docker environment. You'll deploy an Nginx web server and Redis database with proper networking, health checks, and resource management.

**Technologies Used:**
- **Docker** - Container runtime
- **Terraform** - Infrastructure provisioning
- **Ansible** - Configuration management
- **Nginx** - Web server (stable image)
- **Redis** - In-memory database (version 7)

**Architecture:**
The lab creates a Docker network (`tx-net`), an Nginx container (`tx-web`) exposed on port 8080, a Redis container (`tx-redis`) exposed on port 6379, with health checks and resource constraints.

**📂 [Go to Lab](./IT-automation-lab/Docker-container-management-lab/)**

---

### ☕ Lab 3: Java Upgrade Lab

**Duration**: ~45 minutes
**Difficulty**: Intermediate to Advanced

#### What You'll Learn

Master Java modernization with Bob as your upgrade assistant:
- Upgrade legacy Java applications to modern versions
- Identify and resolve compatibility issues
- Update dependencies and libraries
- Modernize code patterns and best practices
- Ensure tests pass after upgrades

#### The Challenge

You'll work with the Tinify API client for Java - a real-world library that compresses images intelligently. The project currently uses Java 1.8 and needs to be upgraded to a modern Java version. Your mission is to modernize the codebase while maintaining backward compatibility and ensuring all tests pass.

#### Technologies Used

- **Java** (upgrading from 1.8 to modern versions)
- **Maven** - Build and dependency management
- **JUnit** - Testing framework
- **OkHttp** - HTTP client library
- **Gson** - JSON processing

#### Key Features

- **Dependency Analysis**: Identify outdated dependencies and compatibility issues
- **Code Modernization**: Update code to use modern Java features
- **Testing**: Ensure all unit and integration tests pass
- **Build Configuration**: Update Maven POM files and build settings
- **Compatibility**: Maintain API compatibility for existing users

#### What You'll Upgrade

- Java version from 1.8 to a modern LTS version
- Dependencies (OkHttp, Gson, test frameworks)
- Build plugins and configurations
- Code patterns to leverage modern Java features

**📂 [Go to Lab](./java-upgrade/)**

---

## Getting Started

### Prerequisites

- **Bob IDE** installed on your laptop ([Download here](https://www.ibm.com/products/bob))
- Basic familiarity with your operating system's terminal/command line
- Git installed for cloning the repository

### Setup Instructions

1. **Clone or Download this repository** onto your laptop:
   ```bash
   git clone <repository-url>
   ```

2. **Rename the directory** to `txc-lab`:
   ```bash
   mv Agentic-TecExchange-mars-26 txc-lab
   ```
   *Note: This is temporary - the walkthroughs are activated when the directory name is 'txc-lab'. We are working to resolve this requirement.*

3. **Open the folder in Bob IDE**:
   - Launch Bob IDE
   - Select "Open Folder"
   - Navigate to and select the `txc-lab` directory

4. **Access the Labs**:
   - You should see a set of labs appear in Bob IDE's walkthrough panel
   - Each lab includes step-by-step instructions
   - Follow the directions in each walkthrough to complete the demo scenarios

### Lab-Specific Setup

Each lab may have additional prerequisites. Please refer to the README or walkthrough instructions within each lab directory for specific setup requirements.

---

## Additional Resources

### Video Demonstrations

We have uploaded video recordings of some of these scenarios on Bob's YouTube channel:
- [Bob YouTube Playlist](https://www.youtube.com/@ibm-bob/playlists)

### Documentation

- [IBM Bob Official Documentation](https://www.ibm.com/products/bob)
- [Bob Developer Resources](https://www.ibm.com/products/bob/developers)

---

## Contact & Support

For questions, feedback, or assistance with the labs, please reach out to our event organizers:

### Primary Contacts

**Mehdi Boulaymen**  
📧 Email: [mehdi.boulaymen@ibm.com](mailto:mehdi.boulaymen@ibm.com)

**François Estepa**  
📧 Email: [Francois.Estepa1@ibm.com](mailto:Francois.Estepa1@ibm.com)

---

## Tips for Success

1. **Take Your Time**: Each lab is designed to be self-paced. Don't rush through the exercises.

2. **Experiment**: Feel free to ask Bob additional questions or try variations of the exercises.

3. **Use Bob's Modes**: Switch between Ask, Plan, and Code modes to get the most out of Bob's capabilities.

4. **Ask for Help**: If you encounter errors, simply copy and paste them to Bob for assistance.

5. **Share Your Experience**: We'd love to hear your feedback about the labs and Bob!

---

## License & Attribution

This repository contains materials prepared for IBM TechXchange 2026. The labs use various open-source tools and datasets:

- Data Science Lab dataset: [Kaggle - Global Jobs, GDP and Unemployment Data](https://www.kaggle.com/datasets/akshatsharma2/global-jobs-gdp-and-unemployment-data-19912022/)
- Security tools: OWASP ZAP, Trivy, ESLint, and others (see individual lab READMEs)

---

**Happy Learning! 🚀**

*Experience the future of AI-powered development with IBM Bob at TechXchange 2026.*
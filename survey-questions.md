# Survey Questions
Below were the **close-to-final** list of questions asked respondents. The final questions are in the **results**.

## Cloud Posture

### How would you describe your organization’s maturity using serverless?
- High: We're all in on serverless
- Medium: We're transitioning to serverless
- Low: We're at the early stages experimenting with serverless or don’t know

### Which public cloud providers do you use?
- Amazon Web Services
- Alibaba
- Cloudflare
- Google Cloud Platform
- IBM Cloud
- Microsoft Azure
- Oracle Cloud
- Rackspace
- Tencent
- Other (please specify): ______________
- None/On-Prem

### How long has your organization been running production applications in the cloud?
- Less than 6 months
- 6 months to a year
- 1 to 2 years
- 3 or more years
- We do not run production application in the cloud

### What percentage of your production workloads utilize serverless (FaaS or Managed Services) in a public cloud environment?
- 0%
- 1-5%
- 6-10%
- 11-20%
- 21-30%
- 31-40%
- 41-50%
- Greater than 50%
- Don’t know
 
### What percentage of your production workloads utilize serverless (FaaS or Managed Services) in an on-premises environment?
- 0%
- 1-5%
- 6-10%
- 11-20%
- 21-30%
- 31-40%
- 41-50%
- Greater than 50%
- Don’t know

### How many serverless functions (FaaS) are you currently running in production?
- 0
- 1-10
- 11-50
- 51-100
- 101-250
- 251-500
- Greater than 500

### How many distinct managed services (e.g. AWS SQS, Google Cloud Firestore, Event Hubs) are you currently using in production environments?
- 0
- 1-5
- 6-10
- 11-15
- 16-20
- 21-25
- More than 25

### Before using serverless, what was your organization’s level of experience with the public cloud?
- I had used multiple public clouds to run production workloads
- I had used a single public cloud provider to run a production workload
- I had used the public cloud in a limited capacity
- I had never used the public cloud before

### How would you define your “multi-cloud” strategy?
- Agnostic Portability
- Full Parity
- Platform Diversity
- Availability of Differentiated Services
- Other (please specify): __________
- None / Not Applicable

## Application Characteristics

### Which FaaS (Functions as a Service) products do you use?
*Use scale: Using, Planning to use in the next 12 months, Not Using/Not Planning to Use, Don’t Know*
- Adobe I/O
- Alibaba Cloud Function
- Apache OpenWhisk
- AWS Lambda
- Azure Functions
- Binaris
- Clay
- CloudBoost
- CloudFlare Workers
- FN Project
- Google Cloud Functions
- Huawei Functions
- Hyper Func
- IBM Cloud Functions
- Knative
- Kubeless
- Nano Lambda
- Netlify
- Nuweba
- OpenFaas
- Oracle Functions
- PubNub Functions
- Spotinst Functions
- Other (please specify): ____________

### Which container-based products do you use?
*Use scale: Using, Planning to use in the next 12 months, Not Using/Not Planning to Use, Don’t Know*
- Alibaba Container Service for Kubernetes
- AWS Fargate
- AWS ECS
- AWS EKS
- Google Cloud Run
- Google Kubernetes Engine
- IBM Cloud Kubernetes Service
- Azure Kubernetes Service
- Red Hat OpenShift Container Platform
- Oracle Cloud Infrastructure Container Engine for Kubernetes
- Kubernetes
- Other (please specify): ____________

### Which categories of managed services are you currently using in production? (Check all that apply)
- Analytics
- API Routing/GraphQL
- Cost Management
- Customer Engagement
- Database
- Event Bus/Messaging
- Internet of Things
- Machine Learning
- Management & Governance
- Media Services
- Mobile
- Networking & Content Delivery
- Orchestration
- Security, Identity, & Compliance
- Storage
- Other (please specify): ____________
- None

### Which framework(s)/services do you currently use with serverless? (Check all that apply)
- Apex Framework
- Architect
- AWS Amplify
- AWS CDK
- AWS Serverless Application Model (SAM)
- Chalice
- ClaudiaJS
- Gordon
- Kappa
- Pulumi
- Serverless Framework
- Serverless Framework Pro
- Sparta
- Stackery
- Terraform
- Zappa
- A custom framework
- None
- Other (please specify): ___________

### Which datastores do you integrate with your serverless applications?
- DynamoDB
- Cosmo DB
- Cassandra
- Google Cloud SQL
- BigTable
- Firestore
- FaunaDB
- Aurora Serverless
- Open-Source RDBMS (MySQL, PostgreSQL, etc.)
- CouchBase
- MongoDB
- Oracle
- Microsoft SQL Server
- Other (please specify): ____________

### Which of the following use cases do you use serverless for?
- REST APIs
- GraphQL
- ETL/Data/Batch Processing Tasks
- DevOps/Operational tasks
- Internet of Things (IoT)
- Business Logic
- Continuous Integration (CI)
- Mobile Backends
- Multimedia Processing
- 3rd-party Service Integration
- Security Automation
- Single Page Applications (SPAs)
- Chatbots
- Edge computing
- Stream Processing
- Change Data Capture (CDC)
- Other (please specify): ___________

### How many serverless “applications” are you running in production? Applications should be defined as a collection of functions and services that form separately managed processes.
[enter number]

### What programming languages does your organization use to develop software?
*Use scale: Currently using, Planning to Use in the next 12 months, Not Planning to Use*
- .NET
- C#
- C++
- F#
- Golang
- Java
- JavaScript
- Node.js
- Perl
- PHP
- Python
- Ruby
- Rust
- Swift
- Other (please specify): _____________
- Other (please specify): _____________

### What programming languages does your organization use to develop serverless functions (FaaS)?
*Use scale: Currently using, Planning to Use in the next 12 months, Not Planning to Use*
- .NET
- C#
- C++
- F#
- Golang
- Java
- JavaScript/Node.js
- Perl
- PHP
- Python
- Ruby
- Rust
- Swift
- Other (please specify): _____________
- Other (please specify): _____________

### How do you structure your serverless applications?
- Mono-repo (i.e. one repository with multiple services/applications, deployed separately)
- Nested stacks (i.e. multiple services/applications that have independent repos but are deployed together)
- Each service is its own repo and stack and is deployed independently
- Each service is its own repo and stack but has shared dependencies that are deployed together
- Other - please explain: ______________
 
### What percentage of your serverless functions are “single-purpose” that perform a small piece of discrete business logic?
- 0%
- 1-25%
- 26-50%
- 51-75%
- 76-99%
- 100%
- Not Sure

## Operations

### Which services and/or tools do you use to monitor your serverless applications?
- Epsagon
- Dashbird
- AWS CloudWatch ServiceLens
- Loggly
- CloudZero
- Sumo Logic
- Thundra
- AWS X-Ray
- AppDynamics
- Serverless Framework Pro
- Datadog
- New Relic
- Lumigo
- Splunk
- Other (please specify): ____________
- None/Only using cloud provider’s default

### Which role in your organization generally decides on adopting new technologies such as serverless?
- Developer / Software Engineer
- Operations / DevOps 
- Product / Team Lead
- Architect
- VP of Engineering
- IT Management CTO / CIO / CISO
- C-level (non-technical) 
- Other (please specify): ____________

## Security

### How would you describe your serverless security posture?
- We rely on the standard security features of our provider
- We are utilizing additional security services available through our provider
- We are utilizing third-party tools and/or services to enhance our security posture
- Not sure

### Do you believe your organization’s security posture has been improved by serverless?
- Yes
- No
- Don’t know

### What security solutions do you use for your serverless applications?
- Aqua Security
- Intrinsic
- Palo Alto Networks (PureSec)
- Check Point (Protego)
- Serverless Framework Pro
- Snyk
- Terraform Enterprise
- Thundra
- Twistlock
- Other (please specify): ______________
- None

### Does your organization create separately scoped roles for each serverless function?
- Yes
- No
- Not Sure

## General Serverless Experience

### What are the top two pain points when using serverless? (Select two)
- Latency (Cold Starts)
- Security
- Debugging
- Monitoring
- Vendor Lock-in
- Deployments
- Cost
- Platform Limitations (tmp folder size, duration, etc.)
- GPU Support
- Other (please specify): _____________

### What are the _top three_ areas in which serverless architecture has had a POSITIVE impact on your software development life cycle?
- Application performance
- Control	
- Cost of labor
- Cost of resources
- DevOps culture
- Event-driven architectures
- Flexibility of architecture
- Flexibility of scaling
- Flexibility of team responsibilities
- Risk reduction
- Portability
- Security – runtime
- Security – vulnerability management and compliance
- Speed of development
- Speed of deployment
- Time to feature or lead time
- Other (please specify): ___________


### What are the top three areas in which serverless architecture has had a NEGATIVE impact on your software development life cycle?
- Application performance
- Control	
- Cost of labor
- Cost of resources
- DevOps culture
- Event-driven architectures
- Flexibility of architecture
- Flexibility of scaling
- Flexibility of team responsibilities
- Risk reduction
- Portability
- Security – runtime
- Security – vulnerability management and compliance
- Speed of development
- Speed of deployment
- Time to feature or lead time
- Other (please specify): ___________


### Did the recent announcement of AWS Lambda’s Provisioned Concurrency have any effect on your organization’s serverless use cases?
- Yes, it has made new use cases possible for our organization
- Yes, it has improved/enhanced our existing use cases
- No, it has had no effect on existing use cases
- We were unaware of it
- We do not use AWS

### Did the latest improvements to AWS Lambdas in VPCs have any effect on your organization’s serverless use cases?
- Yes, it has made new use cases possible for our organization
- Yes, it has improved/enhanced our existing use cases
- No, it has had no effect on existing use cases
- We were unaware of it
- We do not use AWS

### Has your organization tried serverless architecture and decided that it wasn’t a good fit?
- Yes
- No

### What is your organization’s preferred method of compute for greenfield projects?
- Bare metal
- VM
- Container
- Functions
- Other (please specify): _____________

### What “features” are missing from serverless? (in order of importance)
[Open-ended]

## Serverless Education

### Where do you hear about new updates and technologies related to serverless?
- Blogs
- Cloud Provider websites
- Newsletters
- Podcasts
- Serverless Vendor websites
- Medium
- Reddit
- Forums
- Tech News
- Conferences and Meetups
- Webinars
- Other (please specify): ______________


### Please indicate whether you agree or disagree with the following statements regarding your primary cloud provider's quality and quantity of training materials/documentation?
*Use scale: Agree, Disagree, No Opinion*
- Documentation is complete and up-to-date
- Documentation is well-organized and easy to find what I’m looking for
- Concepts are explained with helpful examples
- Example code is provided for my language of choice
- Training materials (e.g. videos, webinars, etc.) are readily available
- Additional content (e.g. blogs, whitepapers, etc.) are readily available
- Content is available for all levels of experience

### What type of activities best evangelize serverless?
- Serverless-specific Conferences (e.g. ServerlessDays, Serverlessconf, etc.)
- Live Coding/Demonstrations
- Workshops
- Webinars
- Online Courses
- Blogs
- Other (please specify): _____________

### What percentage of your developers have cloud certifications or equivalent training?
- 0%
- 1-5%
- 6-10%
- 11-20%
- 21-30%
- 31-40%
- 41-50%
- Greater than 50%
- Don’t know

## Planning

### How likely is your organization to build a greenfield serverless application in the next 12 months?
- Very likely
- Somewhat likely
- Somewhat unlikely
- Very unlikely

### How likely is your organization to convert an existing (brownfield) application to serverless in the next 12 months?
- Very likely
- Somewhat likely
- Somewhat unlikely
- Very unlikely

## Demographics

### How would you classify your organization?
- Enterprise
- Medium-sized
- Small business
- Funded Startup
- Side project/bootstrapped startup

### How many employees are there in your organization?
- Just me
- 2-10
- 11-50
- 51-100
- 101-500
- 501-1,000
- 1,001-10,000
- More than 10,000
- Don’t know

### Which category most closely defines your job role?
- Developer / software engineer
- Administrator / operations
- Architect
- Community manager / developer advocate
- IT management, including CIO / CISO / CTO
- C-level (non-technology) management
- Marketing / PR
- Other (please specify): ___________

### How long has your company/organization been in business?
- Less than a year
- 1 to 2 years
- 2 to 5 years
- 5 to 10 years
- More than 10 years

### In which industry is your business?
- Software & Internet
- Retail / Consumer Goods
- Media
- Marketing and Advertising
- Food and Beverage
- Transportation
- Insurance
- Automotive
- Telecommunications
- Healthcare or Pharmaceuticals 
- Education
- Real Estate
- Non-Profit
- Government
- Manufacturing or Industrial
- Energy or Utilities
- Financial
- Professional Services
- Infotech: Cloud Native services
- Infotech: On-premises services
- Other (please specify): __________

### What geographic regions is your organization located?
- North America
- South America
- Europe
- Africa or Middle East
- East or Southeast Asia
- South Asia
- Australia, Oceania or Pacific Islands

### How would you describe your organization’s product offerings?
- B2B - Business-to-Business
- B2C - Business-to-Consumer
- C2C - Consumer-to-Consumer
- C2B - Consumer-to-Business
- Other (please specify): ___________

### What is your company name? (not to be shared with results)
[enter text] *(optional)*

### What is your email? (to be entered for drawing)
[enter text] *(optional)*
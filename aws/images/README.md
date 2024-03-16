# Table of Content
```
Chapter 01 - Understanding the Foundations of AWS Architecture
Chapter 02 - The AWS Well-Architected Framework
Chapter 03 - Designing Secure Access to AWS Resources
Chapter 04 - Designing Secure Workloads and Applications
Chapter 05 - Determining Appropriate Data Security Controls
Chapter 06 - Designing Resilient Architecture
Chapter 07 - Designing Highly Available and Fault-Tolerant Architecture
Chapter 08 - High-Performing and Scalable Storage Solutions
Chapter 09 - Designing High-Performing and Elastic Compute Solutions
Chapter 10 - Determining High-Performing Database Solutions
Chapter 11 - High-Performing and Scalable Networking Architecture
Chapter 12 - Designing Cost-Optimized Storage Solutions
Chapter 13 - Designing Cost-Effective Compute Solutions
Chapter 14 - Designing Cost-Effective Database Solutions
Chapter 15 - Designing Cost-Effective Network Architectures
```
# Chapter 01
[Establishing your cloud foundation on AWS](https://docs.aws.amazon.com/whitepapers/latest/establishing-your-cloud-foundation-on-aws/capabilities.html)

![AWS services](/aws/images/cloud-foundations-capabilities-full-list.d858b919fb2c4dcb3b27628ba91a1896b1b3e020.png)

```
There are six categories to help you establish a cloud foundation.
- Governance, Risk Management, and Compliance
- Operation
- Security
- Infrastructure
- Business Continuity
- Finance
```

## Governance, Risk Management, and Compliance
> Governance, Risk Management, and Compliance (GRC) helps organizations set the foundation for meeting security and compliance requirements and define the overall policies your cloud environment should adhere to. The capabilities within this area help you define what needs to happen, defines your risk appetite, and informs alignment of internal policies.

### Tagging
> ***Tagging*** enables you to **group sets of resources** by **assigning metadata** to cloud resources for a variety of purposes. These purposes include access control (such as ABAC), cost reporting :money_with_wings:, and automation :oncoming_automobile: (such as patching for select tagged instances). Tagging can also be used to create new resource constructs for visibility or control (such as grouping together resources that make up a microservice, application, or workload). Tagging is fundamental to providing enterprise-level visibility and control. :eyes:

### Log storage
> ***Log*** storage :memo: enables you to collect and store your environment logs centrally and securely. This will enable you to evaluate, monitor, alert, and audit access and actions performed on your cloud resources and objects.

### Forensics
> ***Forensics*** :chart_with_upwards_trend: involves the analysis of log data and evidentially-captured images of potentially compromised resources, to determine whether a compromise occurred (and if so, how). Outcomes of root cause analysis resulting from forensic investigations are typically used to produce and motivate the application of preventative measures.

### Service Onboarding
> ***Service Onboarding*** :ok_hand: provides the ability to review and approve AWS services for use based on consideration of internal, compliance, and regulatory requirements. This capability includes risk assessment, documentation, implementation patterns, and the change communication aspects of service consumption.

### Data De-Identification
> ***Data De-Identification*** :mens: enables you to discover and protect sensitive data as it is stored and processed (for example, national ID numbers, trade data, healthcare information).

### Governance
> ***Governance*** enables you to define and enforce business and regulatory policies :closed_book: for your cloud environment. Policies can include rules for your environment or risk definitions. A portion of your governance policies is embedded in other capabilities across your environment to ensure that you meet your requirements.

### Audit & Assessment
> ***Audit & Assessment*** provides the ability to gather and organize documentary evidence to enable internal or independent assessment of your cloud environment. This capability allows you to validate assertions that all changes were performed in accordance with policy.

### Change Management
> ***Change Management*** enables you to deploy planned alterations to all configurable items that are in an environment within the defined scope, such as production and test. An approved change is an action which alters resource configuration that is implemented with a minimized and accepted risk to existing IT infrastructure.

### Records Management
> ***Records Management*** :department_store: enables you to store, retain, and secure your data according to your internal policies and regulatory requirements. Some examples may include financial records, transactional data, audit logs, business records, and personally identifiable information (PII).

![AWS service](/aws/images/AWS-services.png)

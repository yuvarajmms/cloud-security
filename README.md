# Cloud Security

Cloud security is a broad set of policies, technologies, applications, and controls utilized to protect virtualized IP, data, applications, services, and the associated infrastructure of cloud computing.

Cloud security is a shared responsibility between the cloud provider and the customer. The cloud provider is responsible for the security of the underlying infrastructure, while the customer is responsible for the security of their data and applications.

There are a number of cloud security best practices that organizations can follow to protect their data and applications in the cloud. These include:

Choose a reputable cloud provider. When choosing a cloud provider, it is important to do your research and select a provider that has a strong track record of security.
Implement strong access controls. It is important to implement strong access controls to your cloud resources. This includes using strong passwords, multi-factor authentication, and role-based access control (RBAC).
Encrypt your data. It is important to encrypt your data at rest and in transit. This will help to protect your data from unauthorized access.
Monitor your cloud environment. It is important to monitor your cloud environment for security threats. This includes using cloud security tools to detect and respond to threats.
Stay up-to-date on the latest security threats. It is important to stay up-to-date on the latest security threats. This will help you to protect your cloud environment from emerging threats.

# Contents
    
- [Why Cloud Security](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#why-cloud-security)
- [Identity and access management (IAM)](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#identity-and-access-management-iam)
- [Cloud Infrastructure Protection](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#cloud-infrastructure-protection)
- [Data Protection](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#data-protection)
- [Zero Trust in Cloud Security](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#zero-trust-in-cloud-security)
- [Cloud Security Documentation](https://github.com/yuvarajmms/cloud-security/edit/main/README.md#cloud-security-documentation)


# Why Cloud Security

Cloud security is important because it helps to protect your data and applications from unauthorized access, use, disclosure, disruption, modification, or destruction.

Here are some of the reasons why cloud security is important:

- Data breaches are a real threat. In 2021, there were over 15 billion records exposed in data breaches. This data could include personal information, financial information, and intellectual property.
- Cloud computing is a popular target for hackers. Because cloud computing is so widely used, it is a popular target for hackers. Hackers can target cloud computing environments to steal data, launch denial-of-service attacks, or disrupt services.
- Cloud computing is complex. The complexity of cloud computing makes it difficult to secure. There are many different components to cloud computing environments, and each component has its own security risks.

# Identity and access management (IAM)


Identity and access management (IAM) is a framework of policies and technologies that helps organizations secure their systems and data by controlling who has access to what. IAM encompasses the processes of creating, managing, and retiring user identities, as well as controlling access to resources such as applications, data, and systems.
* <a href="https://aws.amazon.com/iam/?trk=cf28fddb-12ed-4ffd-981b-b89c14793bf1&sc_channel=ps&ef_id=CjwKCAjwkLCkBhA9EiwAka9QRmmsLiEiAmTFxJxIbnGrUhb5jPCKahQTnnXdSa8FJ3VarJNvNSqflxoCf78QAvD_BwE:G:s&s_kwcid=AL!4422!3!652240143562!e!!g!!amazon%20iam!19878797467!148973348604" target="_blank">AWS IAM</a> Securely manage identities and access to AWS services and resources.
 * <a href="https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/ops-guide-iam" target="_blank">Azure IAM</a> Secure access to your resources with Azure identity and access management solutions.
* <a href="https://cloud.google.com/iam" target="_blank">Google Cloud IAM</a> Fine-grained access control and visibility for centrally managing Google cloud resources.

# Detection

Security detection in the cloud refers to the process of identifying and responding to security threats and incidents within a cloud environment. Cloud providers offer various security detection mechanisms and services to help customers protect their data and applications. 
Some common security detection capabilities in the cloud:
1. Intrusion Detection and Prevention Systems (IDS/IPS)
2. Log Management and Analysis
3. Threat Intelligence
4. Security Analytics
5. Vulnerability Scanning
6. Behavioral Analysis
6. File Integrity Monitoring
7. Distributed Denial of Service (DDoS) Protection
8. Endpoint Detection and Response (EDR)
- <a href="https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/detection.html">AWS Detection</a> Security Pillar
- <a href="https://azure.microsoft.com/en-us/products/cognitive-services/anomaly-detector/">Azure Anomaly Detector</a> Anomaly Detection System
- <a href="https://console.cloud.google.com/marketplace/product/cybereason-public/edr">Google Cloud</a> Cybereason Endpoint Detection and Response

# Cloud Infrastructure Protection

Cloud infrastructure protection is the practice of securing cloud-based resources, such as servers, storage, and networks. It is a critical aspect of cloud security and is essential for protecting the confidentiality, integrity, and availability of cloud-based data and applications.

- <a href="https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/infrastructure-protection.html">AWS Infrastructure Protection</a> AWS Holistic guidelines and trainings to help you prevent attacks
- <a href="https://learn.microsoft.com/en-us/azure/security/fundamentals/infrastructure">Azure Infrastructure Security</a> Securing the Azure infrastructure
- <a href="https://cloud.google.com/docs/security/infrastructure/design">Google Infrastructure Security</a> Google Cloud's global technical infrastructure

# Data Protection


Data protection is the process of ensuring that data is secure from unauthorized access, use, disclosure, disruption, modification, or destruction. It is a critical aspect of information security and is essential for protecting the confidentiality, integrity, and availability of data.

- <a href="https://aws.amazon.com/compliance/data-protection/">Data Protection & Privacy at AWS</a> Build with comprehensive data protection in the cloud
- <a href="https://azure.microsoft.com/en-us/explore/trusted-cloud/privacy">Azure Data Privacy in the Trusted Cloud </a> You control your data
- <a href="https://cloud.google.com/security/transparency">Google Cloud Transparency & Data Protection </a> Creating trust through transparency

# Compliance

Cloud compliance refers to adhering to regulatory, industry, and organizational standards when utilizing cloud services. Cloud providers often offer various compliance certifications and frameworks to demonstrate their commitment to security and data privacy. 

- <a href="https://aws.amazon.com/compliance/programs/">AWS Compliance</a>
- <a href="https://learn.microsoft.com/en-us/azure/compliance/">Azure Compliance</a>
- <a href="https://cloud.google.com/security/compliance">Google Cloud Compliance</a>

# Zero Trust in Cloud Security

Zero trust is a security model that assumes that no user or device is inherently trustworthy, even if they are inside the network perimeter. This means that all access to resources, regardless of location, must be authenticated and authorized.

Zero trust is a departure from traditional security models, which rely on perimeter security to protect assets. Perimeter security is based on the idea that the network perimeter is a secure boundary that can be used to keep unauthorized users out. However, this model is no longer effective in today's world, where users and devices can connect to the network from anywhere.

- <a href="https://aws.amazon.com/security/zero-trust/">Zero Trust on AWS</a> Advancing your security model with a Zero Trust approach.
- <a href="https://learn.microsoft.com/en-us/azure/security/fundamentals/zero-trust">Azure Zero Trust security</a> Guiding principles of Zero Trust.
- <a href="https://cloud.google.com/learn/what-is-zero-trust">Google Cloud Zero Trust</a> Zero trust defined.
  
# Cloud Security Documentation

- <a href="https://aws.amazon.com/security/">AWS Cloud Security</a> Infrastructure and services to elevate your security in the cloud.
- <a href="https://azure.microsoft.com/en-us/explore/security">Azure Cloud Security</a> Strengthen your security posture with Azure.
 - <a href="https://cloud.google.com/security">Google Cloud Security</a> Your security transformation: safer with Google technology and expertise.

# Note

Please note that the information provided is a general overview and may not capture every detail or feature of each cloud. It's important to refer to the official documentation and websites of each cloud provider for the most up-to-date and comprehensive information regarding their Security offerings.

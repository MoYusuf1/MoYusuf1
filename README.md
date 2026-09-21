<h2 align="center">Mohamed Yusuf</h2>
<p align="center"><b>Cloud Engineer</b> · Minneapolis, MN<br/>I design AWS infrastructure, build it as code, and break it on purpose to prove it holds.</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Solutions Architect Associate"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

### What I work on

Software Engineer at World Racing Group, where I work with AWS (S3, IAM, Lightsail, CloudFormation) and GitHub Actions CI/CD. Outside of work I build production-style AWS architectures, write up every design decision, and document what broke along the way.

### Featured project

**[aws-privatelink-multi-vpc-terraform](https://github.com/MoYusuf1/aws-privatelink-multi-vpc-terraform)**
Three isolated VPCs share one internal service over PrivateLink, with no peering and no public IPs. Access approvals live in code, the service identifies which team is calling, and every change runs through mocked tests, tflint, and Checkov in CI.

```mermaid
flowchart LR
  P[Payments VPC] -->|PrivateLink| S[Shared Services]
  A[Analytics VPC] -->|PrivateLink| S
  P x--x|no route| A
```

### Architecture write-ups

| Project | What it proves |
|---|---|
| [Private multi-VPC with PrivateLink](https://www.linkedin.com/pulse/how-i-built-private-multi-vpc-architecture-aws-mohamed-yusuf-xjnoc/) | Sharing one service between teams without connecting their networks |
| [Rebuilt in Terraform](https://www.linkedin.com/pulse/how-i-rebuilt-private-multi-vpc-architecture-so-team-could-yusuf-c21mf/) | Access decisions reviewed in code, tested before they reach AWS |
| [Multi-region with Global Accelerator](https://www.linkedin.com/in/mohamed-yusuf1/recent-activity/articles/) | Surviving a regional outage, verified by taking the primary down |
| [Event-driven order processing](https://www.linkedin.com/in/mohamed-yusuf1/recent-activity/articles/) | Retries, dead-letter queues, and no lost orders when a worker fails |
| [Zero-downtime deployments](https://www.linkedin.com/in/mohamed-yusuf1/recent-activity/articles/) | Blue-green cutover and one-step rollback behind a load balancer |
| [Private S3 and CloudFront hosting](https://www.linkedin.com/in/mohamed-yusuf1/recent-activity/articles/) | Tracing a misleading 403 across CloudFront and S3 |

### Currently

Migrating [LeetGrammar](https://github.com/MoYusuf1/LeetGrammar) from Vercel to AWS with Terraform.

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-yusuf1/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

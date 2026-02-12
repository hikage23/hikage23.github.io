 
layout: default
title: Projects
 

# 🛠 projects@sec-eng:~$

### `> pwd`
/home/numaan/security/projects



### `> ls -la`

```
drwxr-xr-x  secure-cicd-lab/
drwxr-xr-x  api-security-demo/
drwxr-xr-x  ai-vuln-triage/
drwxr-xr-x  cloud-review/
```

 

## 🔐 secure-cicd-lab/

### `> cat README.md`

**Focus:** DevSecOps | Secure SDLC | Pipeline Security

Built a containerized microservice and integrated security controls directly into the CI/CD workflow.

```
Security Controls Implemented:
  - Static code analysis (SAST)
  - Dependency vulnerability scanning (SCA)
  - Container image scanning
  - Build-time security gates
```

```
Operational Outcomes:
  - Vulnerability detection during pull request stage
  - Severity-based triage workflow
  - Documented remediation lifecycle
  - Reduced exposure window before deployment
```

Objective: Shift security left and operationalize automated controls within development pipelines.

 

## 🧪 api-security-demo/

### `> ./run_assessment.sh`

**Focus:** Application Security | OWASP API Top 10

Designed a vulnerable REST API to simulate realistic exploitation paths.

```
Tested Scenarios:
  - Broken object-level authorization (IDOR)
  - JWT validation weaknesses
  - Injection via unsanitized input
  - Rate limiting bypass
```

Includes:
  - Structured threat model
  - Exploitation walkthrough
  - Risk severity classification
  - Remediation strategy documentation

 

## 🤖 ai-vuln-triage/

### `> python triage.py --analyze scan_output.json`

**Focus:** AI-Augmented Security Engineering

Prototype workflow that processes raw scanner output and enhances triage efficiency.

```
Capabilities:
  - Severity normalization
  - Context-aware risk tagging
  - False positive likelihood scoring
  - Remediation guidance generation
```

Objective: Improve signal-to-noise ratio in large-scale vulnerability management programs.

 

## ☁️ cloud-review/

### `> terraform plan --security-review`

**Focus:** Cloud Security | IAM | Infrastructure Risk

Simulated review of cloud-native deployment patterns.

```
Security Analysis:
  - Overly permissive IAM role detection
  - Public exposure surface identification
  - Container registry permission audit
  - Least-privilege enforcement validation
```

 

### `> echo $NEXT`

Planned Modules:
  - Structured SaaS threat modeling case study
  - Secure design review checklist (API-driven systems)
  - CI/CD hardening benchmark report

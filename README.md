# Khaleel Ahmad – Professional CV Repository

A collection of role-specific, ATS-optimized CVs and cover letters for targeted job applications.

---

## 👤 About

This repository contains multiple CV versions tailored for different engineering positions. Each CV emphasizes relevant experience, technical expertise, and certifications for the target role while maintaining a clean, professional structure built on the [Awesome CV](https://github.com/posquit0/Awesome-CV) LaTeX template.

**Quick Profile:**
- **Education:** M.S. Artificial Intelligence (BTU Cottbus-Senftenberg, 2025–Present)
- **Location:** Berlin, Germany
- **Links:** [LinkedIn](https://linkedin.com/in/khaleel-ahmad) | [GitHub](https://github.com/khaleel-git)

---

## 📂 CV Versions

Each role directory contains a complete, optimized CV package:

| Role | Focus | Key Technologies |
|------|-------|------------------|
| **DevOps Engineer** | Cloud infrastructure, automation, CI/CD | AWS, Kubernetes, Terraform, Docker, GitHub Actions |
| **Data Engineer** | ETL pipelines, data processing, analytics | Apache Airflow, Python, PostgreSQL, MongoDB, Power BI |
| **Linux System Admin** | Infrastructure management, security, monitoring | Linux, systemd, firewall, bash scripting, Ansible |

---

## 📁 Repository Structure

```
Portfolio/
├── devops/                          # DevOps Engineer CV package
│   ├── Khaleel_CV.tex              # Full CV (2-3 pages)
│   ├── Khaleel_Resume.tex          # Concise resume (1 page)
│   ├── Khaleel_CoverLetter.tex     # Cover letter template
│   └── awesome-cv.cls              # LaTeX template class
├── data-engineer/                   # Data Engineer CV package
├── linux-sysadmin/                  # Linux SysAdmin CV package
├── examples/                        # Template reference examples
├── .gitignore                       # Version control settings
├── Makefile                         # Build automation
└── README.md                        # This file
```

---

## 🏗️ Building CVs

### Prerequisites
- **TeX Live** (macOS/Linux) or **MiKTeX** (Windows)
- `xelatex` compiler
- GNU `make` (optional but recommended)

### Quick Build

Build a specific role's CV:
```bash
cd devops && make
cd data-engineer && make
cd linux-sysadmin && make
```

Or compile manually:
```bash
cd devops
xelatex Khaleel_CV.tex
```

Output: `Khaleel_CV.pdf` in the respective directory

### Build All Documents

```bash
make
```

---

## ✏️ Customization Guide

### File Structure
Each role directory contains:
- **`Khaleel_CV.tex`** – Full curriculum vitae with complete work history and skills
- **`Khaleel_Resume.tex`** – Single-page resume for quick screening
- **`Khaleel_CoverLetter.tex`** – Customizable cover letter template
- **`awesome-cv.cls`** – LaTeX styling (modify carefully)

### Editing Tips
1. Open `.tex` files in any text editor (VS Code, Sublime Text, etc.)
2. Modify sections:
   - **Job descriptions** – Adjust to match job postings
   - **Skills section** – Emphasize relevant technologies
   - **Experience order** – Lead with most relevant roles
   - **Keywords** – Include industry terminology for ATS systems
3. Rebuild PDF to preview changes

### Common Changes
```latex
% Update contact info
\email{your.email@example.com}
\mobile{+49 123 456 7890}

% Modify job title emphasis
\cventry{Period}{Title}{\textbf{Company}}{Location}{Achievement}

% Add technologies
\cvskill{Python}{NumPy, Pandas, PyTorch, Scikit-learn}
```

---

## 🎯 Role Details

### DevOps Engineer
- **Experience:** Cloud infrastructure, container orchestration, CI/CD pipelines
- **Key Certifications:** CKA (Certified Kubernetes Administrator), LFCS (Linux Foundation)
- **Technologies:** AWS, Kubernetes, Docker, Terraform, GitHub Actions, Prometheus, Grafana
- **Focus:** Automation, scalability, reliability

### Data Engineer
- **Experience:** ETL pipeline design, data warehouse architecture, analytics infrastructure
- **Key Skills:** Python, SQL, data modeling, performance optimization
- **Tools:** Apache Airflow, PostgreSQL, MongoDB, Power BI, PySpark
- **Focus:** Data quality, pipeline optimization, scalability

### Linux System Administrator
- **Experience:** Server administration, system hardening, infrastructure monitoring
- **Key Certifications:** LFCS (Linux Foundation), additional cloud certifications
- **Technologies:** Linux kernel, systemd, bash/Python scripting, Ansible, monitoring tools
- **Focus:** Security, performance tuning, automation

---

## 🔍 ATS Optimization

All CVs are optimized for Applicant Tracking Systems:

✅ **Clean Structure** – Minimal special characters, standard formatting  
✅ **Keywords** – Industry-standard terminology matching job descriptions  
✅ **Metrics** – Quantified achievements and impact (percentages, numbers, scale)  
✅ **Clarity** – Action-oriented language with strong verbs  
✅ **Parseable Layout** – Logical sections, consistent formatting

**Best Practice:** Before submitting, validate with [JobScan](https://www.jobscan.co/) against the target job posting.

---

## 📋 Document Checklist

**Before Applying:**
- [ ] Select the appropriate role-specific CV
- [ ] Verify PDF renders correctly
- [ ] Customize cover letter for the specific company
- [ ] Update keywords to match job posting
- [ ] Check for typos and formatting consistency
- [ ] Test ATS compatibility if required

---

## 🔐 Privacy & Security

Sensitive personal documents (certificates, transcripts, enrollment records) are excluded from this repository and protected via `.gitignore`. If you fork this project, ensure similar security practices for your own credentials.

---

## 📞 Contact & Links

**Email:** khaleel.eu@gmail.com  
**LinkedIn:** [linkedin.com/in/khaleel-ahmad](https://linkedin.com/in/khaleel-ahmad)  
**GitHub:** [github.com/khaleel-git](https://github.com/khaleel-git)

---

## 📜 License

This project uses the [Awesome CV](https://github.com/posquit0/Awesome-CV) template. See the original repository for license details.

---

**Last Updated:** May 2026  
**Format:** LaTeX (xelatex)

Built with [Awesome CV](https://github.com/posquit0/Awesome-CV) template

[**LaTeX**](https://www.latex-project.org) is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

[**FontAwesome6 LaTeX Package**](https://github.com/braniii/fontawesome) is a LaTeX package that provides access to the [Font Awesome 6](https://fontawesome.com/v6/icons) icon set.

[**Roboto**](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.




# Khaleel Ahmad's CV Repository

Professional CV workspace with role-specific versions optimized for different job applications.

## 📋 About

This repository contains tailored CVs for various roles built with the [Awesome CV](https://github.com/posquit0/Awesome-CV) LaTeX template. Each version emphasizes relevant experience, skills, and certifications for the target position.

**Quick Info:**
- 🎓 M.S. Artificial Intelligence (BTU Cottbus-Senftenberg, 2025–Present)
- 🎓 B.S. Computer Science (ITU Pakistan, 2016–2021)
- 📍 Berlin, Germany
- 🔗 [Portfolio](https://khaleel.eu) | [LinkedIn](https://linkedin.com/in/khaleel-ahmad) | [GitHub](https://github.com/khaleel-git)

## 🗂️ Directory Structure

```
├── devops/                    # DevOps Engineer (AWS, Kubernetes, IaC)
├── data-engineer/             # Data Engineer (ETL, Pipelines, Databases)
├── linux-sysadmin/            # Linux System Administrator (LFCS, Infrastructure)
├── examples/                  # Template examples
└── README.md
```

## 🚀 Building Your CV

### Requirements
- TeX Live or MiKTeX installed
- `xelatex` command available

### Build a Specific Role CV

```bash
cd devops && make
# or
cd data-engineer && make
# or
cd linux-sysadmin && make
```

**Or manually:**
```bash
xelatex Khaleel_CV.tex
```

This generates `Khaleel_CV.pdf` in the respective folder.

## 📝 Customizing

Each folder contains:
- `Khaleel_CV.tex` - Full CV (role-tailored)
- `Khaleel_Resume.tex` - One-page resume
- `Khaleel_CoverLetter.tex` - Cover letter template
- `awesome-cv.cls` - LaTeX template

Edit the `.tex` files to customize:
- Job descriptions and bullet points
- Technical skills emphasis
- Experience ordering

## 🎯 Role-Specific Versions

### DevOps Engineer
- Focus: AWS, Kubernetes, CI/CD, Infrastructure as Code
- Certifications: CKA, LFCS
- Key Skills: Terraform, Docker, GitHub Actions, Prometheus/Grafana

### Data Engineer
- Focus: ETL pipelines, data processing, databases
- Key Tools: Airflow, Python, PostgreSQL, MongoDB
- Emphasis: Data quality, optimization, automation

### Linux System Administrator
- Focus: System administration, Linux, security hardening
- Certifications: LFCS (primary), CKA (secondary)
- Key Skills: Linux kernel, systemd, monitoring, firewall configuration

## 📊 ATS Optimization

Each CV is optimized for Applicant Tracking Systems (ATS):
- ✅ Clean LaTeX structure with minimal special characters
- ✅ Industry-standard keywords and terminology
- ✅ Quantified metrics and achievements
- ✅ Action-oriented language

**Recommendation:** Export to PDF and test with [JobScan](https://www.jobscan.co/) before submitting to job portals.

## 📄 Supporting Documents

- `Khaleel_Certificates_References.pdf` - Certifications & references
- `Certificate of Enrolment [PDF].pdf` - University enrollment
- `Transcipt of Records_BTU.pdf` - Academic transcript

## 📧 Contact

- Email: khaleel.eu@gmail.com
- Phone: +49 155 63611714
- Website: https://khaleel.eu

---

Built with [Awesome CV](https://github.com/posquit0/Awesome-CV) template

[**LaTeX**](https://www.latex-project.org) is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

[**FontAwesome6 LaTeX Package**](https://github.com/braniii/fontawesome) is a LaTeX package that provides access to the [Font Awesome 6](https://fontawesome.com/v6/icons) icon set.

[**Roboto**](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.


## Contact

You are free to take my `.tex` file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though!

If you have any questions, feel free to join me at [`#posquit0` on Freenode](irc://irc.freenode.net/posquit0) and ask away. Click [here](https://kiwiirc.com/client/irc.freenode.net/posquit0) to connect.

Good luck!


## Maintainers
- [posquit0](https://github.com/posquit0)
- [OJFord](https://github.com/OJFord)


## See Also

* [Awesome Identity](https://github.com/posquit0/hugo-awesome-identity) - A single-page Hugo theme to introduce yourself.

# CV Repository

Customizable CV and cover letter templates for targeted job applications.

## About

This repo contains CV and cover letter templates built with [Awesome CV](https://github.com/posquit0/Awesome-CV). Each folder represents a specific role version you can customize for your needs.

- **Education:** M.S. Artificial Intelligence (BTU Cottbus-Senftenberg, 2025–Present)
- **Location:** Berlin, Germany

## How to Use

Pick the role folder that matches your target position (e.g., `devops/`, `data-engineer/`, `linux-sysadmin/`). Each contains:
- `Khaleel_CV.tex` – Full CV
- `Khaleel_Resume.tex` – One-page resume
- `Khaleel_CoverLetter.tex` – Cover letter template
- `profile.jpg` – Professional photo (included in some folders)

Edit the `.tex` files with your own information and build to PDF.

## Building Your CV

### Option 1: Online (Recommended)
Use [Overleaf](https://www.overleaf.com/) – upload the `.tex` files and compile directly in the browser. No installation needed.

### Option 2: Local Installation
Install `xelatex` on your system:

**macOS:**
```bash
brew install basictex
```

**Ubuntu/Debian:**
```bash
sudo apt-get install texlive-xetex
```

**Windows:**
Download and install [MiKTeX](https://miktex.org/download)

Then compile:
```bash
xelatex Khaleel_CV.tex
```

This generates `Khaleel_CV.pdf`.

## Customization

Open the `.tex` file in any text editor and modify:
- Contact information
- Work experience and achievements
- Technical skills
- Education details
- Add/remove sections as needed

The `profile.jpg` file is referenced in the CV header for a professional photo. Update the reference or replace the image file.

## Links

- [LinkedIn](https://linkedin.com/in/khaleel-ahmad)
- [GitHub](https://github.com/khaleel-git)

---

Built with [Awesome CV](https://github.com/posquit0/Awesome-CV)

Built with [Awesome CV](https://github.com/posquit0/Awesome-CV) template

[**LaTeX**](https://www.latex-project.org) is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

[**FontAwesome6 LaTeX Package**](https://github.com/braniii/fontawesome) is a LaTeX package that provides access to the [Font Awesome 6](https://fontawesome.com/v6/icons) icon set.

[**Roboto**](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.




# 📚 Bibliometric Analysis Complete Guide
**By Mahbub Hassan**  
*PhD Student, Civil Engineering (Transportation)*  
*Chulalongkorn University, Bangkok, Thailand*

[![GitHub stars](https://img.shields.io/github/stars/mahbubchula/Bibliometric-Analysis-by-Mahbub)](https://github.com/mahbubchula/Bibliometric-Analysis-by-Mahbub/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/mahbubchula/Bibliometric-Analysis-by-Mahbub/graphs/commit-activity)

---

## 🎯 Overview

Welcome to the most comprehensive, beginner-friendly guide to bibliometric analysis! This interactive course takes you from absolute zero to publishing your first bibliometric paper using **R Biblioshiny** and **VOSviewer**.

### 🌟 What Makes This Course Special?

- **Zero to Hero Approach**: Designed for complete beginners
- **Interactive Learning**: Beautiful, modern UI with expandable sections
- **Step-by-Step Guidance**: Every single step explained in detail
- **Practical Examples**: Real datasets and code templates included
- **Publication-Ready**: Learn to write and publish your analysis

---

## 📖 Course Modules

### Module 1: Introduction to Bibliometric Analysis
- Understanding bibliometric analysis fundamentals
- Key terminology and concepts
- Types of bibliometric studies
- Research applications in transportation engineering

### Module 2: Data Collection Strategies
- Web of Science navigation and export
- Scopus search techniques
- Designing effective search queries
- Data quality assurance

### Module 3: R Biblioshiny Analysis
- Installation and setup guide
- Data import and conversion
- Descriptive statistics
- Performance analysis (most cited papers, authors, journals)
- Trend analysis and temporal evolution
- Co-occurrence networks
- Thematic mapping
- Visualization generation

### Module 4: VOSviewer Visualization
- Software installation
- Network construction techniques
- Co-citation analysis
- Bibliographic coupling
- Co-authorship networks
- Keyword co-occurrence
- Customization and export

### Module 5: Writing Your Paper
- Standard paper structure
- Reporting guidelines
- Result interpretation
- Journal selection tips
- Submission process

### Module 6: Resources & Templates
- R code templates
- Sample datasets
- PRISMA diagram templates
- Manuscript templates
- Supplementary materials examples

---

## 🚀 Quick Start

### Option 1: Access Online Course
Simply open `index.html` in your web browser to start the interactive course immediately!

```bash
# Clone the repository
git clone https://github.com/mahbubchula/Bibliometric-Analysis-by-Mahbub.git

# Open the course
cd Bibliometric-Analysis-by-Mahbub
open index.html  # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

### Option 2: GitHub Pages (Coming Soon)
Visit: `https://mahbubchula.github.io/Bibliometric-Analysis-by-Mahbub`

---

## 💻 Prerequisites

### For Biblioshiny Analysis:
- **R** (version 4.0 or higher)
- **RStudio** (recommended but optional)
- **bibliometrix** R package

### For VOSviewer Analysis:
- **Java Runtime Environment** (JRE 8 or higher)
- **VOSviewer** software (free download)

### Data Access:
- Institutional access to **Web of Science** or **Scopus**
- Alternative: Google Scholar (limited functionality)

---

## 📦 Repository Structure

```
Bibliometric-Analysis-by-Mahbub/
├── index.html                 # Main interactive course
├── README.md                  # This file
├── LICENSE                    # MIT License
├── examples/                  # Example datasets and outputs
│   ├── sample_wos_data.txt
│   ├── sample_scopus_data.csv
│   └── example_outputs/
├── templates/                 # Code and document templates
│   ├── biblioshiny_scripts/
│   ├── vosviewer_guides/
│   └── paper_templates/
├── resources/                 # Additional learning materials
│   ├── cheat_sheets/
│   ├── video_tutorials/
│   └── recommended_readings/
└── assets/                    # Images and styling
    ├── css/
    ├── images/
    └── fonts/
```

---

## 🎓 Learning Path

### Beginner (Week 1-2)
1. Complete Module 1: Introduction
2. Learn Module 2: Data Collection
3. Practice with sample datasets

### Intermediate (Week 3-4)
4. Master Module 3: Biblioshiny Analysis
5. Complete Module 4: VOSviewer Visualization
6. Analyze your own dataset

### Advanced (Week 5-6)
7. Study Module 5: Writing Your Paper
8. Draft your manuscript
9. Prepare for journal submission

---

## 🔥 Key Features

### Interactive Learning Experience
- **Expandable Sections**: Click to reveal detailed content
- **Code Examples**: Copy-paste ready code blocks
- **Visual Guides**: Beautiful Chula-themed design
- **Progress Tracking**: Monitor your learning journey

### Comprehensive Coverage
- **150+ Step-by-Step Instructions**
- **50+ Code Examples**
- **30+ Visualization Techniques**
- **20+ Real-world Examples**

### Publication Quality
- **Q1 Journal Standards**
- **Reporting Guidelines Compliant**
- **Reproducible Research Practices**
- **Open Science Principles**

---

## 📊 Example Analyses Included

### Transportation Engineering Examples:
- Electric Vehicle Adoption Research
- Sustainable Mobility Studies
- Smart City Transportation
- Traffic Safety Analysis

### General Examples:
- Machine Learning Applications
- Climate Change Research
- Public Health Studies
- Artificial Intelligence

---

## 🛠️ Installation Guides

### Installing R and Biblioshiny

```r
# Install R from: https://cran.r-project.org/

# Install RStudio from: https://posit.co/download/rstudio-desktop/

# Install bibliometrix package
install.packages("bibliometrix")

# Load library
library(bibliometrix)

# Launch Biblioshiny
biblioshiny()
```

### Installing VOSviewer

```bash
# Download from: https://www.vosviewer.com/download

# Windows: Run installer
# macOS: Extract and run
# Linux: Extract and run (requires Java)
```

---

## 📈 Sample Workflow

### 1. Define Research Question
Example: *"What are the research trends in electric vehicle adoption?"*

### 2. Design Search Query
```
TS=("electric vehicle*" OR "EV" OR "battery electric") 
AND 
TS=("adoption" OR "acceptance" OR "intention")
```

### 3. Collect Data
- Export from Web of Science (Full Record + Cited References)
- Save as .txt files

### 4. Analyze in Biblioshiny
```r
library(bibliometrix)
M <- convert2df("data.txt", dbsource = "wos", format = "plaintext")
results <- biblioAnalysis(M)
plot(results, k=10)
```

### 5. Visualize in VOSviewer
- Import data → Create map → Customize → Export

### 6. Write Your Paper
- Use provided templates
- Follow reporting guidelines
- Include all visualizations

---

## 🤝 Contributing

Contributions are welcome! Whether it's:
- Reporting bugs
- Suggesting new features
- Adding examples
- Improving documentation
- Translating content

Please feel free to open an issue or submit a pull request.

---

## 📧 Contact

**Mahbub Hassan**  
PhD Student in Civil Engineering (Transportation)  
Chulalongkorn University, Bangkok, Thailand

- 📧 Email: 6870376421@student.chula.ac.th
- 📧 IEEE Email: mahbub.hassan@ieee.org
- 💻 GitHub: [@mahbubchula](https://github.com/mahbubchula)
- 🔗 Google Scholar: [Profile](https://scholar.google.com)
- 🔗 ResearchGate: [Profile](https://www.researchgate.net)
- 🔗 ORCID: [Profile](https://orcid.org)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Chulalongkorn University** for institutional support
- **Faculty of Engineering** for providing research facilities
- **R bibliometrix team** for the excellent package
- **VOSviewer developers** for the visualization tool
- **Open Science Community** for sharing knowledge

---

## 📚 Citation

If you use this course in your research or teaching, please cite:

```bibtex
@misc{hassan2025bibliometric,
  author = {Hassan, Mahbub},
  title = {Complete Bibliometric Analysis Guide: From Zero to Published},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/mahbubchula/Bibliometric-Analysis-by-Mahbub}
}
```

---

## 🌟 Star History

If you find this course helpful, please consider giving it a star ⭐️

[![Star History Chart](https://api.star-history.com/svg?repos=mahbubchula/Bibliometric-Analysis-by-Mahbub&type=Date)](https://star-history.com/#mahbubchula/Bibliometric-Analysis-by-Mahbub&Date)

---

## 📈 Repository Stats

![GitHub repo size](https://img.shields.io/github/repo-size/mahbubchula/Bibliometric-Analysis-by-Mahbub)
![GitHub last commit](https://img.shields.io/github/last-commit/mahbubchula/Bibliometric-Analysis-by-Mahbub)
![GitHub issues](https://img.shields.io/github/issues/mahbubchula/Bibliometric-Analysis-by-Mahbub)
![GitHub pull requests](https://img.shields.io/github/issues-pr/mahbubchula/Bibliometric-Analysis-by-Mahbub)

---

## 🔗 Quick Links

- [📖 Start Learning Now](index.html)
- [💡 Example Datasets](examples/)
- [📝 Code Templates](templates/)
- [🎥 Video Tutorials](resources/video_tutorials/)
- [❓ FAQ](resources/faq.md)
- [🐛 Report Issues](https://github.com/mahbubchula/Bibliometric-Analysis-by-Mahbub/issues)

---

<div align="center">

### 🎓 From Chulalongkorn University with 💖

**Happy Learning and Good Luck with Your Research!** 🚀

Made with ❤️ by [Mahbub Hassan](https://github.com/mahbubchula)

</div>

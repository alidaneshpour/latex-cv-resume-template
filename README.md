# Professional LaTeX Resume (CV) Template

A clean, modern, and ATS-friendly LaTeX resume template perfect for academics, researchers, and professionals in technical fields. This template is based on [Jake Gutierrez's](https://github.com/jakegut/resume) work and has been enhanced with additional features and customizations.

## 🌟 Features

- **Clean and Professional Design**: Minimalist layout that focuses on content
- **ATS-Friendly**: Machine-readable format that passes through Applicant Tracking Systems
- **Highly Customizable**: Easy to modify colors, fonts, and sections
- **Academic Focus**: Perfect for researchers, PhD students, and academics
- **Multiple Sections**: Supports education, experience, publications, projects, and more
- **Font Options**: Multiple serif and sans-serif font choices
- **Icon Integration**: FontAwesome icons for contact information and links
- **Responsive Layout**: Optimized for both digital and print formats

## 📋 Template Sections

- **Header**: Name, contact information, and professional links
- **Education**: Academic background with GPA and relevant coursework
- **Research Experience**: Research positions and responsibilities
- **Work Experience**: Professional experience with detailed descriptions
- **Teaching Experience**: Teaching assistant and instructor roles
- **Publications**: Academic publications with proper formatting
- **Projects**: Technical projects with GitHub links
- **Technical Skills**: Programming languages, frameworks, and tools
- **Honors and Awards**: Academic achievements and recognitions

## 🚀 Quick Start

### Prerequisites

You'll need a LaTeX distribution installed on your system:
- **Windows**: [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
- **macOS**: [MacTeX](https://tug.org/mactex/)
- **Linux**: TeX Live (usually available in package managers)
- [**Overleaf**](https://www.overleaf.com): Online option (no installation required, works entirely in the browser)

### Required Packages

The template uses the following LaTeX packages:
latexsym, fullpage, titlesec, marvosym, color, verbatim, enumitem, 
hyperref, fancyhdr, babel, tabularx, fontawesome5, multicol, ragged2e

### Installation and Usage

1. **Clone the repository**:
   git clone https://github.com/yourusername/latex-resume-template.git
   cd latex-resume-template

2. **Edit the main.tex file**:
   - Replace the personal information in the header section
   - Update each section with your own information
   - Customize colors and fonts as needed

3. **Compile the document**:
   pdflatex main.tex
   Or use your preferred LaTeX editor (TeXstudio, Overleaf, VS Code with LaTeX Workshop)

## 🎨 Customization Options

### Font Options

Uncomment one of the following in the preamble to change fonts:

**Sans-serif options**:
\usepackage[sfdefault]{FiraSans}
\usepackage[sfdefault]{roboto}
\usepackage[sfdefault]{noto-sans}
\usepackage[default]{sourcesanspro}

**Serif options**:
\usepackage{CormorantGaramond}
\usepackage{charter}

### Color Customization

The template uses a simple color scheme. You can modify the title rule color:
[\color{black}\titlerule \vspace{-5pt}]

### Section Customization

Add new sections by following this pattern:
\section{New Section}
\resumeSubHeadingListStart
  \resumeSubheading
    {Position/Title}{Date}
    {Organization}{Location}
    \resumeItemListStart
      \resumeItem{Description}{Additional Info}
    \resumeItemListEnd
\resumeSubHeadingListEnd

## 📁 File Structure

├── main.tex              # Main resume file
├── README.md             # This file
├── resume.pdf            # Compiled PDF (generated)
└── fonts/                # Custom fonts (optional)

## 💡 Tips for Best Results

1. **Keep it concise**: Aim for 1-2 pages maximum
2. **Use action verbs**: Start bullet points with strong action verbs
3. **Quantify achievements**: Include numbers and metrics where possible
4. **Proofread carefully**: Check for typos and formatting consistency
5. **Test ATS compatibility**: Use simple formatting and avoid complex tables
6. **Update regularly**: Keep your resume current with recent achievements

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs or issues
- Suggest new features or improvements
- Submit pull requests
- Share your customizations

### How to Contribute

1. Fork the repository
2. Create a feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

[- Original template by [Jake Gutierrez](https://github.com/jakegut/resume)
- [Based on [sb2nov's resume template](https://github.com/sb2nov/resume)
- FontAwesome for icons
- LaTeX community for excellent documentation

## 📸 Preview

![Resume Preview](preview.png)
*Preview of the compiled resume (add a screenshot of your PDF here)*

## 📞 Support

If you have any questions or need help customizing the template:
- Open an issue on GitHub
- Check existing issues for solutions
- Refer to the LaTeX documentation

---

⭐ If you found this template helpful, please give it a star on GitHub!

## 📋 Changelog

### Version 1.0.0 (Current)
- Initial release
- Clean academic/professional template
- ATS-friendly design
- Multiple customization options
- Comprehensive documentation

## 🔧 Technical Details

### Custom Commands Used

The template includes several custom LaTeX commands for consistent formatting:

- \resumeItem{description}{additional_info} - For bullet points with optional right-aligned info
- \resumeSubheading{title}{date}{subtitle}{location} - For main section entries
- \resumeProjectHeading{title}{date} - For project entries
- \resumeSubHeadingListStart and \resumeSubHeadingListEnd - For section containers

### Margin and Spacing Settings

The template uses custom margin settings for optimal space utilization:
- Reduced side margins for more content space
- Adjusted top and bottom margins
- Custom spacing between sections and items

### Icon Integration

FontAwesome5 icons are used throughout the template:
- Contact information icons (phone, email, LinkedIn, etc.)
- Section bullet points
- Social media and professional profile links

### Key Features of This Template

- **Fully customizable sections** - Easy to add, remove, or modify sections
- **Professional typography** - Clean fonts and proper spacing
- **ATS-compatible** - Machine-readable format for applicant tracking systems
- **Academic-focused** - Designed for researchers and academics
- **Multi-column layouts** - Efficient use of space for skills and coursework
- **Hyperlinked elements** - Clickable links for digital versions
- **Print-friendly** - Optimized for both screen and print viewing

### Sample Usage

To use this template:
1. Replace all personal information with your own
2. Update the education section with your degrees
3. Add your research and work experience
4. Include your publications and projects
5. Customize the technical skills section
6. Add your honors and awards

### Troubleshooting

**Common Issues:**
- Missing packages: Install the required LaTeX packages listed above
- Font issues: Make sure FontAwesome5 is properly installed
- Compilation errors: Check for typos in LaTeX commands
- Spacing issues: Adjust \vspace commands as needed

**Performance Tips:**
- Use pdflatex for faster compilation
- Comment out unused font packages
- Optimize images if adding any graphics

---

**Made with ❤️ for the LaTeX and academic community**

Remember to update the repository URL and add your own preview image!

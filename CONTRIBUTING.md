> [فارسی](CONTRIBUTING.fa.md) | **English**

# 🤝 Contributing to World Logos Archive

We warmly welcome your contributions! To ensure smooth and effective collaboration, please follow the guidelines below.

## ✅ What You Can Contribute

- **Add new logos**: Public domain, properly licensed, or with explicit permission
- **Fix file names and structure**: Improve organization and standardization  
- **Add LICENSE files**: Legal information and licensing details
- **Translate documentation**: Help internationalize the project
- **Improve organization**: Optimize categorization and folder structure
- **Enhance visual quality**: Fix and optimize images

## 📂 Folder & File Guidelines

### Folder Structure
- Place logos in appropriate category folders
- Use lowercase, hyphenated folder names (`nike`, `apple-inc`, `coca-cola`)
- For large companies with subsidiaries, use hierarchical structure

### File Formats
- **Priority**: `.svg` (vector and scalable)
- **Complementary formats**: `.ai`, `.eps`, `.png` (minimum 1000x1000 pixels)
- **Additional formats**: `.psd`, `.sketch`, `.fig` (if available)

### File Naming Convention
```
brand-name-logo.svg
brand-name-logo-white.svg
brand-name-logo-black.svg
brand-name-icon.svg
brand-name-wordmark.svg
```

### Required Files
- `LICENSE.txt`: Legal information and source details
- `README.md`: Brief brand description (optional)

## 🔒 Legal & Copyright Requirements

### Acceptable Logos
- **Public domain**: Expired or freely available logos
- **Officially licensed**: Logos with CC or similar licenses
- **Explicit permission**: Written authorization from copyright holder

### Required Documentation
- Official source link
- Date retrieved
- License type (CC0, CC BY, GPL, etc.)
- When in doubt, don't include the logo

### Prohibited Content
- Copyright infringement
- Modified logos without permission
- Fake or unofficial logos

## 📝 Contribution Process

### 1. Setup
```bash
# Fork the repository
git clone https://github.com/borodayeh/world-logos-archive.git 
cd world-logos-archive

# Create new branch
git checkout -b add-logo-brandname
```

### 2. Add Logo
```
brands/
  new-brand/
    ├── new-brand-logo.svg
    ├── new-brand-logo.png
    ├── new-brand-logo.ai
    └── LICENSE.txt
```

### 3. Complete LICENSE.txt
```
Brand: [Brand Name]
Source: [Official Source]
License: [License Type]
Date Retrieved: [Date]
URL: [Source URL]
Notes: [Additional Information]
```

### 4. Commit Changes
```bash
git add .
git commit -m "Add [brand-name] logo with SVG and PNG formats"
git push origin add-logo-brandname
```

### 5. Create Pull Request
- Clear and descriptive title
- Complete description of changes
- Preview images (when possible)
- Reference any related issues

## 🔍 Approval Criteria

### Technical Requirements
- Appropriate image quality
- Standard file formats
- Correct folder structure
- Proper file naming

### Legal Requirements
- Valid license
- Trustworthy source
- No copyright violations

### Quality Standards
- Clean images without noise
- Correct colors
- Proper aspect ratios
- No duplicates or outdated versions

## ⚠️ Important Notes

### Security
- Don't upload suspicious files
- Use trusted sources only
- Scan binary files for malware

### Quality Control
- Avoid duplicates
- Ensure current versions
- Maintain high quality standards

### Responsibility
- Verify legal information accuracy
- Respect copyright laws
- Honor intellectual property rights

## 🚀 After Submission

- Review within 7 business days
- Feedback provided if needed
- Merge after approval
- Automated quality checks

## 📊 Contribution Statistics

- **Response time**: Usually 1-3 days
- **Approval rate**: ~85% for properly formatted submissions
- **Common issues**: Missing LICENSE files, incorrect formats

## 🛠️ Tools & Resources

### Recommended Tools
- **Vector editing**: Inkscape (free), Adobe Illustrator
- **Image optimization**: TinyPNG, SVGO
- **File validation**: SVG validators

### Helpful Resources
- [Creative Commons License Guide](https://creativecommons.org/licenses/)
- [SVG Optimization Guide](https://jakearchibald.github.io/svgomg/)
- [Copyright Basics](https://www.copyright.gov/what-is-copyright/)

## 🤔 FAQ

**Q: Can I add logos from Google Images?**
A: Only if you can verify the legal source and licensing. We recommend official brand resources.

**Q: What if I'm unsure about licensing?**
A: When in doubt, don't include it. Contact the brand directly or check their official media/press kit.

**Q: How do I handle variations of the same logo?**
A: Include all official variations (horizontal, vertical, monochrome, etc.) in separate files.

## 📞 Contact & Support

- **Technical issues**: Open an issue
- **Legal questions**: Direct email to maintainers
- **Feature requests**: Use Discussions section
- **General help**: Check existing issues first

## 🌟 Recognition

Contributors will be:
- Listed in project contributors
- Credited in release notes
- Eligible for contributor badges

---

Thank you for helping make this project better! 🙏

**Note**: Please sync with the main repository before contributing to avoid conflicts.

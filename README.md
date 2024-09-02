# LicenseWise 🔑📜

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge)](https://github.com/amirallami-code/license-wise/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg?style=for-the-badge)](https://github.com/ellerbrock/open-source-badges/)

A comprehensive guide to understanding, choosing, and applying software licenses

## 📚 Table of Contents

- [Introduction](#introduction)
- [Why Licenses Matter](#why-licenses-matter)
- [Types of Licenses](#types-of-licenses)
  - [Open Source Licenses](#open-source-licenses)
  - [Proprietary Licenses](#proprietary-licenses)
- [Choosing the Right License](#choosing-the-right-license)
- [How to Apply a License](#how-to-apply-a-license)
  - [Step-by-Step Guide](#step-by-step-guide)
  - [GitHub-Specific Instructions](#github-specific-instructions)
- [License Comparison](#license-comparison)
- [GitHub's Default Licenses](#githubs-default-licenses)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A software license is a legal instrument governing the use or redistribution of software. This comprehensive guide helps you understand various licenses, choose the best option for your project, and correctly apply it to your repository.

## Why Licenses Matter

Licenses are crucial for several reasons:

1. **Legal Protection**: They safeguard the intellectual property rights of developers.
2. **Usage Clarity**: They specify the terms of software use for users and contributors.
3. **Collaboration Framework**: They provide guidelines for project collaboration.
4. **Legal Compliance**: They help prevent potential legal issues and misunderstandings.
5. **Attribution**: They ensure proper credit is given to the original developers.
6. **Community Building**: They can attract or deter certain types of contributors and users.
7. **Business Strategy**: They impact the ability to monetize or distribute software.
8. **Liability Limitation**: Many licenses include clauses that limit the developer's liability.
9. **Innovation Promotion**: Open source licenses, in particular, can foster innovation by allowing others to build upon existing work.

## Types of Licenses

### Open Source Licenses

1. **MIT License**
   - Simple and permissive
   - Allows commercial and private use
   - Requires copyright and license notices

2. **GNU General Public License (GPL)**
   - Ensures software freedom
   - Requires derivative works to remain open source
   - Versions: GPLv2, GPLv3

3. **Apache License 2.0**
   - Suitable for large projects
   - Includes patent rights
   - Requires stating changes

4. **BSD Licenses**
   - Family of permissive free software licenses
   - Minimal restrictions on use and redistribution

5. **Mozilla Public License 2.0**
   - Weak copyleft license
   - File-level copyleft

6. **GNU Lesser General Public License (LGPL)**
   - Designed for software libraries
   - Allows linking from non-GPL programs

7. **Eclipse Public License (EPL)**
   - Designed for the Eclipse project
   - Includes patent grant provisions

8. **Artistic License 2.0**
   - Perl-friendly license
   - Allows commercial use

9. **ISC License**
   - Functionally equivalent to BSD 2-Clause and MIT
   - Preferred by OpenBSD

10. **GNU Affero General Public License (AGPL)**
    - Similar to GPL, but also covers network use

### Proprietary Licenses

1. **Proprietary Software**
   - All rights reserved
   - Typically for commercial software

2. **Custom Licenses**
   - Tailored to specific business needs
   - Can combine various terms

3. **Dual Licensing**
   - Offering software under two different licenses
   - Often one open source and one proprietary

4. **Shared Source**
   - Microsoft's model allowing source code access with restrictions

5. **Freemium**
   - Basic features are free, but premium features require payment

## Choosing the Right License

Consider these factors when choosing a license:

1. **Project Goals**: Define your project's objectives (e.g., community growth, monetization).
2. **Target Community**: Identify your intended user and contributor base.
3. **Compatibility**: Ensure compatibility with libraries and dependencies used.
4. **Business Model**: Align the license with your monetization strategy.
5. **Patent Rights**: Consider whether patent protection is necessary.
6. **Derivative Works**: Decide how you want others to use and build upon your work.
7. **Project Size and Complexity**: Different licenses may suit projects of varying scales.
8. **Industry Standards**: Consider common practices in your field.
9. **Legal Jurisdiction**: Be aware of how different licenses may be interpreted in various countries.
10. **Future Flexibility**: Think about potential changes in project direction.

## How to Apply a License

### Step-by-Step Guide

1. Select an appropriate license based on the factors discussed above.
2. Create a `LICENSE` or `LICENSE.md` file in your project's root directory.
3. Copy the full text of your chosen license into the file.
4. Add a short license notice to the top of each source file in your project.
5. Include licensing information in your project's documentation (e.g., README.md).
6. If using dependencies, ensure license compatibility and include necessary attributions.

Example for adding to the top of code files:

```python
# Copyright (c) 2024 Amirhossein Allami
# This code is licensed under the MIT License.
# For full license text, see the LICENSE file in the project root.

def main():
    print("Hello, LicenseWise!")

if __name__ == "__main__":
    main()
```

### GitHub-Specific Instructions

1. Navigate to your repository on GitHub.
2. Click the "Add file" button and select "Create new file".
3. Name the file `LICENSE` or `LICENSE.md`.
4. Above the editor, click "Choose a license template".
5. Browse available licenses and select the desired one.
6. Fill in any required fields (e.g., full name, year).
7. Click "Review and submit".
8. Add a commit message and commit the new license file to your repository.

## License Comparison

| License | Permissions | Conditions | Limitations |
|---------|-------------|------------|-------------|
| MIT | Commercial use, Distribution, Modification, Private use | License and copyright notice | Liability, Warranty |
| GPLv3 | Commercial use, Distribution, Modification, Patent use, Private use | Disclose source, License and copyright notice, Same license | Liability, Warranty |
| Apache 2.0 | Commercial use, Distribution, Modification, Patent use, Private use | License and copyright notice, State changes | Trademark use, Liability, Warranty |
| BSD 3-Clause | Commercial use, Distribution, Modification, Private use | License and copyright notice | Liability, Warranty |
| MPL 2.0 | Commercial use, Distribution, Modification, Patent use, Private use | Disclose source, License and copyright notice, Same license (file) | Liability, Trademark use, Warranty |
| AGPL v3 | Commercial use, Distribution, Modification, Patent use, Private use | Disclose source, License and copyright notice, Network use is distribution, Same license | Liability, Warranty |
| Unlicense | Commercial use, Distribution, Modification, Private use | N/A | Liability, Warranty |

## GitHub's Default Licenses

GitHub offers several popular licenses as templates when creating a new repository. Here's a brief overview of each:

1. **Apache License 2.0**
   - Permissive license that also provides an express grant of patent rights from contributors to users.

2. **GNU General Public License v3.0**
   - Strong copyleft license that requires distributors of derivative works to make their source code available under the same terms.

3. **MIT License**
   - Short and simple permissive license with conditions only requiring preservation of copyright and license notices.

4. **BSD 2-Clause "Simplified" License**
   - Permissive license that comes in two variants: BSD 2-Clause and BSD 3-Clause.

5. **BSD 3-Clause "New" or "Revised" License**
   - Similar to the 2-Clause version, but with a 3rd clause that prohibits others from using the name of the project or its contributors to promote derived products without written consent.

6. **Boost Software License 1.0**
   - Simple permissive license, similar to the BSD 2-Clause License, but with an explicit disclaimer of the implied warranty of merchantability and fitness for a particular purpose.

7. **Creative Commons Zero v1.0 Universal**
   - Public domain dedication, waiving all rights to the work worldwide under copyright law.

8. **Eclipse Public License 2.0**
   - Copyleft license used by the Eclipse Foundation for its software, with provisions regarding patents and use of trademarks.

9. **GNU Affero General Public License v3.0**
   - Similar to the GNU GPLv3, but with an additional term to allow users who interact with the licensed software over a network to receive the source.

10. **GNU General Public License v2.0**
    - Older version of the GNU GPL, still widely used.

11. **GNU Lesser General Public License v2.1**
    - Designed as a compromise between the strong copyleft of the GPL and more permissive licenses such as the MIT and BSD licenses.

12. **Mozilla Public License 2.0**
    - Weak copyleft license, characterized as a middle ground between permissive and strong copyleft licenses.

13. **The Unlicense**
    - A license with no conditions whatsoever which dedicates works to the public domain.

## Frequently Asked Questions

1. **Q: Can I change the license of my project?**
   A: Yes, but it can be complicated, especially if you've had other contributors. You may need to get permission from all contributors to change the license.

2. **Q: What happens if I don't choose a license?**
   A: Without a license, your project is copyright by default, and others can't use, modify, or distribute it without your permission.

3. **Q: Can I use multiple licenses?**
   A: Yes, but it can create complexities and should be done carefully. This is known as dual licensing or multi-licensing.

4. **Q: How do I handle dependencies with different licenses?**
   A: You need to ensure that your project's license is compatible with the licenses of its dependencies. Some licenses may require you to release your project under the same or a compatible license.

5. **Q: Do I need a different license for documentation?**
   A: You can use the same license for your code and documentation, but some projects choose to use separate licenses, such as Creative Commons licenses for documentation.

6. **Q: Can I use code with a copyleft license in my proprietary software?**
   A: Generally, no. Copyleft licenses like GPL require that any derivative work be distributed under the same license terms.

7. **Q: What's the difference between "use", "modify", and "distribute" in license terms?**
   A: "Use" refers to running the software, "modify" means changing the code, and "distribute" involves sharing the original or modified version with others.

8. **Q: How do online services and SaaS relate to open source licenses?**
   A: Most open source licenses don't require you to share your code if you're only providing a service (not distributing the software). The AGPL is an exception to this.

9. **Q: What's a "patent grant" in a license?**
   A: It's a term that explicitly grants patent rights to users, protecting them from potential patent litigation by the original authors.

10. **Q: How do I enforce my chosen license?**
    A: While you can take legal action for license violations, most issues are resolved through communication. Make sure your license terms are clear and easily accessible.

## Additional Resources

- [Choose a License](https://choosealicense.com/)
- [Open Source Initiative](https://opensource.org/licenses)
- [GNU Licenses](https://www.gnu.org/licenses/)
- [Creative Commons](https://creativecommons.org/licenses/)
- [TLDRLegal](https://tldrlegal.com/) - Simplified explanations of open source licenses
- [SPDX License List](https://spdx.org/licenses/) - Standardized list of license identifiers
- [Software Package Data Exchange (SPDX)](https://spdx.dev/) - Standard for communicating software bill of material information
- [Free Software Foundation's License List](https://www.gnu.org/licenses/license-list.html)
- [OSI's License Proliferation Committee Report](https://opensource.org/proliferation-report)
- [GitHub's Licensing a Repository Guide](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
- [The Legal Side of Open Source](https://opensource.guide/legal/) by GitHub

## Contributing

We welcome your contributions to improve this guide! Please create an Issue or Pull Request for any suggestions or corrections. Before contributing, please read our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

⭐️ If you find this repository helpful, please consider giving it a star!

Made with ❤️ by [Amirhossein Allami](https://github.com/amirallami-code)

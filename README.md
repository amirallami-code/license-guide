# License Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg?style=for-the-badge)](https://github.com/ellerbrock/open-source-badges/)
[![GitHub Stars](https://img.shields.io/github/stars/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/issues)

A comprehensive guide to understanding, choosing, and applying software licenses

## 📚 Table of Contents

- [Introduction](#introduction)
- [Why Licenses Matter](#why-licenses-matter)
- [Types of Licenses](#types-of-licenses)
  - [Open Source Licenses](#open-source-licenses)
  - [Proprietary Licenses](#proprietary-licenses)
- [GitHub-Specific Licenses](#github-specific-licenses)
- [Choosing the Right License](#choosing-the-right-license)
- [How to Apply a License](#how-to-apply-a-license)
  - [Step-by-Step Guide](#step-by-step-guide)
  - [GitHub-Specific Instructions](#github-specific-instructions)
- [License Comparison](#license-comparison)
- [Creative Commons Licenses](#creative-commons-licenses)
- [Compatibility Between Licenses](#compatibility-between-licenses)
- [Changing or Updating Licenses](#changing-or-updating-licenses)
- [International Aspects of Licensing](#international-aspects-of-licensing)
- [Licensing and Monetization](#licensing-and-monetization)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A software license is a legal instrument that governs the use, modification, and distribution of software. This comprehensive guide aims to help you understand various licenses, choose the most suitable option for your project, and correctly apply it to your repository.

## Why Licenses Matter

Licenses are crucial for several reasons:

1. **Protection of Rights**: They safeguard the intellectual property rights of developers.
2. **Clarity**: They clearly specify the terms of software use for users and contributors.
3. **Collaboration**: They provide a framework for collaboration and contribution to projects.
4. **Legal Compliance**: They help prevent potential legal issues and misunderstandings.
5. **Recognition**: They ensure proper attribution and recognition of developers' work.
6. **Community Building**: They can attract or deter certain types of contributors and users.
7. **Business Strategy**: They can impact your ability to monetize or distribute your software.
8. **Innovation Promotion**: They can encourage or restrict innovation based on their terms.
9. **Interoperability**: They can affect how your software can be integrated with other projects.

## Types of Licenses

### Open Source Licenses

1. **MIT License**
   - Simple and permissive
   - Allows commercial and private use
   - Requires copyright and license notices
   
2. **GNU General Public License (GPL)**
   - Ensures software freedom
   - Requires derivative works to remain open source
   - Different versions: GPLv2, GPLv3
   
3. **Apache License 2.0**
   - Suitable for large projects
   - Includes patent rights
   - Requires stating changes
   
4. **BSD Licenses**
   - Family of permissive free software licenses
   - Minimal restrictions on the use and redistribution of covered software

5. **Mozilla Public License 2.0**
   - Weak copyleft license
   - File-level copyleft

6. **GNU Lesser General Public License (LGPL)**
   - Designed for libraries
   - Allows linking from non-GPL programs

7. **Eclipse Public License (EPL)**
   - Copyleft license used by the Eclipse Foundation
   - Includes patent grant

8. **GNU Affero General Public License (AGPL)**
   - Similar to GPL, but also covers network use

9. **ISC License**
   - Functionally equivalent to the BSD 2-Clause and MIT licenses

10. **Artistic License 2.0**
    - Used primarily for Perl modules and applications

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
   - Microsoft's program that allows access to source code under certain conditions

5. **Freemium**
   - Basic features are free, but advanced features require payment

## GitHub-Specific Licenses

GitHub provides a selection of licenses that can be easily added to repositories. Here's a list of licenses available through GitHub's license picker:

1. Apache License 2.0
2. GNU General Public License v3.0
3. MIT License
4. BSD 2-Clause "Simplified" License
5. BSD 3-Clause "New" or "Revised" License
6. Boost Software License 1.0
7. Creative Commons Zero v1.0 Universal
8. Eclipse Public License 2.0
9. GNU Affero General Public License v3.0
10. GNU General Public License v2.0
11. GNU Lesser General Public License v2.1
12. Mozilla Public License 2.0
13. The Unlicense

## Choosing the Right License

Consider these factors when choosing a license:

1. **Project Goals**: Do you want the project to be fully open or maintain more control?
2. **Target Community**: Do you want to foster a community of contributors?
3. **Compatibility**: Are you using libraries with specific licenses?
4. **Business Model**: Do you plan to commercialize your project?
5. **Patent Rights**: Do you need to consider patent protection?
6. **Derivative Works**: How do you want others to use and build upon your work?
7. **Project Size and Complexity**: Different licenses may be more suitable for larger or more complex projects.
8. **Industry Standards**: Some industries have preferred licenses.
9. **Geographic Considerations**: Different regions may have specific legal requirements.
10. **Future Plans**: Consider how your choice might affect future developments or partnerships.

## How to Apply a License

### Step-by-Step Guide

1. Choose an appropriate license based on the factors discussed above.
2. Create a `LICENSE` file in the root directory of your project.
3. Copy the full text of your chosen license into the `LICENSE` file.
4. Add a short license notice to the top of each source file in your project.
5. Include licensing information in your project's documentation.

Example for adding to the top of code files:

```python
# Copyright (c) 2024 Amirhossein Allami
# This code is licensed under the MIT License.
# For more information, see the LICENSE file in the project root.

def main():
    print("Hello, License Guide!")

if __name__ == "__main__":
    main()
```

### GitHub-Specific Instructions

1. Navigate to your repository on GitHub.
2. Click on the "Add file" button and select "Create new file".
3. Name the file `LICENSE` or `LICENSE.md`.
4. Click on "Choose a license template" button.
5. Select your desired license from the list.
6. Fill in the required fields (e.g., full name).
7. Click on "Review and submit" button.
8. Commit the new license file to your repository.

## License Comparison

| License | Commercial Use | Modify | Distribute | Patent Use | Private Use | Sublicense | Trademark Use | Conditions |
|---------|----------------|--------|------------|------------|-------------|------------|---------------|------------|
| MIT     | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Include copyright & license |
| GPLv3   | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Disclose source, same license |
| Apache 2.0 | ✅          | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | State changes, patent grant |
| BSD 3-Clause | ✅        | ✅     | ✅         | ❌         | ✅          | ✅         | ❌            | Include license |
| MPL 2.0 | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Disclose source |
| LGPL v3 | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Disclose source, library modifications |
| AGPL v3 | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Disclose source, network use |
| EPL 2.0 | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Disclose source, state changes |
| Unlicense | ✅           | ✅     | ✅         | ✅         | ✅          | ✅         | ✅            | No conditions |
| Proprietary | ❌         | ❌     | ❌         | ❌         | ✅          | ❌         | ✅            | Requires explicit permission |

## Creative Commons Licenses

While primarily used for creative works, some software projects use Creative Commons licenses for documentation:

1. CC0 (No Rights Reserved)
2. CC BY (Attribution)
3. CC BY-SA (Attribution-ShareAlike)
4. CC BY-ND (Attribution-NoDerivs)
5. CC BY-NC (Attribution-NonCommercial)
6. CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)
7. CC BY-NC-ND (Attribution-NonCommercial-NoDerivs)

## Compatibility Between Licenses

License compatibility is crucial when combining software or libraries with different licenses. Here's a brief overview:

- MIT and BSD licenses are generally compatible with most other licenses.
- GPL licenses are compatible with each other but may not be compatible with some other licenses.
- Apache License 2.0 is compatible with GPLv3, but not with GPLv2.
- Creative Commons licenses are not recommended for software and may cause compatibility issues.

Always check the specific terms of each license when combining software under different licenses.

## Changing or Updating Licenses

Changing the license of a project can be complex:

1. If you're the sole copyright holder, you can change the license at will.
2. If there are multiple contributors, you need permission from all copyright holders.
3. Some licenses (like GPL) make it difficult or impossible to change to a more restrictive license.
4. Consider using tools like CLA (Contributor License Agreement) to manage contributions and potential license changes.

## International Aspects of Licensing

Software licensing can have international implications:

1. Most open source licenses are designed to be internationally applicable.
2. Some countries may have specific requirements or interpretations of certain license terms.
3. The Berne Convention provides a framework for international copyright protection.
4. Consider consulting with legal experts when dealing with international licensing issues.

## Licensing and Monetization

Different licenses can affect your ability to monetize your software:

1. Permissive licenses (MIT, Apache) allow for easier commercial use and integration.
2. Copyleft licenses (GPL) can be monetized through support, services, or dual licensing.
3. Proprietary licenses offer the most control over monetization but may limit adoption.
4. Open core models combine open source and proprietary elements.

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

6. **Q: Can I use code snippets from Stack Overflow in my project?**
   A: Code on Stack Overflow is typically under the CC BY-SA license. It's best to attribute the source and check if it's compatible with your project's license.

7. **Q: How do patent rights work with open source licenses?**
   A: Some licenses, like Apache 2.0, include explicit patent grants. Others, like MIT, don't mention patents, which can create uncertainty.

8. **Q: Can I revoke an open source license?**
   A: Generally, no. Once you've released code under an open source license, that version remains under that license. However, you can stop distributing new versions under the same license.

## Additional Resources

- [Choose a License](https://choosealicense.com/)
- [Open Source Initiative](https://opensource.org/licenses)
- [GNU Licenses](https://www.gnu.org/licenses/)
- [Creative Commons](https://creativecommons.org/licenses/)
- [TLDRLegal](https://tldrlegal.com/) - Simplified explanations of open source licenses
- [SPDX License List](https://spdx.org/licenses/) - Standardized list of license identifiers
- [FOSSology](https://www.fossology.org/) - Open source license compliance software
- [CopyrightX](https://copyx.org/) - Free online course on copyright law
- [Software Freedom Law Center](https://softwarefreedom.org/) - Legal services for free and open source software projects

## Contributing

We welcome your contributions to improve this guide! Please create an Issue or Pull Request for any suggestions or corrections.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

⭐️ If you find this repository helpful, please consider giving it a star!

Made with ❤️ by [Amirhossein Allami](https://github.com/amirallami-code)

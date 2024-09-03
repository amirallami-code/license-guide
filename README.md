# License Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg?style=for-the-badge)](https://github.com/ellerbrock/open-source-badges/)
[![GitHub Stars](https://img.shields.io/github/stars/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/amirallami-code/license-guide.svg?style=for-the-badge)](https://github.com/amirallami-code/license-guide/issues)

A comprehensive guide to understanding, choosing, and applying software licenses

## 🌐 Available Languages

- 🇬🇧 [English](README.md)
- 🇮🇷 [Persian (فارسی)](README.fa.md)

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
- [Practical Examples and Case Studies](#practical-examples-and-case-studies)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

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
| GPLv3   | ✅             | ✅     | ✅         | ✅         | ✅          | ❌         | ❌            | Must disclose source, same license for derivatives |
| Apache 2.0 | ✅          | ✅     | ✅         | ✅         | ✅          | ✅         | ✅            | Must include license and notices, State changes, provides explicit grant of patent rights |
| BSD 2-Clause | ✅        | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Must include copyright & license |
| LGPLv3  | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ❌            | Modifications must be licensed under LGPL |
| MPL 2.0 | ✅             | ✅     | ✅         | ✅         | ✅          | ✅         | ✅            | Modifications must be documented, Same license for files |
| AGPLv3  | ✅             | ✅     | ✅         | ✅         | ✅          | ❌         | ❌            | Disclose source for network interactions, Same license for derivatives |

## Creative Commons Licenses

Creative Commons (CC) licenses are often used for content rather than software. Here are some key types:

1. **CC BY**: Allows distribution, modification, and commercial use as long as credit is given to the creator.
2. **CC BY-SA**: Same as CC BY, but derivatives must be licensed under the same terms.
3. **CC BY-ND**: Allows redistribution, commercial and non-commercial, as long as it is passed along unchanged with credit to the creator.
4. **CC BY-NC**: Allows modification and distribution for non-commercial purposes only, with credit to the creator.
5. **CC BY-NC-SA**: Same as CC BY-NC, but derivatives must be licensed under the same terms.
6. **CC BY-NC-ND**: The most restrictive license, only allowing others to download your works and share them with others as long as they credit you, but they can’t change them in any way or use them commercially.

## Compatibility Between Licenses

Compatibility between different licenses is crucial when combining multiple components or dependencies within a project. Some licenses, such as MIT and Apache 2.0, are generally compatible with most others. However, licenses like GPL have strict requirements that might conflict with more permissive licenses. It’s important to verify the compatibility of all licenses involved before combining or distributing software.

## Changing or Updating Licenses

If you need to change the license of a project:

1. **Review Current License**: Ensure that you are legally permitted to change the license.
2. **Choose New License**: Select a license that aligns with the new direction of your project.
3. **Notify Contributors**: Inform all contributors of the change, especially if contributions are licensed under the original license.
4. **Update Documentation**: Replace the old license with the new one in the `LICENSE` file and update all references.
5. **Public Announcement**: Consider making a public announcement or update log to inform users of the license change.

## International Aspects of Licensing

Software licenses might be interpreted differently in various jurisdictions. Some licenses include clauses to address international concerns, such as the applicability of local laws or the rights granted under different legal systems. Be mindful of these aspects when selecting a license, especially if your project has a global audience.

## Licensing and Monetization

Licensing can be a crucial part of your business model:

1. **Dual Licensing**: Offer an open-source version under a permissive license and a proprietary version with additional features.
2. **Freemium Models**: Provide a basic version of your software for free, with the option to purchase advanced features or services.
3. **Subscription-Based**: Offer the software under a subscription model, with continuous updates and support.

## Practical Examples and Case Studies

Reviewing real-world examples can provide insights into how licensing choices impact a project's success. For instance, the transition of MySQL from GPL to dual licensing, or the decision by React.js to switch from the BSD+Patents license to MIT, had significant implications for their communities.

## Frequently Asked Questions

**Q1: Can I change the license of a project after it's been released?**
A: Yes, but it depends on the current license's terms and whether you have permission from all contributors.

**Q2: Do I need a lawyer to choose a license?**
A: Not necessarily, but consulting a legal expert can be beneficial for complex projects or if you have specific legal concerns.

**Q3: Can I use multiple licenses for different parts of my project?**
A: Yes, but this can complicate your project’s legal framework. Ensure that all licenses are compatible.

## Additional Resources

- [ChooseALicense.com](https://choosealicense.com/)
- [Open Source Initiative](https://opensource.org/licenses)
- [Creative Commons License Chooser](https://creativecommons.org/choose/)
- [SPDX License List](https://spdx.org/licenses/)
- [GitHub’s Guide to Licensing](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository)

## Contributing

We welcome contributions to this License Guide! Here's how you can contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This guide is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this guide, as long as proper attribution is given.

## Contact

For any questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/amirallami-code/license-guide/issues) or directly to [Amirhossein Allami](mailto:amirallami@gmail.com).

---

We hope this guide helps you navigate the complex world of software licensing. Remember, while this guide provides general information, it's always best to consult with a legal professional for specific advice regarding your software projects and licensing needs.

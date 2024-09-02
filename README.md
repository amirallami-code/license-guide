# LicenseWise 🔑📜

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/amirallami-code/license-wise/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

A comprehensive guide to understanding, choosing, and using software licenses

## 📚 Table of Contents

- [Introduction](#introduction)
- [Why Licenses Matter](#why-licenses-matter)
- [Types of Licenses](#types-of-licenses)
  - [Open Source Licenses](#open-source-licenses)
  - [Proprietary Licenses](#proprietary-licenses)
- [Choosing the Right License](#choosing-the-right-license)
- [How to Apply a License](#how-to-apply-a-license)
- [License Comparison](#license-comparison)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A software license is a legal document that specifies the terms of use, modification, and distribution of software. This guide helps you understand various licenses and choose the best option for your project.

## Why Licenses Matter

Licenses are important for several reasons:

1. **Protection of Rights**: They protect the intellectual and material rights of developers.
2. **Clarity**: They specify the terms of software use for users.
3. **Collaboration**: They provide a framework for collaboration and contribution to projects.
4. **Legal Compliance**: They help prevent potential legal issues.
5. **Recognition**: They ensure recognition of developers' work.

## Types of Licenses

### Open Source Licenses

1. **MIT License**
   - Simple and permissive
   - Allows commercial and private use
   - Requires copyright and license notices
   
   Example:
   ```
   Copyright (c) [year] [fullname]

   Permission is hereby granted, free of charge, to any person obtaining a copy
   of this software and associated documentation files (the "Software"), to deal
   in the Software without restriction, including without limitation the rights
   to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
   copies of the Software, and to permit persons to whom the Software is
   furnished to do so, subject to the following conditions:

   [The rest of the license text...]
   ```

2. **GNU General Public License (GPL)**
   - Ensures software freedom
   - Requires derivative works to remain open source
   - Different versions: GPLv2, GPLv3
   
   Example (part of GPLv3):
   ```
   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   [The rest of the license text...]
   ```

3. **Apache License 2.0**
   - Suitable for large projects
   - Includes patent rights
   - Requires stating changes
   
   Example:
   ```
   Copyright [yyyy] [name of copyright owner]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   [The rest of the license text...]
   ```

### Proprietary Licenses

1. **Proprietary Software**
   - All rights reserved
   - Typically for commercial software
   
   Example:
   ```
   © [year] [company name]. All rights reserved.
   Any use, copying, or distribution without written permission is prohibited.
   ```

2. **Custom Licenses**
   - Tailored to specific business needs
   - Can combine various terms

## Choosing the Right License

Consider these factors when choosing a license:

1. **Project Goals**: Do you want the project to be fully open or maintain more control?
2. **Target Community**: Do you want a community of contributors?
3. **Compatibility**: Are you using libraries with specific licenses?
4. **Business Model**: Do you plan to commercialize?

## How to Apply a License

1. Choose an appropriate license
2. Create a `LICENSE` file in the project root
3. Add license information to the main project files

Example for adding to the top of code files:

```python
# Copyright (c) 2024 Amir Allami
# This code is licensed under the MIT License.
# For more information, see the LICENSE file in the project root.

def main():
    print("Hello, LicenseWise!")

if __name__ == "__main__":
    main()
```

## License Comparison

| License | Commercial Use | Modify | Distribute | Conditions |
|---------|----------------|--------|------------|------------|
| MIT     | ✅             | ✅     | ✅         | Include copyright & license |
| GPLv3   | ✅             | ✅     | ✅         | Disclose source |
| Apache 2.0 | ✅          | ✅     | ✅         | State changes, patent grant |
| Proprietary | ❌         | ❌     | ❌         | Requires explicit permission |

## Frequently Asked Questions

1. **Q: Can I change the license of my project?**
   A: Yes, but it can be complicated, especially if you've had other contributors.

2. **Q: What happens if I don't choose a license?**
   A: Without a license, your project is copyright by default, and others can't use it.

3. **Q: Can I use multiple licenses?**
   A: Yes, but it can create complexities and should be done carefully.

## Additional Resources

- [Choose a License](https://choosealicense.com/)
- [Open Source Initiative](https://opensource.org/licenses)
- [GNU Licenses](https://www.gnu.org/licenses/)
- [Creative Commons](https://creativecommons.org/licenses/)

## Contributing

We welcome your contributions to improve this guide! Please create an Issue or Pull Request for any suggestions or corrections.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Amir Allami](https://github.com/amirallami-code)

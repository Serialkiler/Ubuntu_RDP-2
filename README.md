## ⚠️ Disclaimer

**Please read this disclaimer carefully before using this repository. By using this repository, you agree to the following terms and conditions.**

*If your GitHub account is flagged or suspended due to any activities associated with this repository, I cannot be held responsible. Please use this repository at your own risk. This repository is designed exclusively for educational purposes, providing resources and materials to enhance learning and foster educational growth.*

### 📚 Guidelines

When using this repository, please adhere to the following guidelines:

1. **Refrain from using this repository for the following activities:**
   - **Crypto Currency Mining**: This includes utilizing the repository for running resource-intensive processes to mine cryptocurrencies such as Bitcoin, Ethereum, or any other digital currency.
   - **Hacking**: This encompasses any attempts to gain unauthorized access, exploit vulnerabilities, or manipulate systems, networks, or data without proper authorization. Examples of hacking activities include breaching security systems, conducting phishing attacks, or launching denial-of-service (DoS) attacks.
   - **Malware Development**: It is strictly prohibited to use this repository for creating, distributing, or sharing malicious software, viruses, worms, ransomware, or any other form of harmful code.
   - **Unauthorized Access**: This refers to any attempts to access, modify, or retrieve sensitive information, systems, or accounts without appropriate authorization. This includes activities like unauthorized penetration testing, password cracking, or unauthorized access to private networks.
   - **Illegal Activities**: The repository should not be used for any illegal activities, such as distributing copyrighted content without permission, engaging in fraudulent activities, or promoting unlawful acts.

*Please note that these examples are not an exhaustive list. It is essential to use this repository responsibly and adhere to legal and ethical standards.*

**Remember, using this repository implies your acceptance of these guidelines and your commitment to using it responsibly.**

## 📖 About:
**Ubuntu RDP**: is an extraordinary repository that grants users a complimentary Ubuntu RDP server on GitHub's renowned hosted virtual machine, also referred to as the runner operating system (OS). Immerse yourself in a seamless experience with Ubuntu RDP, the perfect solution for unleashing the full potential of your projects. Harness the power of this exceptional offering today!

### 🤔 How to get an Ubuntu RDP server ?
To get an Ubuntu RDP server, you should know about: *How to use `GitHub's workflow` ?* If you are aware of GitHub's workflow usage then you must have heard about: *`inputs` (that are passed to the called workflow from the caller workflow).* If you have heard of GitHub's workflow and, *`inputs`* then it will be easy for you to get started because we gonna need some required information from you via *`inputs`*. You must be wounding: *Why is `inputs` needed ?* Well, we need them to configure following things:

| Input's field:    | Description: / Usages: / Details:                                                                    | Default values: |
| :----------------:|:---------------------------------------------------------------------------------------------------- | :-------------: |
| `hostname`        | Stores your input to set host's name according to your provided information.                         | `ubuntu`        |
| `username`        | Takes input from you to create a new user as per your given instruction.                             | `user`          |
| `password`        | Asks you to enter a passcode which is used later to setup a new user.                                | `root`          |
| `Pin`             | A numeric pincode is stored to set a PIN which is used to connect with RDP server.                   | `123456`        |
| `CRP`             | Requires a command that you have to get it from [`here`](http://remotedesktop.google.com/headless).    | -               |

After getting knowledge about above informations, you have to follow the given steps to get an Ubuntu RDP server: <br>
**Step 1:** You have to clone or crate a fork of [`this`](https://github.com/Diwash0007/Ubuntu_RDP) repository either to your GitHub's account or to your GitHub's organization account. <br>
**Step 2:** Go to your cloned or forked repository and, navigate to a section named as `Actions` to run [`this`](.github/workflows/Ubuntu_RDP.yml) workflow using your GitHub's account or your GitHub's organization account. <br>
**Step 3:** You will see a workflow named as `Ubuntu RDP` select that and, click `Run workflow` button to trigger [`this`](.github/workflows/Ubuntu_RDP.yml) workflow for further operations. <br>
**Step 4:** After that, you have to fill all required fields using `inputs` from my previous explanation then again click `Run workflow` button to finally start executing [`this`](.github/workflows/Ubuntu_RDP.yml) workflow. <br>
**Step 5:** After completing run and, getting success you can see your RDP according to your provided name at [`http://remotedesktop.google.com/headless`](http://remotedesktop.google.com/headless) and, you can access it via `Pin` that you provided during provision of *`inputs`* process.

## 📄 License:
```
   Copyright 2030 Díwash (Diwash0007)

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
## 💡 Credits:
**Main Scripture Credit:**
- [`Ubuntu_RDP.sh`](Ubuntu_RDP.sh)*(A Bash script to configure an Ubuntu RDP server.)* and, [`Keep_Running.sh`](Keep_Running.sh)*(A simple Bash script to keep Ubuntu RDP server running for about 5 hours.)*
  - By me [@Diwash0007](https://github.com/Diwash0007)

**Internal Utility Credit:**
- [`Cleanup.sh`](Cleanup.sh)*(A simple composite Bash script to clean GitHub Actions workflow environment to bare minimum space.)*
  - By [@rokibhasansagar](https://github.com/rokibhasansagar)

## 🤝 Support:
Thanks for those who are using this repository. I made this repository specifically for those who doesn't have computer like me. I spent a lot of my valuable time to make this possible. So, I would appreciate if you give this repository a star 🌟.

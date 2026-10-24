# Oasis Browser

Oasis is a modern, smooth, and lightweight web browser built on top of the Chromium engine. Designed from the ground up to prioritize user privacy, Oasis completely removes Google's built-in telemetry, tracking scripts, and data collection mechanisms. 

Key architectural components, memory management, and browser window rendering are built using Node.js to ensure a highly responsive browsing experience.

<img width="2557" height="1377" alt="Screenshot 2026-10-24 095404" src="https://github.com/user-attachments/assets/b313be57-353a-47ce-84d9-7af5b3ebe028" />

## Features

* **Zero Telemetry:** All background tracking, data logging, and automated reporting to Google infrastructure have been stripped out.
* **Custom Search Infrastructure:** Full user control over the default search engine configuration with no hardcoded commercial tracking partners.
* **Localization Capabilities:** Deep multi-language support enabling fast, seamless language switching within the core user interface.
* **Optimized UI Engine:** A clean, minimal layout designed to minimize system resources and maximize screen real estate.


## Installation and Execution

### For Users (Pre-compiled Binary)
Navigating to the Releases section of this repository provides access to the latest stable and beta installation packages. Download and execute the installer to deploy the browser to your system. Please note that you won't get an administrator prompt, the browserwill just installs.

# FOR COMPILING:
## System Requirements and Dependencies for SOURCE CODE

To compile or run the source code of Oasis, ensure you have the following environments configured on your system:

* Node.js (LTS version recommended)
* npm (Node Package Manager)
* Compatible operating systems: Windows 8.1 or later.

### For Developers (Running from Source)
To clone the repository and run the application locally for development or inspection purposes, execute the following commands in your terminal:

1. Clone the repository:
   git clone https://github.com/TinkerbyteYT/OasisBrowser

2. Navigate into the project directory:
   cd Oasis

3. Install the required Node.js dependencies defined in the package files:
   npm install

4. Start the application:
   npm start

## Licensing and Distribution Terms

Oasis Browser is an open-source software project distributed under the terms of the GNU General Public License v3.0 (GPLv3). 

Under the terms of this license:
* The source code remains 100% open and accessible to the public.
* Any modifications, forks, or derivative works distributed by third parties must also be made publicly available under the exact same GPLv3 license terms.
* Commercial entities or individual developers looking to modify this software or integrate proprietary code modifications without publishing their resulting source code are strictly prohibited from doing so without obtaining prior written authorization from the primary copyright holder.

## Release Status

This project is currently in the beta phase of development. Features, user interface components, and underlying engine optimizations are subject to frequent updates. It is recommended to review the release notes accompanying each tag for security patches and performance improvements.

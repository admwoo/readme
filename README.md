# Ecodata RecycleRight

<div align="center">
  <img src="logo.png" alt="Project Logo" width="600"/>
</div>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Project Description

Our waste tracker website provides an easy way to track waste usage, as well as learn more about recycling guidelines. Designed for anyone wanting to be more conscious of their carbon footprint, it solves all the unknowns and struggles with proper waste disposal by providing by providing a one-stop shop for all your recycling and trash guideline needs.

---

## Table of Contents

- [Quick Start](#quick-start)
- [Installation](#installation)
- [Features](#features)
- [Usage Examples](#usage-examples)
- [FAQ](#frequently-asked-questions)
- [License](#license)
- [Support](#support)

---

## Quick Start

Get up and running in less than 5 minutes:

### Prerequisites

- [Node.js] (latest version)


### Installation

#### Clone from Source
```bash
git clone https://github.com/admwoo/waste-tracker-f24.git
cd project-name
```
#### npm installs
```bash
npm install
npm install express
npm install body-parser
npm install express-session
npm install express-flash
npm install sqlite3
npm install ejs

```



### Basic Setup

1. **Start the development server**
   ```bash
   node server.js
   ```

2. **Open your browser** to `http://localhost:3002`

**That's it! Your project is now running.**

<div align="center">
  <img src="setup_3x.gif" alt="setup gif" width="600"/>
</div>

---

## Features

### Core Features

#### Feature 1: Waste Input and Tracker
<div align="center">
  <img src="waste_tracker.gif" alt="tracker gif" width="600"/>
</div>

With this feature, you can manually enter waste type and weight to track your waste usage. Entries will be saved to your account with timestamps accordingly. 

#### Feature 2: GreenScan Item Scanner (Work in Progress)

Have an item to dispose but don't know what it is or what to do with it? Scan your item, and we'll classify what the item is, and provide guidelines on how to dispose of it, logging it into your waste tracker. 

<div align="center">
  <img src="greenscan.png" alt="green scan ui" width="600"/>
</div>

This is the current user interface for the item scanner on the website. 

<div align="center">
  <img src="green_scan.gif" alt="green sca gif" width="600"/>
</div>

If you would like to run a demo of the scanner locally in your IDE, you can run the following command:

```bash
python python_scripts/trash_detect.py
```

#### Additional Features
- General Recycling guidelines
- Account Login and Signup
---

## 💡 Usage Examples

### Basic Usage

To access basic features such as the waste or progress tracker, you must login with an account. If you don't have an account, you can register one on the signup page.

## Frequently Asked Questions

### General Questions

**Q: What makes RecycleRight different from alternatives?**
A: Not only does RecycleRight provide a user friendly site to track you carbon footprint by waste disposal, but it also has object detection and classification abilities to seamlessly and quickly provide guidelines for an item and store it in the waste tracker.

**Q: Is RecycleRight suitable for production use?**
A: Unfortunately not currently. While you can access the website locally, there are still some features and aspects that are still in progress of developing. Feel free to still visit the website to use its current functionality, and we welcome any feedback you may have.

**Q: How do I know if the recycling guidelines apply to my local municipality?**
A: Unfortunately, the current guidelines only apply to the local Ann Arbor, MI area. We are currently working on expanding this other areas.


## License

This project is licensed under the MIT License.


## Acknowledgments

Special thanks to all our contributors at EcoData who made this project possible.

---

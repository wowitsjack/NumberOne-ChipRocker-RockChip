
# 🧙 NumberOne-ChipRocker 🧙

![Python](https://img.shields.io/badge/Python-3.7%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Maintenance](https://img.shields.io/badge/Maintenance-Active-green.svg)

(images/demo.jpg)

## Overview

The **NumberOne-ChipRocker Wizard** is an interface system tailored for RockChip devices. It facilitates interaction for tasks such as dumping, writing, and general interfacing with RKXXX devices.

## Features

- 🚀 **Efficient**: Built with Python, the ChipRocker Wizard provides a highly efficient means to interact with RockChip devices.
  
- 🛠️ **Comprehensive**: Beyond the basics, ChipRocker offers functionalities that go above and beyond traditional tools, such as alignment checks for specific RK devices, and offset support.
  
- 🧠 **Intuitive**: With a well-structured interface, users can easily navigate and execute commands without diving deep into documentation.

### A Comparative Analysis

| Feature                        | ChipRocker       | rkflashtool      |
|--------------------------------|------------------|------------------|
| **Universal Interface**        | ✅               | ❌               |
| **Alignment Check**            | ✅               | ❌               |
| **Interactive Wizard**         | ✅               | ❌               |
| **Efficient Data Dumping**     | ✅               | ⚠️ Partial       |
| **Extended Device Support**    | ✅               | ❌               |
| **Animated UI**                | ✅               | ❌               |
| **Intelligent Error Handling** | ✅               | ⚠️ Limited       |

## Installation & Setup

1. Clone the repository:
```bash
$ git clone https://github.com/wowitsjack/NumberOne-ChipRocker/edit/main/README.md
```

2. Navigate to the directory:
```bash
$ cd NumberOne-ChipRocker/
```

3. Install the required packages:
```bash
$ pip install -r requirements.txt
```

### Manually Requirements

To install all necessary packages, use:
```bash
$ pip install tqdm termcolor
```

## Technical Overview

It orchestrates command-line executions to `rkflashtool`, eallowing for automated data read/writing, efficient data transfers, and multi-part dumping operations.

**Note:** Ensure your device is in LOADER mode for flash I/O operations.

## Usage

To use the ChipRocker Wizard, run the script:
```bash
$ sudo -E python3 chip_rocker_script.py
```

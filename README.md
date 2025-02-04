# Cookie Clicker Automation with Selenium

This Python script automates the **Cookie Clicker** game by 
[Orteil](http://orteil.dashnet.org/experiments/cookie/) using selenium. It simulates gameplay by repeatedly clicking 
the cookie, purchasing upgrades every 5 seconds when affordable, and running for a set period of 30 minutes.

## Features

- Automatically clicks the cookie to generate cookies.
- Checks for and purchases upgrades when affordable.
- Runs for 30 minutes, then outputs the Cookies Per Second (CPS) at the end.

## Requirements

- **Python 3.x** or higher
- **Selenium** library
- **Google Chrome** (for the ChromeDriver)
- **ChromeDriver** (matching your Chrome version)

## Installation

### 1. Install Python

Make sure you have **Python 3.x** installed. You can download it from [python.org](https://www.python.org/downloads/).

### 2. Install Dependencies

Install the required Python packages using `pip`:

```bash
pip install selenium


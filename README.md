# URL Shortener Application

## Overview

The **URL Shortener Application** is a Python Django project that provides users with a simple interface to shorten long URLs, making them easier to share and manage. This application enhances user convenience by allowing for quick access to lengthy web addresses through concise links.

## CI/CD Integration

This project utilizes **Continuous Integration and Continuous Deployment (CI/CD)** practices through **GitHub Actions**.

The configuration file `.github/workflows/jekyll-docker.yml` automates the build process whenever there are pushes or pull requests to the **master branch**.

This workflow ensures that the site is built in a **Docker container** every time you push changes to the master branch or create a pull request.

This automation enhances the **reliability and performance** of the site, allowing for seamless updates and feature implementations.

## Setup Instructions

### 1. Install Python
Ensure Python is installed on your system. Download the latest version from the [official Python website](https://www.python.org/) and follow the installation instructions for your operating system.

### 2. Set Up a Virtual Environment (Recommended)
Creating a virtual environment helps isolate project dependencies. Open a terminal or command prompt, navigate to your project directory, and run the following command:

```bash
python -m venv myenv
```

This will create a new virtual environment named `myenv` in your project directory.

### 3. Activate the Virtual Environment
Activate the virtual environment you created. The process for activation depends on your operating system:

**On Windows:**
```bash
myenv\Scripts\activate
```

**On macOS/Linux:**
```bash
source myenv/bin/activate
```

## Running the Application

To start the application, execute the following command:

```bash
python manage.py runserver
```

The application will now be running, and you can access it via your web browser.


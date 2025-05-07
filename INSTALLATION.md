# Installation Guide for BeeWare Example

This guide will help you set up and run the BeeWare example program on Windows.

## Prerequisites
- Python 3.7 or newer (Python 3.12 recommended)
- pip (Python package manager)

## Steps

1. **Clone or Download the Project**
   - Download or clone the repository to your local machine.

2. **Navigate to the Project Directory**
   ```powershell
   cd .\beeware-example
   ```

3. **(Optional) Create a Virtual Environment**
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate
   ```


4. **Install Dependencies**
   ```powershell
   pip install --upgrade pip
   pip install toga
   pip install -e helloworld
   ```
   This installs Toga and uses the `pyproject.toml` in the `helloworld` directory to install requirements.

5. **Run the Application**
   ```powershell
   python -m helloworld
   ```
   This will launch the BeeWare example app.

## For more help, visit the [BeeWare documentation](https://beeware.org/docs/).

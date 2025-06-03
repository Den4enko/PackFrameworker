# PackFrameworker

PackFrameworker is a script that automates building and updating Minecraft modpacks

- Prompting for configuration (Minecraft version and modloader) on the first run
- Building modpack variants (giga, nano, server) by merging files from multiple directories
- Updating or cloning the PackFramework repository
- Copying the beta build to a release folder
- Quietly checking for required dependencies (Git and Packwiz) in your system's PATH
- Providing a simple, menu-based interface for managing builds and configuration

## Requirements

- **Python 3.8+**

- **Git**

- **Packwiz**

## Installation

1. **Install Python 3.8 or later**  
   Download and install from the [Python website](https://www.python.org/).

2. **Install Git**  
   Follow the instructions on the [Git website](https://git-scm.com/).

3. **Install Packwiz**  
   See the instructions on the [Packwiz GitHub page](https://github.com/packwiz/packwiz) for installation details.

4. **Download PackFrameworker**  
   Clone this repository or download the `packframeworker.py` script into your working directory. Make sure that any necessary folders (such as `beta`, `mod`, etc.) are also present.

## Usage

Run the script from the command line:

```bash
python PackFrameworkerScript.py

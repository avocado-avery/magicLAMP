# Automated LAMP Stack Deployment Script

magicLAMP is a Bash-based automation tool designed to streamline the deployment of LAMP (Linux, Apache, MySQL/MariaDB, PHP) stacks. This script automatically installs required packages, configures web servers, deploys popular Content Management Systems (CMS), and sets up corresponding SQL databases and users. It is ideal for rapid prototyping, testing environments, and ensuring consistent setups across deployments.

## Features

- **OS Detection:**  
  Automatically detects the underlying OS (Ubuntu/Debian or RHEL/CentOS/Fedora) and selects the appropriate package manager.

- **Package Installation:**  
  Installs all required packages such as Apache/httpd, MariaDB/MySQL, PHP, Composer, and additional PHP modules.

- **CMS Deployment:**  
  Downloads and deploys popular CMS releases:
  - PrestaShop
  - osCommerce
  - ZenCart  
  Configures directories, ownership, and permissions based on detected OS.

- **Database Setup:**  
  Automates SQL database creation, user setup, and privileges assignment using an integrated SQL setup script.

- **Automation & Consistency:**  
  Reduces manual setup time and minimizes configuration errors by automating repetitive deployment tasks.


## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/avocado-avery/magicLAMP.git
   cd magicLAMP
   ```
1. **Make The Script Executable:**
 
    ```bash
    chmod +x magicLAMP
    ```
3. 1. **Run The Script:**

    ```bash
    ./magicLAMP --<CMS>
    ```

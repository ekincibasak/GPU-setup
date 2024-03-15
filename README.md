# TensorFlow GPU Setup

This repository contains scripts to set up a Conda environment with TensorFlow GPU support, along with necessary libraries and dependencies.

## Setup Instructions

1. **Clone the Repository**: Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/your-repo.git
- **Execute Initial Setup Script**: Run the `mini.sh` script provided in the repository to set up the initial environment. This script creates a new directory named `work`, copies the Miniconda installation script, and installs Miniconda.

   ```bash
    ./mini.sh

- ** Conda Environment: Activate the Conda environment created by the script using the following command:
   ```bash
    conda activate tf_gpu
....



## Additional Information

- **Environment Variables**: The setup script sets environment variables to update `LD_LIBRARY_PATH` for NVIDIA GPU libraries automatically.
  
- **Conda Deactivation and Activation**: The setup script automatically deactivates the Conda environment after setup and reactivates it before running the test script.
  
- **Troubleshooting**: If you encounter any issues during setup or testing, please refer to the Troubleshooting section below.


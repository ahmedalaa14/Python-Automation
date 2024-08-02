# Python Automation Scripts

- This repository contains a collection of Python scripts for automating various tasks in AWS.

## Contents

- `add-env-tags.py`: Script to add environment tags to AWS resources.
- `cleanup-snapshots.py`: Script to clean up old EBS snapshots.
- `ec2-status-checks.py`: Script to perform status checks on EC2 instances.
- `eks-status-checks.py`: Script to perform status checks on EKS clusters.
- `restore-volume.py`: Script to restore an EBS volume from a snapshot.
- `volume-backups.py`: Script to create backups of EBS volumes.
- `monitor-website.py` : Script to monitor your website.

## Prerequisites

- Python 3.x
- Boto3 library
- AWS credentials configured

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/ahmedalaa14/Python-Automation.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Python-Automation
    ```
3. Install the required dependencies:
    ```sh
    pip install boto3
    ```
4. Run the desired script:
    ```sh
    python script-name.py
    ```

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.

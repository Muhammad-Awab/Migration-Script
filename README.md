# Git Branch Cloner and Pusher

This script automates the process of cloning all branches from a source GitHub repository, checking them out locally, changing the remote URL, and pushing all branches to a new destination repository.

## Prerequisites

- Python 3.x
- Git

## Usage

1. **Clone this repository**

    ```bash
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

2. **Make the script executable**

    ```bash
    chmod +x script.py
    ```

3. **Run the script with the source repository URL and the destination repository URL**

    ```bash
    python script.py <source-repo-url> <destination-repo-url>
    ```

    Replace `<source-repo-url>` with the URL of the repository you want to clone from and `<destination-repo-url>` with the URL of the repository you want to push to.

## Example

To clone all branches from `https://github.com/Priority-Media/react-offer-sites.git` and push them to `https://github.com/your-username/your-new-repo.git`, run:

```bash
python script.py https://github.com/Priority-Media/react-offer-sites.git https://github.com/your-username/your-new-repo.git

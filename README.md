# Project Contribution Guidelines

Welcome to our project! We appreciate your interest in contributing. Please follow these guidelines to get started.

## Cloning the Repository

1. **Clone the Repository:**
   - Start by cloning the repository to your local machine:
     ```bash
     git init
     git remote add origin https://github.com/pandeyaman2170/SDE-Practice2.git
     ```

## Making Changes

2. **Create a Feature Branch:**
   - Create a new branch locally for your changes. Make sure to name it appropriately:
     ```bash
     git pull origin main
     git branch feature-branch
     git checkout feature-branch
     ```
   - This helps in keeping your changes isolated and makes the collaboration process smoother.

3. **Make Changes:**
   - Implement your changes and improvements in the feature branch only.

4. **Commit Your Changes:**
   - Commit your changes to the feature branch:
     ```bash
     git add .
     git commit -m "Your descriptive commit message"
     ```

## Raising a Pull Request

5. **Raise a Pull Request:**
   - Once you are ready to contribute your changes, push the feature branch to the remote repository:
     ```bash
     git push origin feature-branch
     git checkout main
     git merge feature-branch
     git push origin main
     ```
   - Visit the GitHub repository and create a Pull Request from your feature branch.
   - Provide a clear title and description for your Pull Request.
   - Ensure your changes have been tested and are ready for review.

Thank you for contributing to our project! If you have any questions or need assistance, feel free to reach out.

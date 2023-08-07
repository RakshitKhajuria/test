# LangTest Contribution Guide

We welcome contributions from the community to help us achieve our mission of making safe and reliable NLP models a reality. If you're interested in contributing, follow the steps below:

## Getting Started

To start contributing to LangTest, follow these steps:

1. **Finding an Issue**

   - Visit our [Issue Tracker](https://github.com/JohnSnowLabs/langtest.git/issues) to find a list of open issues.
   - Look for issues that align with your skills and interests. Feel free to ask for clarification or more information on any issue.

2. **Fork the Repository**: Click on the "Fork" button on the top-right corner of the [LangTest GitHub repository](https://github.com/JohnSnowLabs/langtest.git) to create a copy of the repository in your GitHub account.

3. **Clone the repository**: Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button, and then click the _copy to clipboard_ icon.

   Open a terminal and run the following git command:

   ```bash
   git clone "url you just copied"
   ```
   where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

4. **Create a branch**: Change to the repository directory on your computer (if you are not already there):

   ```bash
   cd langtest
   ```

   Now create a branch using the `git checkout -b` command:

   ```bash
   git checkout -b your-branch-name
   ```

5. **Set Up Environment**: Create a virtual environment for LangTest using your preferred method. For example, you can use `venv` or `conda`.

6. **Install Poetry**: Poetry is the package manager used for this project. If you don't have Poetry installed, run the following command:

   ```bash
   pip install poetry
   ```

7. **Install Dependencies**: Use Poetry to install the project dependencies:

   ```bash
   poetry install --with dev
   ```

## Contributing to LangTest

Now that your environment is set up, you can start contributing to LangTest. Here are the general steps to follow:

1. **Make your changes**: Implement the desired features, fix bugs, or make improvements to the existing codebase.

2. **Write tests**: Whenever possible, add new tests to cover the changes you've made. This ensures that your code works as expected and helps maintain the project's quality.

3. **Commit your changes**: Once you are satisfied with your changes, commit them with a descriptive commit message.

    ```bash 
        git add .
        git commit -m "Brief description of the changes"
    ```
5. **Push your changes**: Push the changes to your forked repository.
    ```bash 
    git push origin feature-name
    ```

6. **Create a pull request**: Go to the LangTest repository on GitHub and navigate to the "Pull Requests" tab. Click on "New Pull Request" and follow the instructions to create a new pull request from your branch to the main repository.

7. **Description**: Provide a clear and concise description of the changes you've made in the pull request description. Use the format: Fixes # (issue) - Brief description of the changes.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Our team will review your pull request, provide feedback, and work with you to ensure that your contribution meets the project's guidelines and quality standards.

### Additional Resources
- LangTest GitHub Repository: https://github.com/your-username/langtest
- Official LangTest Website: https://langtest.org

If you have any questions or need further assistance, don't hesitate to reach out to us on GitHub or via our official communication channels.

Thank you for contributing to LangTest! Your efforts are greatly appreciated. Happy coding!
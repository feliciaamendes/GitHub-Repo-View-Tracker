# GitHub Repo View Tracker 🚀

![GitHub Repo View Tracker](https://img.shields.io/badge/GitHub-Repo%20View%20Tracker-blue?style=for-the-badge&logo=github)

Welcome to the **GitHub Repo View Tracker**! This automated Python script tracks the number of views on your GitHub repositories. It uses GitHub Actions to run every two days, providing you with up-to-date statistics about your repository's performance.

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [How It Works](#how-it-works)
4. [Setup Instructions](#setup-instructions)
5. [Usage](#usage)
6. [License](#license)
7. [Contributing](#contributing)
8. [Support](#support)
9. [Release Information](#release-information)

## Features

- **Automated Tracking**: The script runs automatically every two days.
- **View Count Difference**: It shows the difference in views between the current and previous runs.
- **Cumulative Counter**: Tracks total views from the first run.
- **Easy Setup**: Simple to configure with a personal access token.

## Getting Started

To get started with the GitHub Repo View Tracker, follow these steps:

1. **Clone the Repository**: Use the command below to clone the repository to your local machine.
   ```bash
   git clone https://github.com/feliciaamendes/GitHub-Repo-View-Tracker.git
   ```

2. **Install Required Libraries**: Make sure you have Python 3 installed. Then, install the required libraries using pip.
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a Personal Access Token**: Go to your GitHub account settings and create a personal access token with the necessary permissions to access your repositories.

4. **Configure the Script**: Edit the configuration file to add your personal access token and specify the repositories you want to track.

## How It Works

The GitHub Repo View Tracker uses the GitHub API to fetch the number of views for your specified repositories. It calculates the difference in views since the last run and updates the cumulative counter. This data is stored in a file for easy reference.

The script runs using GitHub Actions, which allows it to execute automatically every two days. This ensures you always have the latest statistics without manual intervention.

## Setup Instructions

1. **Fork the Repository**: Click on the "Fork" button at the top right of the repository page to create your own copy.

2. **Enable GitHub Actions**: Go to the "Actions" tab in your forked repository and enable GitHub Actions if it is not already enabled.

3. **Add Secrets**: In your repository settings, navigate to "Secrets" and add your personal access token as a new secret. Name it `GITHUB_TOKEN`.

4. **Run the Action**: The action will automatically run based on the schedule defined in the workflow file.

## Usage

After setting up the script, it will run every two days and provide you with the following outputs:

- **Current Views**: The number of views for each tracked repository.
- **Previous Views**: The number of views from the last run.
- **View Difference**: The difference in views since the last run.
- **Total Views**: A cumulative count of all views from the first run.

You can check the output in the "Actions" tab of your repository to see the logs from each run.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request to the main repository.

## Support

If you encounter any issues or have questions, feel free to open an issue in the repository. We appreciate your feedback and will respond as soon as possible.

## Release Information

You can find the latest releases and download the necessary files from the [Releases](https://github.com/feliciaamendes/GitHub-Repo-View-Tracker/releases) section. Make sure to download the latest version to take advantage of new features and fixes.

![Release Badge](https://img.shields.io/badge/Latest%20Release-v1.0.0-green?style=for-the-badge)

## Additional Resources

- [GitHub API Documentation](https://docs.github.com/en/rest)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

Thank you for using the GitHub Repo View Tracker! We hope it helps you keep track of your repository views effectively.
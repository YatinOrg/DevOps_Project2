

######################################################################
# About: Listing users with read access to a GitHub repository
# Input: GitHub username and token of the person executing the script
# Owner: Yatindra Pabbati
# Date of Creation: 20 - 01 -2024
# Last Date of Edit: 21 - 01 -2024
# Modification: Helper function and metadata added
# Contact for Issues: YatindraPabbati (GitHub)
######################################################################

# Helpme Doc
#
# Description:
#   This script lists users with read access to a specified GitHub repository. It requires
#   authentication through a GitHub username and personal access token.
#
# Usage:
#   ./script.sh <GitHub_username> <GitHub_token> <repository_owner> <repository_name>
#
# Arguments:
#   <GitHub_username>     Your GitHub username.
#   <GitHub_token>        Your GitHub personal access token.
#   <repository_owner>    Owner of the GitHub repository.
#   <repository_name>     Name of the GitHub repository.
#
# Example:
#   ./script.sh john_doe abcdef123 owner_repo sample_repo
#
# Installation:
#   1. Clone the repository: git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
#   2. Navigate to the script directory: cd YOUR_REPO
#   3. Make the script executable: chmod +x script.sh
#
# Note:
#   - The GitHub personal access token should have sufficient permissions to access the repository.
#   - Replace placeholders with your actual GitHub credentials and repository details.
#   - For any issues or questions, open an issue on GitHub or contact YatindraPabbati.
#
# Important:
#   The script will exit with an error message if the correct number of arguments is not provided.
#   Make sure to execute the script with the expected command-line arguments.
#   Example: ./script.sh arg1 arg2
#
# License:
#   This script is licensed under the MIT License - see the LICENSE file for details.
#
# Enjoy using the script!
######################################################################

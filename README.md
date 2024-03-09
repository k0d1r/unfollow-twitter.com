# Twitter Unfollow Script

This script, `unfollowScript.js`, automates the process of unfollowing users on Twitter. Written in JavaScript, it's designed to be run directly in the console of a web browser while you're logged into your Twitter account. It's a handy tool for managing your follow list more efficiently, but it must be used responsibly and within the constraints of Twitter's terms of service to avoid potential account limitations or bans.

## Important Notice

Before using this script, please be aware that automated actions can sometimes violate Twitter's terms of service. Excessive use of such scripts might lead to temporary suspension or permanent banning of your account. Use this script at your own risk, and always ensure you're not violating Twitter's automation rules.

## Setup

No installation is required for this script. You will need:
- A modern web browser.
- Access to your Twitter account via the web interface.

## Usage

1. Log into your Twitter account through your web browser.
2. Navigate to your profile or the list of people you're following.
3. Open your browser's Developer Tools (usually accessible by pressing `F12` or right-clicking the page and selecting "Inspect").
4. Go to the Console tab.
5. Copy and paste the contents of `unfollowScript.js` into the console and press Enter to run the script.

## How It Works

The script selects all unfollow buttons on the page using a specific selector (`'[data-testid$="-unfollow"]'`) and clicks each button to unfollow the corresponding user. It includes mechanisms to scroll through the page and handle batches of unfollow actions to avoid triggering Twitter's rate limits.

## Frequently Asked Questions

- **Should I run the script multiple times?**
  - Depending on the number of users you're following, you may need to run the script multiple times. The script includes a scrolling function to load new users, but Twitter's dynamic content loading might require multiple iterations to unfollow everyone.

- **Can using this script get me banned from Twitter?**
  - While this script mimics manual unfollow actions, excessive use can raise flags on automated behavior. Use the script sparingly and responsibly to minimize the risk of account penalties.

## License

This script is released under the MIT License. For more details, see the `LICENSE` file in this repository.

## Contributing

If you'd like to contribute to the project, whether through feature enhancements, bug fixes, or improvements, please feel free to submit a pull request or open an issue to discuss your ideas.

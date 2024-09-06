# Instagram Follower/Following Checker Script

This script helps you fetch and analyze the list of followers and accounts you follow on Instagram. It compares the two lists and identifies users who:
1. You follow but don't follow you back.
2. Follow you but you don't follow back.

## Prerequisites

- **Instagram Account**: You need to be logged into your Instagram account for this script to work.
- **Browser with Developer Console**: This script runs in the browser's developer console, so you’ll need to be on Instagram's website and use the console to execute it.

## Installation

No installation is required. Simply follow these steps to use the script.

## How to Use

### 1. Open Instagram
- Go to the Instagram website: https://www.instagram.com
- Ensure you are logged in to your account.

### 2. Open Developer Console
- Right-click on the Instagram webpage and click "Inspect".
- In the window that appears, click on the "Console" tab.

### 3. Run the Script
- Copy the entire script from this repository.
- Paste it into the console.

### 4. Edit Username
- Replace `"example_username"` in the script with your actual Instagram username.

```js
username = "your_instagram_username";
```

### 5. Execute the Script
- Press Enter to run the script in the console.
- The script will fetch your followers and following lists and display the following results:
  - Users who follow you, but you don't follow them back.
  - Users you follow, but they don't follow you back.

### 6. Review Results
- The script will output the results in the console, showing both lists for your review.

## Features

- Fetches all followers and following lists, including pagination.
- Random delays between API calls to avoid rate-limiting.
- Compares followers and following lists.
- Identifies users who don't follow back and vice versa.

## Limitations

- This script must be run from the Instagram website due to cross-origin policies.
- It can take time to fetch large lists due to Instagram’s rate-limiting.

## License

This project is licensed under the MIT License.

--- 

You can copy and paste this directly into a text editor or a README file.

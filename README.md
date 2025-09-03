# GitLab Review Automove After Viewing A File

This user script automatically moves to the next file after you have viewed a file in review in single file mode. This allows you to lazily keep your finger on the 'v' button to mark a file as viewed and move to the next file.

## Features

- Be extra lazy
- Mark the current file as viewed and automatically move to the next file in one buttonpress. 
- Lightweight and fast — no external dependencies.
- Runs **only** on Merge Request detail pages.

## Installation & Usage

1. **Install Tampermonkey**
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/tampermonkey/)
   - [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)

2. **Download the Script**
   - Open [script.js](./script.js) in your browser.

3. **Install in Tampermonkey**
   - Click the **Raw** button in GitHub to view the plain script.
   - Tampermonkey will detect it and prompt you to install.
   - Click **Install**.

4. **Done!**
   - Visit any Merge Request detail page in GitLab and try to click the Merge button — you should get a confirmation prompt.
  
## Contributing

I welcome contributions!  
You can help in the following ways:

- **Report Issues** — Found a bug? Please [open an issue](https://github.com/rvoortman/gitlab-review-automove-after-viewn/issues).
- **Suggest Features** — Have an idea to improve the script? [Share it here](https://github.com/rvoortman/gitlab-review-automove-after-view/issues).
- **Translations** — Want to add prompts in your language? Submit a pull request!
- **Code Improvements** — Optimize performance, improve detection logic or any other thing you want to improve. 

## Development

1. Fork the repository.
2. Make your changes in `script.js`.
3. Test locally by installing the modified script in Tampermonkey.
4. Submit a pull request.

## License

This project is licensed under the [MIT License](./LICENSE).

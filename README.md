# Web Development Contract
This is the boilerplate I use for web development contracts.

Feel free to use it in your own work, contribute to the discussion by bringing up issues.

Originally created by [Eric Andrew Lewis](https://github.com/ericandrewlewis/web-development-contract), then expanded to match terminology and needs for myself and added an SOW.

## Converting to PDF
There are two ways to make these documents useful for us (besides being so easy to create thanks to Markdown!).

### GitPrint
There is a cool service called "Git Print". You can take the URL of any Markdown file in GitHub and display a PDF ready page in your web browser! Only down side is your finished contract needs to be in GitHub.

E.G. - [https://gitprint.com/colegeissinger/web-development-contract/blob/master/contract.md](https://gitprint.com/colegeissinger/web-development-contract/blob/master/contract.md)

### Grip
[Grip](https://github.com/joeyespo/grip) is my tool of choice to get PDF renderings of my customized Markdown files without needing to commit them to GitHub.

Grip runs on Python so you'll need to make sure you install [PIP](http://pip.readthedocs.org/en/stable/installing/).

**Mac**: `sudo easy_install pip`

**Windows**: [Needs verification!](http://docs.python-guide.org/en/latest/starting/install/win/)

Now install Grip and then run grip where your files are located.

```bash
$ sudo pip install grip
$ grip
```

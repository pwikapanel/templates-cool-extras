*Updated 6 November, 2023*

![Svija: SVG-based websites built in Adobe Illustrator](http://files.svija.love/github/readme-logo.png?2 "Svija: SVG-based websites built in Adobe Illustrator")


### templates-cool-extras

To install, we will set aside the existing templates, then sym-link this repo to the correct location.

Rename the previous folders. If renaming fails because this operation has already been done, the folders will be deleted:
```
sudo printf "here we go\n"
sudo mv /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates-Prev
sudo rm -rf /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
sudo rm -rf /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates
```
Symlink the new folder:
```
repo="Library/Mobile Documents/com~apple~CloudDocs/Repositories/templates-cool-extras"
# 27 - 2023
sudo mv /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates-Prev
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
# 28 - 2024
sudo mv /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates-Prev
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates
```

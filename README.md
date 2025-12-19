
*Updated 19 December, 2025*

![Pwika: SVG-based websites built in Adobe Illustrator](http://files.pwika.com/github/github_banner.png "Pwika: SVG-based websites built in Adobe Illustrator")


### templates-cool-extras

To install, we will set aside the existing templates, then sym-link this repo to the correct location.

Rename the previous folders. If renaming fails because this operation has already been done, the folders will be deleted:
```
sudo ls
```
```
sudo mv /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates-Prev
sudo rm -rf /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
sudo rm -rf /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates
```
Symlink the new folder:
```
repo="Library/Mobile Documents/com~apple~CloudDocs/Repositories/templates-cool-extras"
sudo ln -s ~/"$repo" /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
sudo ln -s ~/"$repo" /Applications/Adobe\ Illustrator\ 2024/Cool\ Extras.localized/en_US/Templates
```

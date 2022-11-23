*Updated 6 April, 2021*

![Svija: SVG-based websites built in Adobe Illustrator](http://files.svija.love/github/readme-logo.png?2 "Svija: SVG-based websites built in Adobe Illustrator")


### templates-cool-extras

To install, we will set aside the existing templates, then sym-link this repo to the correct location.

Rename the previous scripts folder:
```
sudo mv /Applications/Adobe\ Illustrator\ 2020/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2020/Cool\ Extras.localized/en_US/Templates-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2021/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2021/Cool\ Extras.localized/en_US/Templates-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2022/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2022/Cool\ Extras.localized/en_US/Templates-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates-Prev

```
Then link this repo to Illustrator installations:
```
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2020/Cool\ Extras.localized/en_US/Templates
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2021/Cool\ Extras.localized/en_US/Templates
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2022/Cool\ Extras.localized/en_US/Templates
sudo ln -s /Users/Main/Documents/templates-cool-extras /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
```


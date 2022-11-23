*Updated 6 April, 2021*

![Svija: SVG-based websites built in Adobe Illustrator](http://files.svija.love/github/readme-logo.png?2 "Svija: SVG-based websites built in Adobe Illustrator")


### templates-cool-extras
Rename the previous scripts folder:
```
sudo mv /Applications/Adobe\ Illustrator\ 2020/Presets.localized/en_US/Scripts /Applications/Adobe\ Illustrator\ 2020/Presets.localized/en_US/Scripts-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2021/Presets.localized/en_US/Scripts /Applications/Adobe\ Illustrator\ 2021/Presets.localized/en_US/Scripts-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2022/Presets.localized/en_US/Scripts /Applications/Adobe\ Illustrator\ 2022/Presets.localized/en_US/Scripts-Prev
sudo mv /Applications/Adobe\ Illustrator\ 2023/Presets.localized/en_US/Scripts /Applications/Adobe\ Illustrator\ 2023/Presets.localized/en_US/Scripts-Prev

```
Then link this repo to Illustrator installations:
```
sudo ln -s /Users/Main/Documents/scripts-presets /Applications/Adobe\ Illustrator\ 2020/Presets.localized/en_US/Scripts
sudo ln -s /Users/Main/Documents/scripts-presets /Applications/Adobe\ Illustrator\ 2021/Presets.localized/en_US/Scripts
sudo ln -s /Users/Main/Documents/scripts-presets /Applications/Adobe\ Illustrator\ 2022/Presets.localized/en_US/Scripts
sudo ln -s /Users/Main/Documents/scripts-presets /Applications/Adobe\ Illustrator\ 2023/Presets.localized/en_US/Scripts
```

---
*to install*

sudo ln -s /Users/Main/Documents/templates-cool-extras/ /Applications/Adobe\ Illustrator\ 2023/Cool\ Extras.localized/en_US/Templates
sudo ln -s /Users/Main/Documents/templates-cool-extras/ /Applications/Adobe\ Illustrator\ 2022/Cool\ Extras.localized/en_US/Templates

**IMPORTANT NOTE:** the actual scripts are developed in a separate repository called [Presets-Scripts](https://github.com/svijasvg/Presets-Scripts).

This is because scripts stored in:

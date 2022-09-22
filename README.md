# Sublime-text config

## Packages Installeds 📦

- Darkula Color Scheme

- A File Icon

- Dracula Color Scheme

- Git

- Git blame

- Git Extensions

- GitGutter

- Gitmoji

- LikeGit

- Material Theme

- Monokai Dark

- OmnisStudioHighlighter

- Package Control

- Terminal
- Terminus

## Other Packages

Sublimemerge [HERE](https://www.sublimemerge.com/docs/linux_repositories) (Like GitGraph from VsCode but better 😎)

If ur using Ubuntu just copy and paste these commands in ur terminal 👍

```bash
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```

```bash
sudo apt-get install apt-transport-https
```

```bash
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

```bash
sudo apt-get update
sudo apt-get install sublime-merge
```

## Setting (JSON) 🔪 😱

```json
// Settings in here override those in "Default/Preferences.sublime-settings",
// and are overridden in turn by syntax-specific settings.
{
	
	"ignored_packages":
	[
		"Vintage",
	],
	"color_scheme": "Packages/Dracula Color Scheme/Dracula.tmTheme",
	"font_face": "JetBrains Mono", // need install JetBrains Mono font
	"font_options":[
		//these under are for font ligatures
		//idk which really enable
		"gray_antialias",
		"dlig",
		"liga", 
		"clig", 
		"calt",
		"dlig",
		
		//i like bold
		"bold"
	],
	"theme": "auto",
}
```

To install the JetBrains Mono font click [HERE](https://www.jetbrains.com/pt-br/lp/mono/#how-to-install).

## How to use my settings

```bash
git clone https://github.com/mateusribeiroo/sublime-text-config.git
```

Then extract it and move them to ~/.config/sublime-text/User/ and replace the file there

Maybe in your file system the path is  ~/.config/sublime-text3/User/ but who cares

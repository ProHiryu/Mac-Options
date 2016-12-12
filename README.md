# Mac-Options

Record some Mac options

---

_just record in case of something_

# App Store

- wechat
- QQ
- battery monitor
- movist
- xcode - command line tools
- evernote
- you-daodict
- NetEase Music

# Flashlight

[Flashlight](https://github.com/w0lfschild/Flashlight "the new version for Mac OS Sierra") The new version is not well compatible for the system, hope someday the spotlight can be hacked on Mac OS

[Flashlight](https://github.com/nate-parrott/Flashlight "the old version for OS X") The old version only works on OS X

<!-- more -->

# Google Chrome

[Chrome](https://www.google.com/chrome/browser/desktop/index.html "chrme") If you dont need the plugins for chrome, i really recommend you to laern to use the safari, it's much well compatible for Mac

**There is one single problem for chrome is the new tags' search engine**

Solution: settings -> monitor search enging -> scoll it down -> add a search engine named 'google' -> set it to the default one

**the url of the search engine is :<https://www.google.com/search?hl=zh-CN&q=%s>**

Do not forget to get [vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)

## iTerm2

- [Download](http://www.iterm2.com/downloads.html) and install iTerm2 (it has better color fidelity than the built in Terminal).

Get the iTerm color settings

- [Solarized Dark theme](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors)
- [Solarized Light theme](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Light.itermcolors)
- [More themes @ iterm2colorschemes](http://iterm2colorschemes.com/)

Just save it somewhere and open the file(s). The color settings will be imported into iTerm2\. Apply them in iTerm through iTerm -> preferences -> profiles -> colors -> load presets. You can create a different profile other than `Default` if you wish to do so.

# Oh My Zsh

More info here: <https://github.com/robbyrussell/oh-my-zsh>

## Install with curl

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

When the installation is done, edit `~/.zshrc` and set `ZSH_THEME="agnoster"`

## Install a patched font

- [Meslo](https://github.com/Lokaltog/powerline-fonts/blob/master/Meslo/Meslo%20LG%20M%20DZ%20Regular%20for%20Powerline.otf) (the one in the screenshot). Click "view raw" to download the font.
- [Others @ powerline fonts](https://github.com/powerline/fonts)

Open the downloaded font and press "Install Font".

Set this font in iTerm2 (14px is my personal preference) (iTerm -> Preferences -> Profiles -> Text -> Change Font).

Restart iTerm2 for all changes to take effect.

# Further tweaking

Things like

- auto suggestions
- word jumping with arrow keys
- shorter prompt style
- syntax highlighting

can be found in the section below.

## Auto suggestions (for Oh My Zsh)

![Auto suggestions](http://i66.tinypic.com/b5i9dv.png)

Just follow these steps: <https://github.com/tarruda/zsh-autosuggestions#oh-my-zsh>

If the auto suggestions do not appear to show, it could be a problem with your color scheme. Under "iTerm -> Preferences -> Colors tab", check the value of Black Bright, that is the color your auto suggestions will have. It will be displayed on top of the Background color, so if there is not enough contrast between the two, you won't see the suggestions, even if they're actually there.. For Solarized Dark I changed the value of Black Bright to "586e75".

## Shorter prompt style

By default, your prompt will now show "user@hostname" in the prompt. This will make your prompt rather bloated. Optionally set `DEFAULT_USER` in `~/.zshrc` to your regular username (these must match) to hide the "user@hostname" info when you're logged in as yourself on your local machine. You can get your exact username value by executing `whoami` in the terminal.

## Syntax highlighting

```
brew install zsh-syntax-highlighting
```

If you do not have or do not like homebrew, follow [the installation instructions](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md) instead.

After installation through homebrew, add

```
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

to **the end** of your `.zshrc` file. After that, it's best to restart your terminal. Sourcing your `~/.zshrc` does not seem to work well with this plugin.

# Wall Paper

[desktoppr](https://www.desktoppr.co) A website for mac wall paper really good

[Dropbox](https://www.dropbox.com) U need dropbox to download the papers

# Safari

[vimari](https://github.com/guyht/vimari/tree/59723be011a8d2d20e3e615db31f53ca076c01ac) A plugin for safari like vimium for chrome

# Atom

**Website:** [atom.io](https://atom.io)

## Some Articles

- [How to evaluate Atom](http://www.zhihu.com/question/22867204)
- [Why we choose Atom](http://atom-china.org/t/atom/59)
- [Atom basic usage](http://atom-china.org/t/guan-fang-shou-ce-atom-ji-chu-shi-yong/62)

# ShortCut key

- `cmd-\` hide or show index tree
- `ctrl-0` concentrate on index tree
- `fn-F2` change the file name in index tree
- `ctrl-shift-M` Markdown Preview
- `ctrl-alt-b` [atom-beautify](https://atom.io/packages/atom-beautify) format your code
- ``ctrl-` `` [terminal-panel](https://atom.io/packages/terminal-panel) call for CLI
- `ctrl-shift-U` change encoding
- `cmd-t`或`cmd-p` search files

more shortcut just go to settings ![](https://raw.githubusercontent.com/nieweidong/learn-atom/master/img/keybindings.png)

## Packages

- [activate-power-mode](https://atom.io/packages/activate-power-mode)
- [linter](https://atom.io/packages/linter)+[linter-eslint](https://atom.io/packages/linter-eslint)
- [autocomplete-paths](https://atom.io/packages/autocomplete-paths)
- [pigments](https://atom.io/packages/pigments)
- [color-picker](https://atom.io/packages/color-picker)
- [docblockr](https://atom.io/packages/docblockr)
- [emmet](https://atom.io/packages/emmet) [Emmet usage](http://www.w3cplus.com/tools/emmet-cheat-sheet.html)
- [file-icons](https://atom.io/packages/file-icons)
- [csscomb](https://atom.io/packages/atom-csscomb)
- [git-plus](https://atom.io/packages/git-plus)
- [git-time-machine](https://atom.io/packages/git-time-machine)
- [javascript-snippets](https://atom.io/packages/javascript-snippets)
- [atom-beautify](https://atom.io/packages/atom-beautify)
- [esformatter](https://atom.io/packages/esformatter)
- [Minimap](https://atom.io/packages/minimap)

# Microsoft Ofiice & PhotoShop

- [Microsoft Office mac for free](https://drive.google.com/open?id=0BxAvhRqTkT2-bFBWUUVDdWRiZDA)
- [PhotoShop mac for free](https://mega.nz/#!qkVAlByY!PXEFYrCY9YF44c_xX_cAGjG_ykPFn9ln0KI26QLiSEw)

# Python

- `sudo easy_install pip`
- [Python 3.5.2](https://www.python.org)
- `pip3 install xxxxx`

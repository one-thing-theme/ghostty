# Ghostty (One Thing Theme)

_Modern, minimal & simple visual studio code theme that combine black, white and gray colors_

_Screenshots:_

![Banner](https://cdn.hashnode.com/res/hashnode/image/upload/v1746717532966/94c91d15-2b3d-4f1e-b854-a9b0f09f181a.png)

## Recomended settings

If you want to use this theme with all of the features and simplicity, you can start tweak the settings by following the [official guide](https://onethingtheme.vercel.app/docs)

## Installation

To install the theme for oh my posh, you can follow the step below.

1. Go to the ghostty configurations. used to be `~/.config/ghostty`

2. Create the themes folder inside them,

```
mkdir themes
cd themes
```

3. Download the one thing themes for oh my posh.

```
curl -O https://raw.githubusercontent.com/one-thing-theme/oh-my-posh/refs/heads/main/theme/one-thing.omp.json one-thing.omp.json
```

4. Update the oh my posh config to use the theme. Inside the .zshrc file update the settings using.

```
# ZSH CONFIGURATION
# Oh My Posh configuration
if [ "$TERM_PROGRAM" != "Apple_Terminal" ]; then
  eval "$(oh-my-posh init zsh --config ~/.config/oh-my-posh/themes/one-thing.omp.json)"
fi

```

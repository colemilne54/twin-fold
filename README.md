# Twin Fold

### Hides the verbosity of Tailwind classes while still keeping your custom classes visible

![twin fold gif](https://raw.githubusercontent.com/colemilne54/twin-fold/1aa5c57e6bbd8b1434c200f7769c98f6c9c2c185/src/assets/twin-fold.gif)

This repo contains starter code for React using Vite to demonstrate how Twin Fold is implemented.

## Getting Started:

1. Install VSCode Inline Fold

[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=moalamri.inline-fold) - [GitHub Repo](https://github.com/moalamri/vscode-inline-fold)

2. Install [twin.macro](https://github.com/ben-rogerson/twin.macro):

```
> npm i twin.macro
```

2.1 Import to Twin:
```
import 'twin.macro'
```

3. Update twinFold.regex setting to the following:

```
{
    "inlineFold.regex": "(tw)=(({(`|))|(['\"`]))(.*?)(\\2|(\\4)})"
}
```

4. Add Tailwind classes to your JSX/TSX code using the following:

```
<h1 tw="text-sm"...
```

5. (Optional) Tweak additional VSCode Inline Fold settings to suit your preferences.

6. Enjoy folded Tailwind classes while maintaining visibility of your own classes!

# 🚀 Regularize.scss   

Regularize.scss is a SCSS reset stylesheet that eliminates inconsistent browser defaults while preserving essential usability and accessibility features. It ensures a predictable, standardized styling baseline across all modern browsers. Say goodbye to unpredictable layouts and inconsistent form behaviors — Regularize.scss provides a solid foundation for any project.

## 🎯 Why Regularize.scss?

- 🔥 Kills default browser styles – No more surprises!
- 📦 Box-sizing: border-box – Because math should be easy.
- 🎨 Maintains accessibility – Focus outlines? Kept.
- 🌍 Responsive images – No more oversized chaos.
- 🎭 Form control sanity – Inputs behave like they should.
- 🛠️ Fixes browser weirdness – Safari, Firefox, Chrome? We got you.
- ⏩ Built with the almighty SCSS - Syntactically Awesome Style Sheets.

## 📦 Installation  

**NPM Install**
```sh
npm install regularize.scss
```
**SCSS Import**
```css
@import 'regularize.scss/regularize.css';
```
**Compiled CSS**
```html
<link rel="stylesheet" href="path/to/regularize.css">
```

## 🚀 How to use
Just slap Regularize.scss at the top of your main stylesheet, and boom 💥 – your styles are now on solid ground.


## ⚠️ Older Versions
Older versions of Regularize.scss are available as branches in the repository for reference or for rolling back. However, these versions are **no longer maintained** and may not include the latest improvements, bug fixes, or best practices. Use them with caution.

## 📚 References
Regularize.scss has been built from the ground up with the help of:
- [Normalize.css](https://github.com/necolas/normalize.css) by Nicolas Gallagher
- [The New CSS Reset](https://github.com/elad2412/the-new-css-reset) by Elad Shechter

## 📜 License

Licensed under the MIT License – use it, tweak it, share it! 💖

## 🌎 Browser Compatibility

| Feature                        | Chrome | Firefox | Safari | Edge | Opera | Brave | IE 11 |
|--------------------------------|--------|---------|--------|------|-------|-------|-------|
| Reset all styles (except display) | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ⚠️ Partial* |
| Box-sizing: border-box         | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ⚠️ Partial* |
| Text size adjustment fix       | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| List styles removed            | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ⚠️ Partial* |
| Images max-size fix            | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ⚠️ Partial* |
| Table border-collapse          | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ✅      |
| Form input user-select fix     | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Focus-visible outline          | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Placeholder color reset        | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Hidden attribute fix           | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Contenteditable improvements   | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Draggable fix                  | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |
| Modal (dialog:modal) reset     | ✅      | ✅       | ✅      | ✅    | ✅     | ✅     | ❌       |

**Legend:**  
✅ Fully Supported | ⚠️ Partial Support (some quirks in older versions) | ❌ Not Supported

**Notes:**
- *IE 11 lacks support for `display: revert`, `:focus-visible`, `all: unset`, and some other modern CSS properties.
- Older versions of Safari (pre-12) may have inconsistencies with `text-size-adjust`.
- Brave, Edge, and Opera are Chromium-based, so they behave similarly to Chrome.


___

Go forth and build beautifully consistent websites! 🎨✨

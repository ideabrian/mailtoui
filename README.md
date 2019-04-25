<p align="center">
    <a href="https://mailtoui.com">
       <img src="https://mailtoui.com/assets/img/heading.jpg" alt="MailtoUI">
    </a>
</p>

<p align="center">A simple way to enhance your mailto links with a convenient user interface.</p>

<p align="center">
	<a href="https://github.com/mariordev/mailtoui/releases"><img src="https://img.shields.io/npm/v/mailtoui.svg" alt="Latest release"></a>
	<a href="https://www.npmjs.com/package/mailtoui"><img src="https://img.shields.io/npm/dt/mailtoui.svg" alt="Total downloads"></a>
	<a href="https://github.com/mariordev/mailtoui/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mariordev/mailtoui.svg" alt="License"></a>
	<a href="https://twitter.com/intent/tweet?text=Check%20this%20out!%20&url=https%3A%2F%2Fmailtoui.com"><img src="https://img.shields.io/twitter/url/https/mailtoui.com.svg?style=social" alt="Share on Twitter"></a>
</p>

## Introduction

With MailtoUI, you save time by not setting up "Contact Us" form.

Turn mailto links into a convenient user interface. 

MailtoUI is a JavaScript library.  

A plain mailto link will open your default mail application. 
MailtoUI provides a choice. Compose a new message using a browser-based email client <strong><i>or</i></strong> a default email app.


## Quick Setup

### STEP 1

Add MailtoUI via CDN to the bottom of your page, just before the closing `</body>` tag. 

IMPORTANT: Be sure to replace `[version]` with the latest version number.

```html
<body>
    ...
    ...
    <script src="https://cdn.jsdelivr.net/npm/mariordev/mailtoui@[version]/dist/mailtoui-min.js"></script>
</body>
```

### STEP 2

Attach your mailto link to MailtoUI by adding the class `mailtoui` to the `<a>` tag.

```html
<a class="mailtoui" href="mailto:tony.stark@example.com">Contact Tony</a>
```

That's it! Your mailto link is now using MailtoUI. Refresh your page and try it out.


## Documentation

For full documentation, visit [mailtoui.com][1].

## Contributing

If you're interested in contributing to MailtoUI, please follow the directions in the [contributing docs][2] **before working on a pull request**.

## License

[MIT][3]

[1]:	https://mailtoui.com
[2]:	https://github.com/mariordev/mailtoui/blob/master/.github/CONTRIBUTING.md
[3]:	https://github.com/mariordev/mailtoui/blob/master/LICENSE
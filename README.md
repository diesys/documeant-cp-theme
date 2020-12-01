# documeant-cp-theme
A user-friendly, beautiful and modern theme for [CryptPad](https://github.com/xwiki-labs/cryptpad): some CSS and images/icons, **still under development**.
*Doc*uments as *U* *meant* them to be.

![theme showcase](https://raw.githubusercontent.com/diesys/documeant-cp-theme/master/img/documeant-theme.png)

### Prerequisites
 * CryptPad [installation guide](https://github.com/xwiki-labs/cryptpad/wiki/Installation-guide)

### Screenshots
![showcase](https://raw.githubusercontent.com/diesys/documeant-cp-theme/master/img/screens/screens.gif)

### Enabling the theme
Since CryptPad hasn't a *normal* way of including custom themes and I wasn't able properly fork the CryptPad repository with my customizations the fastest way to use the theme is to **inject CSS** via a web browser extension. Hoping to fix this in the near future.

Here are some examples:
 * [Chromium/Chrome/Brave extension](https://chrome.google.com/webstore/detail/super-css-inject/pcfpmmmjdgngeidaggcahhoncahmpiin)
 * [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/customcss-injector/)
 * [Opera extension](https://addons.opera.com/en/extensions/details/custom-style-script/)
 * [Safari guide](https://developer.apple.com/documentation/safariservices/safari_app_extensions/injecting_css_style_sheets_into_a_webpage)

CSS to include:
 * [documeant.css](https://raw.githubusercontent.com/diesys/documeant-cp-theme/master/documeant.css)
 * [documeant-dark-theme.css](https://raw.githubusercontent.com/diesys/documeant-cp-theme/master/documeant-dark-theme.css) (optional)

The dark theme just replaces the background color of the lightest (white) part of the page. Must include `documeant-dark-theme.css` **AFTER** the main `documeant.css`.

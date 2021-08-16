# favicon-rocketacademy
favicon set and starter code for RA favicons

https://stackoverflow.com/questions/48956465/favicon-standard-2021-svg-ico-png-and-dimensions

https://realfavicongenerator.net/

# Instructions
Copy the following HTML code into the `head` tag of the page.

Copy the xml and manifest files into the *root* of the page / site: [browserconfig.xml](https://github.com/rocketacademy/favicon-rocketacademy/blob/main/assets/browserconfig.xml) [site.webmanifest](https://github.com/rocketacademy/favicon-rocketacademy/blob/main/assets/site.webmanifest)

Copy the following CDN links into the head:
```html
<link rel="apple-touch-icon" sizes="180x180" href="https://ra-web-files.s3.ap-southeast-1.amazonaws.com/all/favicons/apple-touch-icon.png?v=2">
<link rel="icon" type="image/png" sizes="32x32" href="https://ra-web-files.s3.ap-southeast-1.amazonaws.com/all/favicons/favicon-32x32.png?v=2">
<link rel="icon" type="image/png" sizes="16x16" href="https://ra-web-files.s3.ap-southeast-1.amazonaws.com/all/favicons/favicon-16x16.png?v=2">
<link rel="manifest" href="/site.webmanifest?v=2">
<link rel="mask-icon" href="https://ra-web-files.s3.ap-southeast-1.amazonaws.com/all/favicons/safari-pinned-tab.svg?v=2" color="#e73c3e">
<link rel="shortcut icon" href="https://ra-web-files.s3.ap-southeast-1.amazonaws.com/all/favicons/favicon.ico?v=2">
<meta name="apple-mobile-web-app-title" content="Rocket Academy">
<meta name="application-name" content="Rocket Academy">
<meta name="msapplication-TileColor" content="#2b5797">
<meta name="theme-color" content="#ffffff">
```

#### Warning, since the files are not actually placed at the root of the actual page, IE6 might have errors 🙄.

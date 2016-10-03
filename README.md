# Progressive Web App Template
[Progressive Web Apps](https://developers.google.com/web/progressive-web-apps) are experiences that combine the best of the web and the best of apps. They are useful to users from the very first visit in a browser tab, no install required. As the user progressively builds a relationship with the app over time, it becomes more and more powerful. It loads quickly, even on flaky networks, sends relevant push notifications, has an icon on the home screen, and loads as a top-level, full screen experience.

### Service Workers
Features provided via service workers should be considered a progressive enhancement, and added only if supported by the browser.

For example, with [service workers](https://developers.google.com/web/fundamentals/primers/service-worker/) you can cache the app shell and data for your app, so that it's available even when the network isn't. When service workers aren't supported, the offline code isn't called, and the user gets a basic experience. Using feature detection to provide progressive enhancement has little overhead and it won't break in older browsers that don't support that feature.



### What is a Progressive Web App?
A Progressive Web App is:

**Progressive** - Works for every user, regardless of browser choice because it's built with progressive enhancement as a core tenet.

**Responsive** - Fits any form factor: desktop, mobile, tablet, or whatever is next.

**Connectivity independent** - Enhanced with service workers to work offline or on low-quality networks.

**App-like** - Feels like an app to the user with app-style interactions and navigation because it's built on the app shell model.

**Fresh** - Always up-to-date thanks to the service worker update process.

**Safe** - Served via HTTPS to prevent snooping and to ensure content hasn't been tampered with.

**Discoverable** - Is identifiable as an "application" thanks to W3C manifest and service worker registration scope, allowing search engines to find it.

**Re-engageable** - Makes re-engagement easy through features like push notifications.
Installable - Allows users to "keep" apps they find most useful on their home screen without the hassle of an app store.

**Linkable** - Easily share via URL, does not require complex installation

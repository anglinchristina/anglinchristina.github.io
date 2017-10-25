---
layout: post
title:      "Progressive Web Apps"
date:       2017-10-23 18:11:33 -0400
permalink:  progressive_web_apps
---

Post inspired by [Patrick Riley's](https://twitter.com/priley86) & [Tara Manicsic's](https://twitter.com/tzmanics?lang=en) sessions at

[![](https://www.exitevent.com/wp-content/uploads/2017/08/All-Things-Open-logo-red-300x168.png)](https://allthingsopen.org/)

__________________

Progressive web apps (PWAs) combine native mobile UX with web functionality.

Native, offline features like push notifications & cached content are made possible by [service workers](https://developers.google.com/web/fundamentals/primers/service-workers/), JavaScript files that act as a proxy between your web app and servers.  
* Service workers check if they're supported before running and won't crash your web app on non-supported browsers.

You can edit the app's manifest.json file to display:standalone so that your content will be full screen and not displayed within the browser.  

Toolsets:
* The [Kendo UI library](https://www.telerik.com/kendo-ui-b?utm_expid=.QZlGnZzwQVuthJ0mrhuF3A.1&utm_referrer=https%3A%2F%2Fwww.google.com%2F) has native components to style your app faster.
* [Workbox](https://developers.google.com/web/tools/workbox/) generates service workers for you

Demos:
* [Patrick's slides](https://rawgit.com/priley86/ato-2017/master/demo/index.html#0) aren't yet up - will update
* [React Storybook demo](https://github.com/priley86/storybook-react-demo)
* [Angular Storybook demo](https://github.com/priley86/storybook-angular-demo)

[Promises](https://developers.google.com/web/fundamentals/primers/promises) was mentioned a lot in today's sessions, so look out for a separate blog post on that!

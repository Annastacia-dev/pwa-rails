# Building a Progressive Web App (PWA) with Rails

## What are Progressive Web Apps?

A progressive web app (PWA) is an app that's built using web platform technologies, but that provides a user experience like that of a platform-specific app. Definition by [mdn web docs](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/What_is_a_progressive_web_app).

As defined by [web.dev](https://web.dev/articles/what-are-pwas) they are built and enhanced with modern APIs to provide enhanced capabilities while still reaching any web user on any device with a single codebase.

## Key Features of a PWA
 - Installable
 - Responsive
 - Push Notifications
 - Offline Access

## Making Your Rails PWA installable

For a web app to be promoted for installation by a supporting browser it requires a web app maifest, a JSON file that tells the browser how the PWA should appear and behave on the device.

The manifest is included using a ```html <link> ``` element in the `app/views/layouts/application.html.erb`

```html
<link rel="manifest" href="manifest.json" />
```

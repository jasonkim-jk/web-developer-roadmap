# Performance 3
* Optimazing codes by writing efficient functions using react wisely and etting into some code splitting
* Progressive web app: making web applications as close to native mobile apps as possible
* Progressive Tooling: https://progressivetooling.com/

## PWA - Progressive Web Apps
A web site that allows users to interact with the web page in many ways

<img src="https://d35fo82fjcw0y8.cloudfront.net/2019/05/03132950/what-is-a-progressive-web-apps.jpg">

> https://clevertap.com/blog/progressive-web-apps/

* https://web.dev/what-are-pwas/
* https://medium.com/@firt/progressive-web-apps-in-2020-c15018c9931c
* https://appmixo.com/pages/ios-and-android-app-using-pwa-technology


#### Progressive Web App attributes: What makes a PWA?
> https://www.coredna.com/blogs/progressive-web-app

  1. ***Responsive***: To fit any form factor

  2. ***Connectivity independent***: Progressively-enhanced with Service Workers (we’ll explain these in more detail below) to let them work offline

  3. ***App-like-interactions***: Adopt a Shell + Content application model to create appy navigations & interactions

  4. ***Fresh***: Transparently always up-to-date thanks to the Service Worker update process

  5. ***Safe***: Served via TLS (a Service Worker requirement) to prevent snooping

  6. ***Discoverable***: Are identifiable as “applications” thanks to W3C Manifests and Service Worker registration scope allowing search engines to find them

  7. ***Re-engageable***: Can access the re-engagement UIs of the OS; e.g. Push   Notifications

  8. ***Installable***: To the home screen through browser-provided prompts, allowing users to “keep” apps they find most useful without the hassle of an app store

  9. ***Linkable***: Meaning they’re zero-friction, zero-install, and easy to share.

#### Responsive website vs native app vs Progressive Web App (PWA)
<img src="https://www.coredna.com/web_images/progressive-web-app-vs-responsive-site-vs-native-app.png">

#### An overview of the device integration HTML5 APIs
* https://whatwebcando.today/
<img src="https://webagility.com/posts/how-progressive-web-apps-make-the-web-great-again/_/image/fe663f8b-4b26-4bad-81f1-3eb22d3116ab:9c93385483fad8349b632371d9d6c0085f182000/width-768/pwa-0.png">

#### Tools for PWA
* Lighthouse: It has audits for performance, accessibility, progressive web apps, SEO and more
    * https://developers.google.com/web/tools/lighthouse

#### Progressive Web App Requirements
<img src="https://d35fo82fjcw0y8.cloudfront.net/2019/05/03132933/progressive-web-apps-requirements.jpg">

> https://clevertap.com/blog/progressive-web-apps/

* Checklist: https://web.dev/pwa-checklist/#what-makes-a-good-progressive-web-app

1. **HTTPS**
    * https://letsencrypt.org/docs/
    * https://certbot.eff.org/
    * https://www.cloudflare.com/
    * https://pages.github.com/

2. **App Manifest**:
  A JSON file that tells the browser about your Progressive Web App and how it should behave when installed on the user's desktop or mobile device

<img src="https://developers.google.com/web/updates/images/2018/07/webmanifest.png">

> https://developers.google.com/web/updates/2018/07/pwacompat
   * https://web.dev/add-manifest/
   * https://developer.mozilla.org/en-US/docs/Web/Manifest
   * Favicon:
      * Recommand: https://realfavicongenerator.net/
      * https://github.com/bradtraversy/design-resources-for-developers#favicons


3. **Service Workers**:
   A JavaScript file that runs separately from the main browser thread, intercepting network requests, caching or retrieving resources from the cache, and delivering push messages

<img src="https://cdn.netlify.com/9852865e142b6f8453d7c1ae083d2e342adc8c02/cbc3a/img/blog/service-worker-diagram.png">

> https://www.netlify.com/blog/2017/10/31/service-workers-explained/
   * https://developers.google.com/web/ilt/pwa/introduction-to-service-worker
   * https://developers.google.com/web/fundamentals/primers/service-workers
   * Cache
     * https://web.dev/storage-for-the-web/
     * https://web.dev/cache-api-quick-guide/
   * Push Notification
     * https://auth0.com/blog/introduction-to-progressive-web-apps-push-notifications-part-3/

## Accessibility
* https://www.w3.org/standards/webdesign/accessibility

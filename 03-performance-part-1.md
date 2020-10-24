# Performance
To improve User Experience

## 3 Keys to Performance
#### 1. We can improve what happens on the client side
  - The front end device needs time to render the page on the screen
    - Critical render path
    - Optimized code
    - Progressive web app
#### 2. We can improve the transfer of our files over the wire network latency
  - Every request needs time time to travel from client to the server and back to our network
    - Minimize files
    - Minimize delivery
#### 3. We can improve the processing done on the backend
  - The web server needs time to load data maybe from the DB and even assemble the website before it sends it over
    - CDNs
    - Caching
    - Load Balancing
    - GZIP
    - DB scaling

## Network Performance
  - Minimize Text
    - Use HTML, CSS, JavaScript Minifier or Webpack to bundle
  - Minimize Images
    - Use proper file format: PNG, GIF, JPG, SVG
    - Compress and resize images if possible
      - https://tinypng.com
      - http://jpeg-optimizer.com
      - https://ezgif.com/optimize
    - Try to choose simple illustrations
    - Display different sized images for different backgrounds using CSS media query
      - https://gist.github.com/bartholomej/8415655
      - https://css-tricks.com/snippets/css/media-queries-for-standard-devices/
    - Use CDNs like imgix (https://www.imgix.com)
    - Remove image metadata (https://www.verexif.com/en)

## Delivery Optimization
  - Minimize files and limit the strips from backends to frontends
    - https://stackoverflow.com/questions/985431/max-parallel-http-connections-in-a-browser

## Critical Render Path
> "https://dimension85.com/images/critical-render-path-large.jpg"

<img src="https://dimension85.com/images/critical-render-path-large.jpg">

  - References
    - https://developer.mozilla.org/en-US/docs/Web/Performance/Critical_rendering_path
    - https://www.freecodecamp.org/news/an-introduction-to-web-performance-and-the-critical-rendering-path-ce1fb5029494/
    - https://bitsofco.de/understanding-the-critical-rendering-path/

#### 1. Constructing the Object Model
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/constructing-the-object-model
#### 2. Render-tree Construction, Layout, and Paint
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction
#### 3. Render Blocking CSS
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css
#### 4. Adding Interactivity with JavaScript
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript
#### 5. Measuring the Critical Rendering Path
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp
#### 6. Analyzing Critical Rendering Path Performance
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp
#### 7. Optimizing the Critical Rendering Path
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path
#### 8. PageSpeed Rules and Recommendations
  - https://developers.google.com/web/fundamentals/performance/critical-rendering-path/page-speed-rules-and-recommendations
### * Introduction to HTTP/2 and HTTP/3
  - https://developers.google.com/web/fundamentals/performance/http2
  - https://blog.cloudflare.com/http3-the-past-present-and-future/

## Webpage Performance Test Sites
  - Google PageSpeed Insights: https://developers.google.com/speed/pagespeed/insights/
  - WebPageTest: https://www.webpagetest.org/
  - https://phoenixnap.com/kb/best-website-speed-performance-test-tools
  - https://www.thinkwithgoogle.com/feature/testmysite/
  - https://pageweight.imgix.com/?ref=producthunt

## Prefetching, preloading, prebrowsing
  - https://css-tricks.com/prefetching-preloading-prebrowsing/

## Other Resources to Reference
  - http://youmightnotneedjquery.com/
  - https://developers.google.com/web/tools/chrome-devtools/rendering-tools
  - https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/reference
  - https://developers.google.com/web/updates/2017/11/devtools-release-notes#perf-monitor
  - https://developers.google.com/web/tools/lighthouse/
  - https://web.dev/fast/#optimize-your-images

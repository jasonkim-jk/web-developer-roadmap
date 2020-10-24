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
  - Minimize files and limit the strips from backends to frontends
    - https://developer.mozilla.org/en-US/docs/Web/Performance/Critical_rendering_path
    - https://bitsofco.de/understanding-the-critical-rendering-path/

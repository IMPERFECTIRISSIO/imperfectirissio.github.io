---
layout: page
title: About
permalink: /about/
---

<style>
  /* Remove default padding from Minima's content area for this page */
  /* to make the iframe use more space. */
  .main-content-wrap .page-content {
    padding: 0 !important;
    margin: 0 !important;
  }
  /* Ensure the iframe's direct parent div (if any) takes full width */
  .page-content > div {
      max-width: 100% !important;
  }
</style>

<iframe
    src="https://is.gd/umizet"
    style="width: 100%; height: 90vh; border: none; display: block;"
    frameborder="0"
    allowfullscreen
    title="Interactive Application">
    Your browser does not support iframes. Please visit <a href="https://is.gd/umizet">our application directly</a>.
</iframe>

<!--
  Note on iframe height:
  - `height: 90vh;` means 90% of the viewport (browser window) height.
  - This is generally a good value to fill most of the screen while accounting
    for your site's header and footer.
  - If you see double scrollbars (one for the page, one for the iframe),
    you might need to slightly reduce this value (e.g., to 85vh or 88vh).
  - If your Next.js app has its own internal scrolling, this setup should work well.
-->

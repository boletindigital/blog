---
title: Work
permalink: /work/
modified: 2016-05-27
layout: splash
excerpt: "Assorted good things I've done."
header:
  overlay_image: pourover-unsplash_1280.jpeg
  overlay_filter: 0.5
  caption: "Photo credit: [*@kfred*](https://unsplash.com/@kfred)"
feature_row1_overview:
  - excerpt: "_To view the source code of a project click **View Source**._"
feature_row1:
  -
    image_path: react-native-webpack-starter-kit.jpeg
    alt: "React Native Webpack Starter Kit logo"
    title: "React Native Webpack Starter Kit"
    excerpt: >
      iOS and Android development toolkit I created for building native apps using JavaScript.
      <br><br>
      <small>React Native / Babel / Webpack / Travis-CI</small>
    url: "https://github.com/jhabdas/react-native-webpack-starter-kit"
    btn_label: "View Source"
    btn_class: "btn--inverse"
  -
    image_path: lumpen-radio-ios-framed-cropped.png
    alt: "Lumpen Radio app screenshot"
    title: "Lumpen Radio App"
    excerpt: >
      iOS app I built using React Native. Selected for the <a href="https://facebook.github.io/react-native/showcase.html" target="_blank">React Native Showcase</a>. Includes webcast covering app construction.
      <br><br>
      [![Download it on the App Store.](/images/download-on-app-store-badge.svg)](http://appsto.re/us/NdeV7.i)<br><br>
      <small>React Native / Babel / Webpack / Xcode</small>
    url: "https://github.com/jhabdas/lumpen-radio"
    btn_label: "View Source"
    btn_class: "btn--inverse"
  -
    image_path: after-dark-framed.png
    alt: "After Dark screenshot"
    title: "After Dark"
    excerpt: >
      A retro dark theme for the Hugo static site generator.
      <br><br>
      <small>Golang / HTML5 / CSS3 / Hugo Static Site Generator</small>
    url: "https://comfusion.github.io/after-dark/"
    btn_label: "View Source"
    btn_class: "btn--inverse"
feature_row2:
  -
    image_path: lumpen-radio-web-schedule-framed.png
    alt: "Lumpen Radio Web screenshot"
    title: "Lumpen Radio Web 2.0"
    excerpt: >
      SEO-friendly and [seriously fast](https://speakerdeck.com/jhabdas/isomorphic-rendering-with-react?slide=13) React application for the Web.
      <br><br>
      <small>React / Alt / Babel / Webpack / Firebase</small>
    url: "https://github.com/jhabdas/lumpenradio-com"
    btn_label: "View Source"
    btn_class: "btn--inverse"
  -
    title: "Xanthippe"
    excerpt: >
      Chat parsing library using ES6, JSPM and Travis-CI. Runs entirely in the browser using SystemJS with CORS disabled.
      <br><br>
      <small>JSPM / SystemJS / Fetch API</small>
    url: "https://github.com/jhabdas/xanthippe"
    btn_label: "View Source"
    btn_class: "btn--inverse"
  - image_path: hopstop.png
    alt: "Hopstop application screenshot"
    title: "Hopstop"
    excerpt: >
      A beer-first mobile search app for the Web. Allows quick retrieval of beer info using the Untappd API.
      <br><br>
      <small>Hapi / Chaplin / Brunch / Untappd API</small>
    url: "https://github.com/jhabdas/hopstop"
    btn_label: "View Source"
    btn_class: "btn--inverse"
---

{% include feature_row id="feature_row1_overview" type="center" %}
{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}

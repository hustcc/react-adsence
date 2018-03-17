# react-adsense


> react-adsense is a React-component for Google AdSense / Baidu advertisement.

[![Build Status](https://travis-ci.org/hustcc/react-adsense.svg?branch=master)](https://travis-ci.org/hustcc/react-adsense) [![npm](https://img.shields.io/npm/v/react-adsense.svg?style=flat-square)](https://www.npmjs.com/package/react-adsense) [![npm](https://img.shields.io/npm/dt/react-adsense.svg?style=flat-square)](https://www.npmjs.com/package/react-adsense) [![npm](https://img.shields.io/npm/l/react-adsense.svg?style=flat-square)](https://www.npmjs.com/package/react-adsense) [![demo](https://img.shields.io/badge/LiveDemo-ClickHere-ff69b4.svg)](http://git.hust.cc/react-adsense/)


# 1. Install

> **npm install --save react-adsense**

Before use Google AdSense, you should add the `script` at the end of HTML.

```html
<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
```

# 2. Usage

```js
import React from 'react';
import AdSense from 'react-adsense';

// ads with no set-up
<AdSense.Google client='ca-pub-7292810486004926'
                slot='7806394673' />

// ads with custom format
<AdSense.Google client='ca-pub-7292810486004926'
                slot='7806394673'
                style={{ width: 500, height: 300, float: 'left' }}
                format='' />
                
// responsive and native ads
<AdSense.Google client='ca-pub-7292810486004926'
                slot='7806394673'
                style={{ display: 'block' }}
                layout='in-article'
                format='fluid' />
```


# 3. TODO

 - `Baidu` advertisement supported.
 - `Google` sync adsense supported.


# 4. LICENSE

MIT

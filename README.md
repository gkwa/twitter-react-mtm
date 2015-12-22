<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Topic branches**

- [book: react essentials](#book-react-essentials)
  - [Add React Chrome extension](#add-react-chrome-extension)
  - [React in Chrome Dev tools helps debug](#react-in-chrome-dev-tools-helps-debug)
  - [Clone filters](#clone-filters)
  - [snapkite engine](#snapkite-engine)
  - [node-gyp](#node-gyp)
  - [Twitter streaming filter overview](#twitter-streaming-filter-overview)
  - [twitter app](#twitter-app)
  - [Book code from React Essentials](#book-code-from-react-essentials)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

book: react essentials
======================

Add React Chrome extension
--------------------------

<https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi>

React in Chrome Dev tools helps debug
-------------------------------------

React in Chrome Dev tools helps debug <https://fb.me/react-devtools>

Clone filters
-------------

cd filters git clone
<https://github.com/Snapkite/snapkite-filter-is-possibly-sensitive.git>
git clone
<https://github.com/Snapkite/snapkite-filter-has-mobile-photo.git> git
clone <https://github.com/Snapkite/snapkite-filter-is-retweet.git> git
clone <https://github.com/Snapkite/snapkite-filter-has-text.git>

find . -iname 'example.config.json' | xargs -n1 dirname | while read
dir; do cp \$dir/example.config.json \$dir/config.json; done;

mkdir -p snapterest/{source/components,build} cd snapterest npm init
--yes npm install --save-dev browerify gulp

npm install --global browerify gulp npm install --save-dev babelify npm
install --save-dev vinyl-source-stream

snapkite engine
---------------

<https://github.com/Snapkite/snapkite-engine>

filter twitter feeds

git clone <https://github.com/Snapkite/snapkite-engine.git> cd
snapkite-engine && npm install

node-gyp
--------

<https://github.com/nodejs/node-gyp#installation>

npm install -g node-gyp

Twitter streaming filter overview
---------------------------------

<https://dev.twitter.com/streaming/overview>

twitter app
-----------

<https://apps.twitter.com/app/new>
<https://github.com/TaylorMonacelli/twitter-react-mtm>

Book code from React Essentials
-------------------------------

<https://github.com/fedosejev/react-essentials.git>

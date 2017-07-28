# \<messaging-tools\>

## Installation

``` bash
bower install messaging-tools --save
```

## Usage

**Remember to also include a `firebase-app` element with the `message-sender-id` set.**
``` html
<link rel="import" href="bower_components/messaging-tools/messaging-subscribe-toggle.html">

<messaging-subscribe-toggle id="toggle"
  topic="test-topic"
  value="Subscribe to test-topic"></messaging-subscribe-toggle>
```

## Setup

### Prerequisites

Install [npm](https://www.npmjs.com/) (or install [Node](https://nodejs.org/en/download/)):

``` bash
curl -L https://www.npmjs.com/install.sh | sh
```

Install [bower](https://bower.io/):

``` bash
npm install -g bower
```

### Tools

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

``` bash
npm install -g polymer-cli
```

### Start the development server

This command serves the app at `http://localhost:8080/components/messaging-tools/` and provides basic URL
routing for the app:

``` bash
polymer serve
```

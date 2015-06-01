# Ember Intercom

This Ember CLI addon injects Intercom's widget javascript code in your page.

## Installation

* `ember install ember-intercom`

## Configuration

In `config/environment.js`, you need to add this :

```javascript
  var ENV = {
    // ...
    intercom: {
      appId: "your app id here"
    },
    // ...
  }
```

If `ENV.intercom.appId` is missing, the javascript code will not be injected.

## Ember CLI

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).

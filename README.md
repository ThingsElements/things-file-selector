# things-file-selector

## Component for selecting files

It displays `things-file-selector-dialog` on the screen by sending an event to` things-dialog-manager` via `things-file-selector-toggle`.

Example:

```html
      <things-file-selector
        resource-url="attachments">
      </things-file-selector>
```


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-file-selector/`, where `things-file-selector` is the name of the directory containing it.

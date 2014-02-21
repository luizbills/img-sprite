# &lt;img-sprite&gt;

CSS Sprite Web Component

> Maintained by [Luiz "Bills"](https://github.com/luizbills).

## Demo

> [Check it live](http://jsfiddle.net/luizbills/GtJ2m/embedded/result,html/).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
    ```

2. Import &lt;img-sprite&gt; Custom Element:

    ```html
    <link rel="import" href="img-sprite.html">
    ```

3. Start using it!

    ```html
    <img-sprite src="img/image.png" width="32" height="32" frame="0"></img-sprite>
    ```

## Options

Attribute  | Default | Description
---        | ---     | ---
`src`      |         | source URL of the image (required)
`width`    | `1`     | sprite width
`height`   | `1`     | sprite height
`frame`    | `0`     | frame number (see the [example](http://jsfiddle.net/luizbills/GtJ2m/embedded/result,html/))

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/element-boilerplate/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)

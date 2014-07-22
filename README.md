x-caps
======

A web component that uppercases content.

## Demo

[Check it live!](http://emiljohansson.github.io/x-tabs)

Or [download as ZIP](https://github.com/emiljohansson/x-caps/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/my-repo/dist/my-element.html">
    ```

3. Start using it!

    ```html
    <x-caps value="default value"></x-caps>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`value`       | *string*    | ``           | Will be converted to upper case text.

## Events

Event         | Description
---           | ---
`valueChanged`| Triggers when the value of value updates.

## History

For detailed changelog, check [Releases](https://github.com/my-user/my-repo/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)

# css-toggle-input

Style checkboxes and radio inputs as iOS style on/off toggles.
No JavaScript needed.
HTML5 Standards Compliant

![Example of toggle in use](/images/css-toggle-input.gif)
### Demo

[Demo](http://chutou.github.io/css-toggle-input/)

### Install
- bower: `bower install --save css-toggle-input`
- npm: `npm install --save css-toggle-input`

## Usage
To see `css-toggle-input` in usage, [view the example](http://chutou.github.io/css-toggle-input/)

Use the following markup
`````html
<div id="container">
    <h2>toggle 默认</h2>
    <div>
        <div class="toggle">
            <input type="checkbox" id="qq" name="qq-setting" checked/>
            <label for="qq">qq</label>
        </div>
        <label for="qq">qq</label>
    </div>

    <div>
        <div class="toggle">
            <input type="checkbox" id="baidu" name="baidu-setting" checked/>
            <label for="baidu">baidu</label>
        </div>
        <label for="baidu">baidu</label>
    </div>

    <div>
        <div class="toggle">
            <input type="checkbox" id="alibaba" name="alibaba-setting"/>
            <label for="alibaba">alibaba</label>
        </div>
        <label for="alibaba">alibaba</label>
    </div>
    <h2>toggle 大小</h2>
    <div>
        <div class="toggle toggle-sm">
            <input type="checkbox" id="small" name="small-setting" checked/>
            <label for="small">small</label>
        </div>
        <label for="small">small</label>
    </div>

    <div class="toggle toggle">
                <input type="checkbox" id="default2" name="default2-setting" checked/>
                <label for="default2">default</label>
            </div>
            <label for="default2">default</label>
        </div>
    <div>

    <div>
        <div class="toggle toggle-lg">
            <input type="checkbox" id="large" name="large-setting" checked/>
            <label for="large">large</label>
        </div>
        <label for="large">large</label>
    </div>
    <h2>toggle 颜色</h2>
    <!-- <div>
        <div class="toggle toggle-default">
            <input type="checkbox" id="default" name="default-setting" checked/>
            <label for="default">default</label>
        </div>
        <label for="default">default</label>
    </div> -->
    <div>
        <div class="toggle toggle-primary">
            <input type="checkbox" id="primary" name="primary-setting" checked/>
            <label for="primary">primary</label>
        </div>
        <label for="primary">primary</label>
    </div>

    <div>
        <div class="toggle toggle-secondary">
            <input type="checkbox" id="secondary" name="secondary-setting" checked/>
            <label for="secondary">secondary</label>
        </div>
        <label for="baidu">secondary</label>
    </div>

    <div>
        <div class="toggle toggle-success">
            <input type="checkbox" id="success" name="success-setting" checked/>
            <label for="success">alibaba</label>
        </div>
        <label for="success">success</label>
    </div>
    <div>
        <div class="toggle toggle-warning">
            <input type="checkbox" id="warning" name="warning-setting" checked/>
            <label for="warning">warning</label>
        </div>
        <label for="warning">warning</label>
    </div>
    <div>
        <div class="toggle toggle-danger">
            <input type="checkbox" id="danger" name="danger-setting" checked/>
            <label for="danger">alibaba</label>
        </div>
        <label for="danger">danger</label>
    </div>
    <div>
        <div class="toggle toggle-dark">
            <input type="checkbox" id="dark" name="dark-setting" checked/>
            <label for="dark">dark</label>
        </div>
        <label for="dark">dark</label>
    </div>
    
</div>
`````


### Browser compatibility

- Chrome
- Firefox
- Safari
- Opera
- IE9 && IE9+

## License
[MIT](LICENSE)

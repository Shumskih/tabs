# Tabs

'Tabs' is a native javascript function for creating tabs on a web page. It takes three parameters, wich are strings(name of classes). First parameter is a tab's header class, second - a tab's items class, third - a tab's content class.

Example of usage:

```javascript
tabs('info-header', 'info-header-tab', 'info-tabcontent');
```

Example of html markup:

```html
<pre>
    <div class="info" >
        <div class="info-header">
            <div class="info-header-tab">First tab</div>
            <div class="info-header-tab">Second tab</div>
            <div class="info-header-tab">Third tab</div>
            <div class="info-header-tab">Fourth tab</div>
        </div>
        <div class="info-tabcontent fade">
            <div class="description">
                <div class="description-title">First tab title</div>
                <div class="description-text">First tab content</div>
            </div>
        </div>
        <div class="info-tabcontent fade">
            <div class="description">
                <div class="description-title">Second tab title</div>
                <div class="description-text">Second tab content</div>
            </div>
        </div>
        <div class="info-tabcontent fade">
            <div class="description">
                <div class="description-title">Third tab title</div>
                <div class="description-text">Second tab content</div>
            </div>
        </div>
        <div class="info-tabcontent fade">
            <div class="description">
                <div class="description-title">Fourth tab title</div>
                <div class="description-text">Fourth tab content</div>
            </div>
        </div>
    </div>
</pre>
```
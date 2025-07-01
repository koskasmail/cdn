<a name="topage"></a>

## `jQuery Migrate`

* `jQuery Migrate` is a helper plugin created by the jQuery team to make upgrading jQuery versions smoother and less painful.
* When jQuery introduces breaking changes—like removing old features or changing behaviors—older code can stop working.
* That’s where jQuery Migrate steps in:
    * `Restores Deprecated Features`:
        * It brings back removed or deprecated APIs so your legacy code continues to function.
    * `Logs Warnings`:
        * In development mode, it shows helpful console warnings when your code uses outdated features, guiding you on what to fix.
    * `Bridges Versions`:
        * It’s especially useful when upgrading from jQuery versions before 1.9 to newer versions like 3.x or 4.x.

#### html add scripts: `jquery` and `jquery-migrate`

* add the plugin `jquery-migrate` after loading `jquery` in your HTML:

####  example

```html
<script src="https://code.jquery.com/jquery-3.7.1.js"></script>
<script src="https://code.jquery.com/jquery-migrate-3.5.2.js"></script>
```

#### TIP
* Once your code is fully updated and no warnings appear, you can safely remove the plugin.
    * [official GitHub repo](https://github.com/jquery/jquery-migrate)
    * [npm](https://www.npmjs.com/package/jquery-migrate).

----

#### jQuery - migrate script
* [jquery-migrate-3.5.2.js](https://code.jquery.com/jquery-migrate-3.5.2.js)
* [jquery-migrate-3.5.2.min.js](https://code.jquery.com/jquery-migrate-3.5.2.min.js)


-----

<p align="right">(<a href="#topage">back to top</a>)</p>
<br/>
<br/>

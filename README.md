# writeLimit.js
This is a simple text input limit jQuery plugin.

### How to use

Firstly, include `writeLimit.js` after including `jQuery`.
Now you're ready to use it!

 - Hook the plugin to an input field / textarea
    ```js
    $("#input-field").writeLimit();
    ```
  - On it's own it will not do anything, so you'll need to pass it some parameters.
    ```js
    $("#input-field").writeLimit(feedback, limit, addon);
    // Feedback - A place where to return the current character number and maximum length.
    // Limit - The maximum amount of characters to be inserted in the current field.
    // Addon - OPTIONAL - something to be appended to feedback.
    ```
  - Example
    ```js
    $("#input-field).writeLimit("#input-field-feedback", 1024, "characters");
    ```

License
----

MIT
  

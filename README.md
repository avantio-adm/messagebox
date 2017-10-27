# Message Box
Bootstrap Plugin That Creates Modal Dialogs

# Features
- Creates modals in JavaScript instead of in the template.
- Adds OK and Cancel Events
- Adds A Standard Dialog

# Typical Usage

<pre>
var mb = messageBox();
mb.setTitle('example');
mb.setBody('Hello World');
mb.show();

mb.on(‘ok’, function() {
    “use strict”;
    // do somthing
    mb.remove();
});

mb.on(‘cancel’, function() {
    “use strict”;
    // do something
    mb.remove();
})
</pre>

Please see the [wiki](https://github.com/daniel-samson/messagebox/wiki) for more information

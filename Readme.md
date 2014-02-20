*This repository is a mirror of the [component](http://component.io) module [tomerdmnt/offcanvas](http://github.com/tomerdmnt/offcanvas). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/tomerdmnt-offcanvas`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# offcanvas

  OffCanvas [component](http://github.com/component/component) as described in http://jasonweaver.name/lab/offcanvas/
  A great way to bring a responsive site up quickly.

  ```html
    <body>
      <div role="nav">
      </div>
      <div role="main">
      </div>
    </body>
  ```

  ```js
    var OffCanvas = require('offcanvas')();

    // show navigation
    OffCanvas.nav();

    // show main
    OffCanvas.main();
  ```
## Installation

    $ component install tomerdmnt/offcanvas

## API

### ()
bind to the page (check if javascript exists. add transitions only after load)

### nav()
Show navigation

### main()
Show main

### toggle()
Toggles between nav and main

## License

  MIT

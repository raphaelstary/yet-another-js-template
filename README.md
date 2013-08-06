yet-another-js-template
=======================

my new simple (standard) template for js projects, containing volo, requireJS, jasmine + node.js dev modules 

Install Dependencies
------------

The project's build/dev stack depends on node.js with npm and volo. Run the following commands from the root folder to install all project dependencies:

    npm install
    volo install

All dependencies are listed in `package.json`.

Testing
-------

To run headless tests with node.js enter:

    volo test

To execute the tests in a browser open `test/SpecRunner.html`.

(With all methods you have to include new spec files manually in `test/allSpecs.js`)
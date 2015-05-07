#Crubrand

## Dependencies

The crubrand theme depends on these other project:

* [bootstrap-scss](https://github.com/twbs/bootstrap-sass)
* [jquery](https://github.com/jquery/jquery)

If you install the Crubrand using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

The recommended installation method is Bower, but you can install the project via a Git Submodule, or copy and paste.

### Install using Bower:

If you already have an existing bower.json file, run the following command:

    $ bower install --save crubrand

Otherwise, create a bower.json file that lists crubrand as a dependency and change the values to fit your project:

    {
      "name": "your-project-name",
      "description": "Your-project-description",
      "version": "your-project-version",
      "dependencies": {
        "crubrand": "latest-release"
      }
    }

Once installed, `@import` into your project's main scss file:

    @import "bower_components/crubrand/crubrand";

### Install as a Git Submodule

    $ git submodule add git@github.com:CruGlobal/crubrand.git

Once installed, `@import` into your project in its Objects layer:

    @import "crubrand/crubrand";

### Install via file download

The least recommended option for installation is to simply download
`crubrand` into your project and `@import` it into your project.

    @import "crubrand/crubrand";

## Updating crubrand using Bower

    bower update crubrand

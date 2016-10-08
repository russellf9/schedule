# Schedule App (Based on angular-seed)

A simple app to Schedule time, using Angular 1 with Components.


### Install Dependencies

We have two kinds of dependencies in this project: tools and angular framework code.  The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [node package manager][npm].
* We get the angular code via `bower`, a [client-side code package manager][bower].

We have preconfigured `npm` to automatically run `bower` so we can simply do:

```
npm install
```

### Run the Application

We have pre-configured the project with a simple development web server.  The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `http://localhost:8000/index.html`.

## Project Objectives

# Learn how to use Angular Components
# Learn how best to set up a SASS structure
# Work out an upgrade plan from AS1 to AS2

## Project Notes

I used the simple angular-seed without a separate Build and Bin folder so I'll have to add a few things to the build process as I'd like to use SASS, Bootstrap and a few other things.

Also, to begin with I didn't want loads of extra build stuff to do.

For SASS

Used the Webstorm SASS compiler - See: [Transpiling Sass, Less, and SCSS to CSS](https://www.jetbrains.com/help/webstorm/2016.2/transpiling-sass-less-and-scss-to-css.html)

Was a bit fiddly to see how to set the correct settings - 

Arguments: `--no-cache --update $FileName$:$FileParentDir$/app/css/$FileNameWithoutExtension$.css`

Output paths to refresh: `$FileParentDir$/app/css/$FileNameWithoutExtension$.css:$FileParentDir$/app/css/$FileNameWithoutExtension$.css.map`

As well as building I'd like to set up a more definitive SASS structure to use in future projects.


## Directory Layout

I'll organise the project per feature.

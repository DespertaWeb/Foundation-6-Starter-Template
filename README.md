# Foundation for Sites Template


### Manual Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/zurb/foundation-sites-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Run `gulp sass` to run the Sass compiler. It will re-run every time you save a Sass file.


Run `gulp scripts` to compile and concatenate all js files into /public/app.js.

Run `gulp watch` for a Livereload effect.
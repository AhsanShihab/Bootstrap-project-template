# Bootstrap Project starter template

This repository is configured with some node modules for developing and building Bootstrap project. To get started download or clone the repository

```bash
git clone https://github.com/AhsanShihab/Bootstrap-project-template.git
```

Then run,

```bash
npm install
```

## Linux or MacOS
The scripts in `package.json` file is configured for Windows. If you are on MacOS or Linux, replace all the \\" (back slash-double quote) with \' (single qoute).

## New HTML files
The project is build with two example html files `index.html` and `aboutus.html`. You should copy the starter code to your new pages for proper import of all the necessary files. As you add new pages, insert them in `usemin` script in `package.json` file as following.

```
&& usemin your_page.html -d dist --htmlmin -o dist/your_page.html
```

## CSS
Use sass for custom styling your webpage. The `styles.scss` file will be automatically converted to `styles.css`. If you want to edit css file directly, create another css file with different name and import that in your html file.

## Dev and Build

For development run
```bash
npm start
```

For build, run

```bash
npm build
```

Build will put all the built files in `dist` folder.


## Modules
### Bootstrap
For designing responsive website UI for different screen sizes

### JQuery, Popper.js
For supporting Bootstrap component functionalities

### Font-awesome, bootstrap-social
For inserting icons in website.

### Lite Server
For providing a live server for development

### node-sass
For converting scss files to css files

### rimraf
For deleting directories so that old files are replaced by updated files

### copyfiles
For copying files to dist folder

### imagemin
For compressing images to optimal size

### cssmin, htmlmin, uglifyjs, usemin-cli
For minimizing and uglifying html, css and javascript files for deployment

### onchange
For keeping watch on file changes and updating files as they change for live rendering.

### parallelshell
For running several scripts in parallel

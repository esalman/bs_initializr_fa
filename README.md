# bs_initializr_fa
Twitter Bootstrap less-complied with Font Awesome pasted into Initializr with suitable setting

Bootstrap is shipped with glyphicons, but no one likes them. Everyone likes Font Awesome. So I complied Bootstrap with Font Awesome; I use it for my projects frequently.

**To use:** initializr folder is your starting template. Or just get bootstrap.css from initializr/css directory.

**Initializr Settings**

modernizr, respond, jQuery (minified), IE classes, old browser warning, Google analytics, favicon, Apple and Windows icons, .htaccess and 404 page.

**How to Compile**

- Download Winless: www.winless.org
- Install
- Add folder: bootstrap-master/less
- Copy font-awesome directory to above folder
- In the same folder, edit bootstrap.less
- Replace `glyphicons.less` with `font-awesome/less/font-awesome.less`
- Back to Winless, deselect all files, only select bootstrap.less and (optional) minify next to it
- Compile, hopefully no error
- Done!

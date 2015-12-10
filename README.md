Before you start running Gulp start, there are a few steps you need to follow...

index.html:
Add these comments that will recognize you want to split the file:(
<!-- split header.php -->,
<!-- split index.php -->,
<!-- split footer.php -->
)

To all your other files you need to wrap your content "without header and footer" with these comments:(
<!-- split "filename".php -->
<!-- split stop -->
)

When you are done with this you can start working in your cmd...

# gulp-webapp-wp-template-automation
Automation for converting a gulp-webapp to a WordPress theme

Run $ npm install
Run $ npm init - to change project name and version etc. (dirty, I know!)
(Run $ gulp start - to initialize templating)
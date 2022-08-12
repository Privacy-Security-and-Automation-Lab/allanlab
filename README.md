# PSAL Lab Website

This will be the website of our academic research group PSAL (Privacy, Security and Automation Lab) at New York University.

Please be patient while we are working on this :)


**For Future Maintainers**

We are running this on apache2

After making changes to the site you need to run the following from the psal_website directory to rebuild the site. (This includes adding new pictures and what not)

    bundle exec jekyll clean
    bundle exec jekyll build

    mv _site/* ../../var/www/html


Thanks for making these theme available to [Allen Lab @ Leiden University](https://www.allanlab.org). Code released under the MIT License.

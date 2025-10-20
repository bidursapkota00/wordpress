# WordPress Guide

![Bidur Sapkota](https://www.bidursapkota.com.np/_next/image?url=%2Fimages%2Fprofile3.png&w=48&q=75 "Bidur Sapkota - Developer")&nbsp;[Bidur Sapkota](https://www.bidursapkota.com.np/)

![WordPress Guide by Bidur Sapkota](/6-wordpress-post.jpg "WordPress Guide – Blog by Bidur Sapkota")

## Table of Contents

1. [Install WordPress with XAMPP](#install-wordpress-with-xampp)
2. [Initial WordPress Setup Process](#initial-wordpress-setup-process)

## Install WordPress with XAMPP

- Download and install XAMPP from [here](https://www.apachefriends.org/download.html).
- Download Wordpress form [here](https://wordpress.org/download/).
- Unzip wordpress-v.x.x.zip. (Extract here.)
- Rename extracted `wordpress` folder to your project name, `blog` for now.
- Move `blog` folder inside htdocs.
- Open XAMPP Control Panel, Start Apache & MySQL.
- Click Admin of MySQL.
- Click `New` to create new database named `blog` and click `create`.
- Open `localhost/blog`.
- Click Continue for English language.
- Click Lets go!.
- Add database name as above that is `blog`
- Add username `root`.
- Leave password blank.
- Click submit.
- Click `Run the installation`.
- Give website name `Blog`.
- Give username `root`.
- Give password `root`.
- Check confirm use of weak password.
- Add your email.
- Click `Install Wordpress`
- Click on `LogIn` using username `root` and password `root`.
- You will end up on wordpress dashboard `http://localhost/blog/wp-admin/`

## Initial WordPress Setup Process

1. Install WordPress on host or local machine
2. Setup Privacy Page via Settings -> Privacy menu
3. Install WP AUTOTERMS and create the Terms and Conditions page.
4. Install WP Forms Lite and create a Contact Form.
5. Install Yoast SEO (sitemap wont work on local install but SEO features work fine).
6. Install UpdraftPlus for backups, but only recommended for Web hosted WordPress, not local
   installs.
7. Install All In One Security & Firewall, on web host installs only.
8. Delete Hello World Post.
9. Delete Sample Page.
10. Change default category from Uncategorized to something more useful.
11. Cleanout any plugins WordPress installed automatically, e.g. Hello Dolly.
12. Install the theme you want to use, and delete any unused themes.
13. Go through settings menus and check basics are correct.
    1. General Settings: Admin email is correct
    2. Reading Settings: Summary is checked and search engine visibility is correct.
    3. Discussion: Uncheck “allow link notifications”, “a comment is held for moderation”,
       “comment author must have previously approved comment” and Check “Comment
       must be manually approved”.
    4. Set Gravatars as required.
14. Setup Gravatar
15. Permalinks
16. Clear out Widgets
    You should now have a blank WordPress set up and ready for you to start building your site.

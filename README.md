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
6. Install UpdraftPlus for backups, but only recommended for Web hosted WordPress, not local installs.
7. Install All In One Security & Firewall, on web host installs only.
8. Delete Hello World Post.
9. Delete Sample Page.
10. Change default category from Uncategorized to something more useful.
11. Cleanout any plugins WordPress installed automatically, e.g. Hello Dolly.
12. Install the theme you want to use, and delete any unused themes.
13. Go through settings menus and check basics are correct.
    1. General Settings: Admin email is correct
    2. Reading Settings: Summary is checked and search engine visibility is correct.
    3. Discussion:
       Uncheck “allow link notifications”,
       “a comment is held for moderation”,
       “comment author must have previously approved comment”
       and Check “Comment must be manually approved”.
    4. Set Gravatars as required.
14. Setup Gravatar
15. Permalinks
16. Clear out Widgets
    You should now have a blank WordPress set up and ready for you to start building your site.

# CMS and WordPress Questions - Answers

## Question 1: What is difference between WordPress theme and template? Write the steps to add and edit pages in WordPress.

### Difference between WordPress Theme and Template

**WordPress Theme:**

- A complete package that controls the entire look, feel, and functionality of a website
- Contains multiple template files, stylesheets, JavaScript files, and images
- Defines the overall design and layout of the entire website
- Can be changed without losing content
- Examples: Twenty Twenty-Four, Astra, Divi

**WordPress Template:**

- A single file within a theme that controls the layout of a specific page or section
- Part of a theme's structure
- Defines how content is displayed on specific pages (e.g., page.php, single.php, header.php)
- Cannot function independently without a theme

**Analogy:** If a theme is a house, templates are individual rooms with specific purposes.

### Steps to Add Pages in WordPress

1. **Login to WordPress Dashboard**

   - Navigate to your-site.com/wp-admin
   - Enter your credentials

2. **Navigate to Pages**

   - Click on "Pages" in the left sidebar
   - Click "Add New"

3. **Create Your Page**

   - Enter the page title in the title field
   - Add content using the block editor (Gutenberg) or classic editor
   - Add blocks for text, images, videos, etc.

4. **Configure Page Settings**

   - Set page attributes (parent page, template, order)
   - Add featured image if needed
   - Set page visibility (public, private, password protected)

5. **Publish the Page**
   - Click "Publish" button on the right sidebar
   - Confirm by clicking "Publish" again

### Steps to Edit Pages in WordPress

1. **Access Pages List**

   - Go to Dashboard → Pages → All Pages

2. **Select Page to Edit**

   - Hover over the page you want to edit
   - Click "Edit" that appears below the title
   - OR click on the page title directly

3. **Make Changes**

   - Modify title, content, or blocks as needed
   - Update images, text, or layout

4. **Update the Page**
   - Click the "Update" button to save changes
   - View the page on frontend to verify changes

---

## Question 2: What is Widgets? Explain different Features of CMS.

### What are Widgets?

Widgets are small blocks or modules that perform specific functions and can be added to different areas of a website (typically sidebars, footers, or headers). They provide dynamic content and functionality without requiring coding knowledge.

**Common Widget Examples:**

- Search bar
- Recent posts
- Categories list
- Tag cloud
- Calendar
- Text/HTML widget
- Social media feeds
- Custom menus

**Widget Areas:** Pre-defined sections in themes where widgets can be placed (also called "sidebars" even if not on the side).

### Different Features of CMS

**1. User Management**

- Multiple user roles (Administrator, Editor, Author, Contributor, Subscriber)
- Permission-based access control
- User authentication and authorization
- Profile management

**2. Content Creation and Editing**

- WYSIWYG (What You See Is What You Get) editor
- Rich text formatting
- Media library for images, videos, and documents
- Draft and preview functionality
- Scheduling and publishing options

**3. Theme and Template Management**

- Easy theme switching
- Customizable templates
- Responsive design support
- Template hierarchy

**4. Plugin/Extension System**

- Extend functionality without core modifications
- Third-party integrations
- Custom feature additions
- Easy installation and management

**5. SEO Features**

- URL customization (permalinks)
- Meta tags management
- XML sitemap generation
- SEO-friendly structure

**6. Media Management**

- Centralized media library
- Image editing and optimization
- Multiple file format support
- Organization with folders/categories

**7. Multi-language Support**

- Content translation capabilities
- RTL (Right-to-Left) language support
- Localization features

**8. Version Control**

- Content revision history
- Rollback to previous versions
- Compare changes between versions

**9. Security Features**

- Regular updates
- User authentication
- Backup and restore functionality
- Security plugins/extensions

**10. Workflow Management**

- Content approval process
- Scheduled publishing
- Editorial calendar
- Collaboration tools

---

## Question 3: What is CMS? Write the steps to create submenu in WordPress or Joomla?

### What is CMS?

**CMS (Content Management System)** is a software application that allows users to create, manage, modify, and publish digital content without requiring specialized technical knowledge or coding skills.

**Key Characteristics:**

- User-friendly interface
- Separation of content from design
- Multiple user collaboration
- Built-in templates and themes
- Plugin/extension architecture

**Popular CMS Examples:**

- WordPress (most popular, 43% of web)
- Joomla
- Drupal
- Magento (e-commerce focused)
- Shopify

**Benefits:**

- No coding knowledge required
- Cost-effective website management
- Easy content updates
- SEO-friendly
- Community support and resources

### Steps to Create Submenu in WordPress

**Method 1: Using Menus Interface**

1. **Access Menu Editor**

   - Login to WordPress Dashboard
   - Navigate to Appearance → Menus

2. **Select or Create Menu**

   - Select an existing menu or create new by entering menu name
   - Click "Create Menu"

3. **Add Menu Items**

   - From left sidebar, select pages, posts, custom links, or categories
   - Click "Add to Menu"

4. **Create Submenu Structure**

   - Drag the menu item slightly to the right under the parent item
   - The item becomes indented, indicating it's a submenu
   - You can create multiple levels by further indenting

5. **Configure Menu Settings**

   - Assign menu to a location (Primary Menu, Footer Menu, etc.)
   - Check the box for desired location

6. **Save Menu**
   - Click "Save Menu" button

**Visual Hierarchy:**

```
- Parent Menu Item
    - Submenu Item 1
        - Sub-submenu Item
    - Submenu Item 2
- Another Parent Item
```

### Steps to Create Submenu in Joomla

**Method: Using Menu Manager**

1. **Access Menu Manager**

   - Login to Joomla Administrator panel
   - Navigate to Menus → Main Menu (or desired menu)

2. **Create Parent Menu Item**

   - Click "New" button
   - Select menu item type
   - Enter menu title
   - Configure settings
   - Save & Close

3. **Create Submenu Item**

   - Click "New" again
   - Enter submenu title
   - Select menu item type

4. **Set Parent Item**

   - In the right panel, find "Parent Item" dropdown
   - Select the parent menu item you created earlier
   - This makes current item a child/submenu

5. **Configure Additional Settings**

   - Set menu status to "Published"
   - Configure access level
   - Set ordering if needed

6. **Save Submenu Item**

   - Click "Save & Close"

7. **Verify Menu Structure**
   - Return to menu manager
   - You'll see submenu items indented under parent items
   - Adjust ordering by dragging items if needed

**Additional Tips:**

- You can create multiple submenu levels in both WordPress and Joomla
- Use descriptive names for better navigation
- Test menu on frontend after creation
- Ensure mobile responsiveness

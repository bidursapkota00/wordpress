# WordPress Guide

![Bidur Sapkota](https://www.bidursapkota.com.np/_next/image?url=%2Fimages%2Fprofile3.png&w=48&q=75 "Bidur Sapkota - Developer")&nbsp;[Bidur Sapkota](https://www.bidursapkota.com.np/)

![WordPress Guide by Bidur Sapkota](/10-wordpress-guide.jpg "WordPress Guide – Blog by Bidur Sapkota")

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

**Old Question:**

**What is difference between WordPress theme and template? Write the steps to add and edit pages in WordPress.**

**WordPress Theme:**

- A complete package that controls the entire look, feel, and functionality of a website
- Contains multiple template files, stylesheets, JavaScript files, and images
- Contains all the design elements including colors, fonts, layouts, and overall appearance
- A theme is made up of several templates working together
- Example: Twenty Twenty-Four, Astra

**WordPress Template:**

- A single file within a theme that controls the layout of a specific page or section
- Part of a theme's structure
- Defines how content is displayed on specific pages (e.g., page.php, single.php, header.php)
- Cannot function independently without a theme

**In Summary:** A theme is the complete package, while a template is an individual file within that theme.

<br>

**Steps to Add Pages in WordPress**

1. **Login to WordPress Admin Dashboard**

   - Navigate to your-site.com/wp-admin
   - Enter your username and password

2. **Access Pages Section**

   - Click on "Pages" in the left sidebar menu
   - Click on "Add New" or "Add New Page"

3. **Enter Page Details**

   - Add a title in the "Add Title" field
   - Add content using the block editor (Gutenberg) or classic editor
   - Add images, videos, or other media as needed

4. **Publish the Page**
   - Click the "Publish" button
   - Confirm by clicking "Publish" again

<br>

**Steps to Edit Pages in WordPress**

1. **Navigate to Pages List**

   - Go to WordPress Dashboard
   - Click on "Pages" → "All Pages"

2. **Select Page to Edit**

   - Hover over the page you want to edit
   - Click "Edit" link that appears below the page title
   - Or click directly on the page title

3. **Make Changes**

   - Modify the title, content, or media as needed
   - Update page settings or template if required
   - Add or remove blocks in the editor

4. **Update the Page**
   - Click the "Update" button to save changes
   - The page will be updated immediately on the live site

---

**Old Question:**

**What is Widgets?**

Widgets are small blocks or modules that perform specific functions and can be added to different areas of a website (typically sidebars, footers, or headers). They provide dynamic content and functionality without requiring coding knowledge.

**Common Widget Examples:**

- Search bar
- Recent posts
- Categories list
- Calendar

---

**What is CMS? Explain different Features of CMS.**

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

**Different Features of CMS**

**1. User Management**

- Multiple user roles (Administrator, Editor, Author, Contributor, Subscriber)
- Permission-based access control
- User authentication and authorization
- Profile management

**2. Content Creation and Editing**

- Easy creation, editing, and deletion of content
- No coding knowledge required for basic operations
- Support for multiple content types (pages, posts, media)
- Rich text editing with formatting options
- Media library for managing images, videos, and documents
- Version control and revision history

**3. Theme and Template Management**

- Easy theme switching
- Customizable templates without coding
- Responsive design support

**4. Plugin/Extension System**

- Extensible functionality through plugins or extensions
- Thousands of free and premium plugins available
- Easy installation and activation
- Custom plugin development support

**5. SEO Features**

- SEO-friendly URLs (permalinks)
- Meta tags and descriptions
- XML sitemap generation
- SEO plugins for advanced optimization

**6. Media Management**

- Centralized media library
- Image editing and optimization
- Multiple file format support
- Automatic image resizing and thumbnail generation

**7. Multi-language Support**

- Built-in or plugin-based translation features
- Support for multilingual websites
- Language switchers for users

**8. Version Control**

- Content revision history
- Rollback to previous versions
- Compare changes between versions

**9. Security Features**

- Regular updates
- User authentication and authorization
- Backup and restore functionality
- Security plugins/extensions

**10. Workflow Management**

- Draft saving and preview options
- Content approval process
- Scheduled publishing
- Collaboration tools

---

## Question 3: Write the steps to create submenu in WordPress or Joomla?

### Steps to Create Submenu in WordPress

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

---

**Old Question:**

**Discuss about MVC architecture with appropriate diagram.**

<br>

### **MVC Architecture**

**MVC (Model–View–Controller)** is a **software architectural pattern** used for designing applications by separating them into three interconnected components:

![MVC Architecture](/MVC-Architecture.webp)

### **1. Model**

- Represents the **data and the business logic** of the application.
- It directly handles:

  - Data storage
  - Data retrieval
  - Business rules
  - Database interaction

- The Model does not depend on the View or Controller.

**Example:**
A `User` class that deals with user data, database queries, etc.

---

### **2. View**

- Represents the **UI (User Interface)** of the application.
- It displays the data coming from the Model.
- It does not contain business logic.
- Views change when the Model data changes.

**Example:**
HTML pages, templates, or UI screens.

---

### **3. Controller**

- Acts as a **middleman** between View and Model.
- Handles user requests, processes them, and returns the appropriate output.
- Controller:

  - Receives request
  - Validates input
  - Interacts with the Model
  - Selects a View to display

**Example:**
A `UserController` that receives a login request, asks Model to verify data, and returns a View.

---

#### **How MVC Works (Flow)**

1. **User interacts with View** (click, submit form).
2. **Controller receives the request**.
3. **Controller calls Model** to get or update data.
4. **Model returns data** to Controller.
5. **Controller updates the View**.
6. **View displays the response** to the user.

---

#### **Benefits of MVC**

**1. Separation of Concerns**

Each component has a separate responsibility → code is easier to write, test, and maintain.

**2. Reusability**

Models and Views can be reused across different parts of the application.

**3. Scalability**

MVC supports large applications by breaking them into manageable components.

**4. Easier Testing**

Since logic is separated, unit testing becomes simpler.

---

#### **Real-World Examples**

- **Laravel** (PHP)
- **ASP.NET MVC**
- **Spring MVC** (Java)

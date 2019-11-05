## Links & Resources.

* Validate Code – validator.w3.org
* Enqueuing Scripts – http://codex.wordpress.org/Function_Reference/wp_enqueue_script
* Enqueuing Styles – http://codex.wordpress.org/Function_Reference/wp_enqueue_style
* Data Validation – http://codex.wordpress.org/Data_Validation
* Data Validation – http://www.paulund.co.uk/data-validation-with-wordpress
* Data Validation – http://mikejolley.com/2013/08/keeping-your-shit-secure-whilst-developing-for-wordpress/
* Sanitizing – http://codex.wordpress.org/Validating_Sanitizing_and_Escaping_User_Data
* CSS / JS Compression – http://refresh-sf.com/yui/
* Compress Images – http://www.smushit.com/ysmush.it/
* Theme Unit Test – http://codex.wordpress.org/Theme_Unit_Test
* Test Widget Areas –https://wordpress.org/plugins/monster-widget/
* Theme Check – https://wordpress.org/plugins/theme-check/
* Themeforest Guidelines – https://help.market.envato.com/hc/en-us/articles/202822450-WordPress-Theme-Submission-Requirements
* Understanding The Review Process – http://marketblog.envato.com/general/submission-tip-understand-the-themeforest-reviewing-process/
* Visual Hierarchy – https://hackdesign.org/lessons/19/
* Inspiration – http://www.awwwards.com/
* Inspiration – https://dribbble.com/



## Soft/Hard Reject Reasons

* CSS file need to be well documented with proper table of contents. Read more:http://www.smashingmagazine.com/2008/05/02/improving-code-readability-with-css-styleguides/

* 404 error in any link. Check Browser Console. (image not found).

* Please use “nav” tags for all navigation in the template. http://www.html-5-tutorial.com/nav-element.htm

* Consider using the preferred .on() rather than .click(), .bind(), .hover(), etc.

* Inline CSS is not permitted. Please remove all inline CSS.

* Theme does not meet Markup Validation requirements (https://validator.w3.org/)

* Unit test is not displayed in an appropriate way;

* Posts, widgets, search page, 404 page, menu, images are displayed incorrectly;

* Sticky Posts are displayed inappropriately;

* Typography mistakes or paddings issues;

* If the esc function for dynamic data display as well as data used for other purposes is missed;

* Due to mistakes in documentation

* If shortcodes, custom post types, widgets, SVG support are created with the help of options in the Theme. This feature functionality should be generated in one plugin

* If google fonts are added incorrectly. How to add google fonts in WordPress: https://gist.github.com/shameemreza/c7fc0c44765263f0ab89d6e3877e1703

* Standard handles for wp_enqueue_script(), wp_enqueue_style() and add_image_size() : https://github.com/grappler/wp-standard-handles

* Design issues with the following template categories: PSD, HTML, WordPress);

* Different padding/margins;

* Typography issues;

* Prefix all your custom functions/variables/classes. A good rule of thumb is to prefix everything with your theme initials and your own initials. http://nacin.com/2010/05/11/in-wordpress-prefix-everything/

* All dynamic data must be correctly escaped for the context where it is rendered.

* Perform a global search for "echo $" and escape ALL outputs. This will ensure there are no security issues.

* query_posts() will change your main query and is not recommended. Only use if absolutely necessary: http://codex.wordpress.org/Function_Reference/wp_reset_query

* wp_reset_query - if you’re not using query_posts(), then you really shouldn’t be messing with the main $wp_query variable, as wp_reset_query() does.

*  Make sure all the WP default widgets display properly in all widgetized areas. You can check with monster widgets plugin.

* Custom widget areas must use the safety condition “is_active_sidebar” to ensure no naming conflict with other plugins.

* All dynamic data must be correctly escaped for the context where it is rendered.

- http://developer.wordpress.com/themes/escaping/
- https://vip.wordpress.com/2014/06/20/the-importance-of-escaping-all-the-things/
- https://css-tricks.com/introduction-to-wordpress-front-end-security-escaping-the-things/


* index.php should be reserved for default blogroll and if there is no static page being set as front page, it should display the blogroll on homepage. You can use a custom page template for homepage.

* No space between paragraphs. http://envato.d.pr/1d4O6/5z2D59V8

* Import the Theme Unit Test [http://codex.wordpress.org/Theme_Unit_Test] file and make sure that:

- Posts display correctly, with no apparent visual problems or errors.
- Posts display in correct order.
- Page navigation displays and works correctly.
- The search results page displays properly, with search query results displayed.
- As "sticky posts" are a core feature, the theme should style and display them appropriately.
- "Read More" link works properly (links to single post at "<!--more-->" tag location).
- If theme supports post format type, post displays as intended in the index view.
- Lack of body text should not adversely impact the layout.
- Theme must incorporate both the "Tag" and the "Category" taxonomies in some manner.
- Floats are cleared properly for floated element (thumbnail image) at the end of the post content.
- Look for potential overflow issues if the theme has a small title area matched with a long non-breaking string. 



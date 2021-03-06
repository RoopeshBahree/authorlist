# AuthorList


== Description ==

Create a Page for users with their roles. With this plugin, you can create different pages as per its user role. This plugin is applicable to any of the post type you have on your WordPress site. It has an inbuilt feature to manage the pagination, sorting options in both the way ASC or DESC. You can also assign multiple post type with a comma separator. So there is no limitation with the Authorlist plugin. 

How to use this plugin
 After activation, you need to create one page and use this given short code on that page. 
[author-list role=administrator post_type=post,page number=1 orderby=email order=ASC]

Explanation of this shortcode. 

•	role=administrator [It can be any of the roles which your WordPress site has like, subscriber, administrator etc..]
•	post_type="post, page" [It can be any of the post types like listing, classifieds, Events, Properties etc..]
•	number=1 [Here you needs to mention that how many authors you needs to list on the single page. ]
•	orderby=email [You needs to mention the field's slug name. By which field you need to perform the sorting order. ]
•	order=ASC [You can perform the sorting by either ASC order or DESC order] 

BENEFITS, FEATURES, AND OPTIONS

Works with any WordPress Theme

Customize the Look and Feel

Easily add Custom CSS and HTML

Uses WordPress Best Practices

== Installation ==

- Download zip
- Extract the Authorlist directory to your computer
- Upload the Authorlist directory to the /wp-content/plugins/ directory
- Activate the plugin in the Plugin’s dashboard

= How do I customize page? =

Yes, you can. To override plugin template files in your theme (or better yet, child theme) simply make a folder named 'author-list' within your theme directory, and then create the template file named 'author-bio.php' and with other plugin too you can overwrite it too by using ' author_list_get_template_part ' filter.


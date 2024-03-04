# Week 5
## Learning Activities & Resources
This week I created a child theme that was used on the assignment website and then removed to ensure I understood how to go back if an issue occurs. 
It is currently not applied to anything.

I have also watched following the linked In videos and youtube videos.
.

- https://developer.wordpress.org/themes/advanced-topics/child-themes/
- https://youtu.be/coLDoM1fQcc
- https://www.linkedin.com/learning/wordpress-building-child-themes-3/level-up-to-wordpress-developer?autoplay=true&u=2223545
- https://www.youtube.com/watch?v=jk1zu6s4HEQ&t=686s
- https://www.youtube.com/watch?v=coLDoM1fQcc

## Estimated time
Spent approxiamtely 6 hours this week. This is less than the weekly target of 8, however I did spend time on this 2 weeks ago as it came up organically in study. 

## Content Insights

Child themes provide the flexibility to modify existing themes without directly altering the main theme files. This enables customization without permanently modifying the original design. Additionally, child themes allow edits to be preserved and unaffected by updates to the parent theme. In contrast, changes made directly to the original theme may be overwritten and lost when updates are applied. By utilizing a child theme, modifications are stored separately, ensuring that updates can still be applied to the main theme without compromising the customizations made by the user. This eliminates the need for users to worry about their changes being removed or having to decide whether to update the theme.


When making a child theme, please note the following:
- naming conventions {parent theme name} - child theme
Example: A child theme of the theme "Lukros" would become "Lukros - child".
- Download the original theme and make a copy 
- The following goes at the top of the theme withing functions.php:
    - Have this information at the top.
    -	Theme name:
    -	Theme URI:
    -	Description:
    -	Author:
    -	Author URI:
    -	Template: (name of parent theme)
    -	Version: 

- Contrary to what I thought, it is common for people to only use Functions.php to do CSS and not use styles.css. It is acceptable to use either. 
  
### Enqueue parent theme stylesheet
The following is required in the functions.php folder, this code ensures that the parent theme's stylesheet (style.css) is enqueued properly in the child theme, allowing the child theme to inherit styles from the parent theme
        -	add_action( 'wp_enqueue_scripts', 'my_custom_child_theme_enqueue_styles' );
        -	function my_custom_child_theme_enqueue_styles() {
        -	    wp_enqueue_style( 'parent-style', get_template_directory_uri() . '/style.css' );
        -	}


### Career/Employability/Learning Insights

Child themes are a core part in a web deisgners tool kit. It protects against updates and changes being reverted back. These are somethings I will be using in my upcoming project of making a website for a friends business. 
As a career I would not pursure web develop but perhaps use this as a side business. If this were to become a business, it would mix well with class CP3401 - e-strategic management to utilise SEO and marketing, providing an end to end, full solution for the client. 

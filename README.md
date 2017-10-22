# drupal_issue_2917192

this simple drupal module allow to reproduce Drupal core issue in https://www.drupal.org/node/2917192

Install Instructions : 

> Install Drupal 8.4 with profile standard
> download contrib module editor_advanced_link
> enabled this module


Reprodude the bug :

> create a basic page with "full html" as body format.
> inside ckeditor, add a link, open the "advanced" section. The checkbox "Open in new window" is not checked

> apply the patch provided and now the checkbox is checked...



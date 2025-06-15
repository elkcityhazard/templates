# A Collection Of Templates For Various Things

These templates are available for public use. A word of caution: they are
tailored to my needs so your mileage may vary.  

## WordPress

For local development, make sure to map your wp-content/* correctly.  Once
you deploy you can:

`docker cp ./wp-content project-wp:/var/www/html` and fix any permission
issues for file cleanup.  


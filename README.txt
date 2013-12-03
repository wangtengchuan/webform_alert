Description
-----------
This module works together with webform modules which provide an easy access
to creating and submitting an questionnaire and so on. 
The total submission limit function has already been included in the latest
version of  webform modules.
But some specific function are still excluded such as send an alert email to
the administrator to remind him the total submission is reaching its limit.

This modules tackle this two problems, 
1) when the total submission is reaching its limit, send an alert email to 
the administrator.
2) when the submission limit has been reached, close the webform.

One more thing we need to keep in mind is that the webfom modules reuse the
specific webform and store the submission data in one single database table,
so we have to figure out the specific submission data respect to each 
particular node.

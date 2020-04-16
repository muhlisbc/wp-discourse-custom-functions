# wp-discourse-custom-functions
Custom functions for the WP Discourse plugins to reformat the way replies are shown.

It does the following:

- Removes Discourse link previews (oneboxes) and images. Outputs a plain text link instead.
- Shortens content of Discourse replies below Wordpress posts. Outputs clean HTML where all cut off HTML elements are closed again.
- Add target="_blank" to the link in the end of the discussion
- Shows Discourse custom message for new created topics for new published posts
- Shows Discourse notification and link below posts when NO Replies are posted in forum
- Shows content of Discourse replies below post without the Participants section

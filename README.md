# WordPress auto-complete for Coda 2.5

This auto-complete mode for Coda 2.5 includes all __WordPress 4.0__ functions.

## Installation

* [Download the latest WordPress auto-complete mode.](https://github.com/tillkruess/Coda-WordPress-Mode/archive/codacompletion.zip)
* Unpack the downloaded Zip file.
* Open `WordPress Additions.codacompletion`.

This will automatically install the syntax mode to `~/Library/Application Support/Coda 2/Completions`.

## Changelog

### 1.1 (2014-08-25)

  - Added 29 new functions: `_update_posts_count_on_delete`, `_update_posts_count_on_transition_post_status`, `_wp_handle_upload`, `_wp_refresh_blog_details_on_updated_option`, `attachment_id3_data_meta_box`, `attachment_url_to_postid`, `get_comments_number_text`, `get_editor_stylesheets`, `is_customize_preview`, `post_form_autocomplete_off`, `wp_ajax_parse_embed`, `wp_ajax_parse_media_shortcode`, `wp_ajax_query_themes`, `wp_ajax_set_attachment_thumbnail`, `wp_destroy_all_sessions`, `wp_destroy_current_session`, `wp_destroy_other_sessions`, `wp_dropdown_languages`, `wp_embed_handler_youtube`, `wp_get_all_sessions`, `wp_get_attachment_id3_keys`, `wp_get_available_translations_from_api`, `wp_get_session_token`, `wp_install_download_language_pack`, `wp_install_language_form`, `wp_install_load_language`, `wp_spaces_regexp`, `wp_validate_boolean`, `wpview_media_sandbox_styles`
  - Added 1 WordPress "compat function": `hash_equals`
  - Removed 7 functions: `disabled`, `init`, `post_supports_thumbnails`, `theme_supports_thumbnails`, `wp`, `wp_get_playlist`, `wp_video_playlist_shortcode`
  - Removed 5 WordPress "compat functions": `hash_hmac`, `json_decode`, `json_encode`, `mb_substr`, `stripos`  

### 1.0 (2014-03-25)

  - Initial release

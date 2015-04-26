# WordPress auto-complete for Coda 2.5

This auto-complete mode for Coda 2.5 includes all __WordPress 4.2__ functions and constants.

## Installation

* [Download the latest WordPress auto-complete mode release.](https://github.com/tillkruess/Coda-WordPress-Mode/archive/1.3.zip)
* Unpack the downloaded Zip file.
* Open `WordPress Additions.codacompletion`.

This will automatically install the syntax mode to `~/Library/Application Support/Coda 2/Completions`.

## Changelog

### 1.3 (2015-04-26)

  - Added 20 functions: `_mb_strlen()`, `_split_shared_term()`, `_wp_check_split_default_terms()`, `_wp_check_split_terms_in_menus()`, `_wp_posts_page_notice()`, `_wp_sanitize_utf8_in_redirect()`, `_wp_scripts_maybe_doing_it_wrong()`, `customize_themes_print_templates()`, `get_avatar_data()`, `get_avatar_url()`, `has_header_image()`, `maybe_convert_table_to_utf8mb4()`, `mb_strlen()`, `options_discussion_add_js()`, `print_emoji_detection_script()`, `upgrade_420()`, `wp_admin_canonical_url()`, `wp_ajax_press_this_add_category()`, `wp_ajax_press_this_save_post()`, `wp_ajax_update_plugin()`, `wp_attachment_is()`, `wp_delete_file()`, `wp_edit_attachments_query_vars()`, `wp_encode_emoji()`, `wp_get_split_term()`, `wp_get_split_terms()`, `wp_install_maybe_enable_pretty_permalinks()`, `wp_media_attach_action()`, `wp_print_request_filesystem_credentials_modal()`, `wp_script_add_data()`, `wp_scripts()`, `wp_staticize_emoji()`, `wp_staticize_emoji_for_email()`, `wp_styles()`
  - Removed 1 function: `get_images_from_uri()`
  
### 1.2.1 (2014-12-18)

  - Removed leading underscore from: `_wp_clear_update_cache()`, `_wp_get_password_hint()`

### 1.2 (2014-12-15)

  - Added 145 constants
  - Added 20 functions: `_navigation_markup()`, `_wp_clear_update_cache()`, `_wp_get_password_hint()`, `_wp_json_convert_string()`, `_wp_json_sanity_check()`, `_wp_render_title_tag()`, `get_the_archive_description()`, `get_the_archive_title()`, `get_the_post_navigation()`, `get_the_posts_navigation()`, `get_the_posts_pagination()`, `network_settings_add_js()`, `the_archive_description()`, `the_archive_title()`, `the_post_navigation()`, `the_posts_navigation()`, `the_posts_pagination()`, `wp_ajax_destroy_sessions()`, `wp_json_encode()`, `wp_print_revision_templates()`
  - Removed 1 function: `admin_created_user_subject()`

### 1.1.1 (2014-09-04)

  - Added 7 functions: `disabled()`, `translations_api()`, `upgrade_400()`, `wp()`, `wp_can_install_language_pack()`, `wp_download_language_pack()`, `wp_get_available_translations()`
  - Removed 4 functions: `_wp_refresh_blog_details_on_updated_option()`, `wp_get_available_translations_from_api()`, `wp_install_download_language_pack()`, `wp_install_load_language()`

### 1.1 (2014-08-25)

  - Added 29 functions: `_update_posts_count_on_delete()`, `_update_posts_count_on_transition_post_status()`, `_wp_handle_upload()`, `_wp_refresh_blog_details_on_updated_option()`, `attachment_id3_data_meta_box()`, `attachment_url_to_postid()`, `get_comments_number_text()`, `get_editor_stylesheets()`, `is_customize_preview()`, `post_form_autocomplete_off()`, `wp_ajax_parse_embed()`, `wp_ajax_parse_media_shortcode()`, `wp_ajax_query_themes()`, `wp_ajax_set_attachment_thumbnail()`, `wp_destroy_all_sessions()`, `wp_destroy_current_session()`, `wp_destroy_other_sessions()`, `wp_dropdown_languages()`, `wp_embed_handler_youtube()`, `wp_get_all_sessions()`, `wp_get_attachment_id3_keys()`, `wp_get_available_translations_from_api()`, `wp_get_session_token()`, `wp_install_download_language_pack()`, `wp_install_language_form()`, `wp_install_load_language()`, `wp_spaces_regexp()`, `wp_validate_boolean()`, `wpview_media_sandbox_styles()`
  - Added 1 WordPress "compat function": `hash_equals()`
  - Removed 7 functions: `disabled()`, `init()`, `post_supports_thumbnails()`, `theme_supports_thumbnails()`, `wp()`, `wp_get_playlist()`, `wp_video_playlist_shortcode()`
  - Removed 5 WordPress "compat functions": `hash_hmac()`, `json_decode()`, `json_encode()`, `mb_substr()`, `stripos()`

### 1.0 (2014-03-25)

  - Initial release

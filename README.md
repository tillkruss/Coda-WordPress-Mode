# WordPress auto-complete for Coda 2.5

This auto-complete mode for Coda 2.5 includes all __WordPress 4.5__ functions and constants.

## Installation

* [Download the latest WordPress auto-complete mode release.](https://github.com/tillkruess/Coda-WordPress-Mode/archive/1.6.zip)
* Unpack the downloaded Zip file.
* Open `WordPress Additions.codacompletion`.

This will automatically install the syntax mode to `~/Library/Application Support/Coda 2/Completions`.

## Changelog

### 1.6 (2016-04-14)
  - Added WordPress 4.5 functions/constants

### 1.5 (2016-01-06)

  - Added 125 functions: `_get_wptexturize_shortcode_regex`, `_get_wptexturize_split_regex`, `_oembed_create_xml`, `_oembed_filter_feed_content`, `_oembed_rest_pre_serve_request`, `_prime_comment_caches`, `_upgrade_440_force_deactivate_incompatible_plugins`, `_wp_batch_split_terms`, `_wp_check_for_scheduled_split_terms`, `_wp_check_split_nav_menu_terms`, `_wp_get_attachment_relative_path`, `_wp_get_image_size_from_meta`, `_wp_get_post_revision_version`, `_wp_json_prepare_data`, `_wp_upload_dir_baseurl`, `add_network_option`, `add_term_meta`, `delete_network_option`, `delete_term_meta`, `enqueue_embed_scripts`, `get_file`, `get_header_image_tag`, `get_html_split_regex`, `get_network_option`, `get_oembed_endpoint_url`, `get_oembed_response_data`, `get_oembed_response_data_rich`, `get_password_reset_key`, `get_post_embed_html`, `get_post_embed_url`, `get_preview_post_link`, `get_rest_url`, `get_shortcode_atts_regex`, `get_subdirectory_reserved_names`, `get_term_meta`, `get_the_author_posts_link`, `get_the_comments_navigation`, `get_the_comments_pagination`, `get_the_post_thumbnail_url`, `is_embed`, `is_post_type_viewable`, `is_registered_sidebar`, `json_last_error_msg`, `map_deep`, `mysql_to_rfc3339`, `print_embed_comments_button`, `print_embed_scripts`, `print_embed_sharing_button`, `print_embed_sharing_dialog`, `print_embed_styles`, `random_bytes`, `random_int`, `randomcompat_intval`, `randomcompat_strlen`, `randomcompat_substr`, `register_rest_route`, `rest_api_default_filters`, `rest_api_init`, `rest_api_loaded`, `rest_api_register_rewrites`, `rest_cookie_check_errors`, `rest_cookie_collect_status`, `rest_do_request`, `rest_ensure_request`, `rest_ensure_response`, `rest_get_date_with_gmt`, `rest_get_url_prefix`, `rest_handle_deprecated_argument`, `rest_handle_deprecated_function`, `rest_handle_options_request`, `rest_output_link_header`, `rest_output_link_wp_head`, `rest_output_rsd`, `rest_parse_date`, `rest_send_allow_header`, `rest_send_cors_headers`, `rest_url`, `signup_get_available_languages`, `strip_fragment_from_url`, `strip_shortcode_tag`, `stripslashes_from_strings_only`, `the_comments_navigation`, `the_comments_pagination`, `the_excerpt_embed`, `the_header_image_tag`, `the_post_thumbnail_url`, `update_network_option`, `update_term_meta`, `update_termmeta_cache`, `upgrade_431`, `upgrade_440`, `urldecode_deep`, `wp_ajax_delete_inactive_widgets`, `wp_ajax_generate_password`, `wp_ajax_save_wporg_username`, `wp_calculate_image_sizes`, `wp_calculate_image_srcset`, `wp_embed_excerpt_attachment`, `wp_embed_excerpt_more`, `wp_filter_oembed_result`, `wp_get_attachment_image_sizes`, `wp_get_attachment_image_srcset`, `wp_get_attachment_image_url`, `wp_get_document_title`, `wp_get_server_protocol`, `wp_get_users_with_no_role`, `wp_handle_comment_submission`, `wp_image_add_srcset_and_sizes`, `wp_installing`, `wp_is_numeric_array`, `wp_make_content_images_responsive`, `wp_maybe_decline_date`, `wp_new_comment_notify_moderator`, `wp_new_comment_notify_postauthor`, `wp_oembed_add_discovery_links`, `wp_oembed_add_host_js`, `wp_oembed_ensure_format`, `wp_oembed_register_route`, `wp_parse_url`, `wp_remote_retrieve_cookie`, `wp_remote_retrieve_cookie_value`, `wp_remote_retrieve_cookies`, `wp_removable_query_args`, `wp_send_new_user_notifications`, `wp_term_is_shared`
  - Remove 1 function: `split_all_shared_terms`
  - Added 9 constants: `GB_IN_BYTES`, `KB_IN_BYTES`, `MB_IN_BYTES`, `MONTH_IN_SECONDS`, `RANDOM_COMPAT_READ_BUFFER`, `REST_API_VERSION`, `REST_REQUEST`, `TB_IN_BYTES`, `WP_JSON_SERIALIZE_COMPATIBLE`

### 1.4 (2015-08-08)

  - Added 34 functions: `_deprecated_constructor`, `_upgrade_422_find_genericons_files_in_folder`, `_upgrade_422_remove_genericons`, `_wp_can_use_pcre_u`, `atom_site_icon`, `convert_invalid_entities`, `do_shortcodes_in_html_tags`, `format_for_editor`, `get_default_comment_status`, `get_language_attributes`, `get_main_network_id`, `get_singular_template`, `get_site_icon_url`, `has_site_icon`, `rss2_site_icon`, `site_icon_url`, `split_all_shared_terms`, `unescape_invalid_shortcodes`, `upgrade_430`, `upgrade_430_fix_comments`, `wp_admin_bar_customize_menu`, `wp_ajax_crop_image`, `wp_html_split`, `wp_kses_attr_check`, `wp_kses_attr_parse`, `wp_kses_hair_parse`, `wp_kses_one_attr`, `wp_post_preview_js`, `wp_replace_in_html_tags`, `wp_resolve_numeric_slug_conflicts`, `wp_roles`, `wp_should_upgrade_global_tables`, `wp_site_icon`, `wptexturize_primes`
  - Added 1 constant: `WP_FEATURE_BETTER_PASSWORDS` 
  - Updated many function parameters
  
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

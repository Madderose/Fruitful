# fruitful_get_theme_options()

> God node · 27 connections · [C:\Users\hoppj\SynologyDrive\- Expertise\- Web\WordPress\Themes\Fruitful\Fruitful\inc\func\fruitful-function.php](file:///C:/Users/hoppj/SynologyDrive/-%20Expertise/-%20Web/WordPress/Themes/Fruitful/Fruitful/inc/func/fruitful-function.php#L319)

## Call Trace Diagram

```mermaid
sequenceDiagram
    participant P0 as fruitful_get_theme_options()
    participant P1 as .get_option()
    participant P2 as .process_bulk_actions()
    participant P3 as .can_plugin_activate()
    participant P4 as .is_plugin_installed()
    participant P5 as .does_plugin_have_update()
    participant P6 as .get_tgmpa_url()
    participant P7 as .prepare_items()
    participant P8 as .update_option()
    participant P9 as .install_plugins_page()
    participant P10 as .can_plugin_update()
    participant P11 as .get_download_url()
    participant P12 as .inject_update_info()
    participant P13 as fruitful_get_sliders()
    participant P14 as fruitful_get_content_with_custom_sidebar()
    participant P15 as fruitful_get_slider_layout_flex()
    participant P16 as fruitful_get_slider_layout_nivo()
    participant P17 as fruitful_custom_do_settings_sections()
    participant P18 as fruitful_slider_images()
    participant P19 as fruitful_scripts()
    participant P20 as fruitful_get_slider()
    participant P21 as fruitful_loop_shop_per_page()
    participant P22 as fruitful_is_latest_posts_page()
    participant P23 as fruitful_new_slide()
    participant P24 as .timezone_string()
    participant P25 as ed_metabox_include_front_page()
    participant P26 as fruitful_get_responsive_style()
    participant P27 as fruitful_get_woo_sidebar()
    participant P28 as fruitful_add_custom_fonts()
    participant P29 as fruitful_get_footer_text()
    participant P30 as .display_field()
    participant P31 as fruitful_get_default_array()
    participant P32 as fruitful_thumbnail_size()
    participant P33 as fruitful_get_cart_button_html()
    participant P34 as fruitful_get_logo()
    participant P35 as fruitful_get_favicon()
    participant P36 as fruitful_is_social_header()
    participant P37 as fruitful_get_socials_icon()
    participant P38 as fruitful_state_post_comment()
    participant P39 as fruitful_state_page_comment()
    participant P40 as fruitful_loop_columns()
    participant P41 as fruitful_get_languages_list()
    participant P42 as fruitful_body_classes()
    participant P43 as .register_settings()
    P0->>+ P1: calls
    P1-->>- P0: return
    P1->>+ P0: calls
    P0-->>- P1: return
    P1->>+ P2: calls
    P2-->>- P1: return
    P2->>+ P1: calls
    P1-->>- P2: return
    P2->>+ P3: calls
    P3-->>- P2: return
    P2->>+ P4: calls
    P4-->>- P2: return
    P2->>+ P5: calls
    P5-->>- P2: return
    P2->>+ P6: calls
    P6-->>- P2: return
    P2->>+ P7: calls
    P7-->>- P2: return
    P2->>+ P8: calls
    P8-->>- P2: return
    P2->>+ P9: calls
    P9-->>- P2: return
    P2->>+ P10: calls
    P10-->>- P2: return
    P2->>+ P11: calls
    P11-->>- P2: return
    P2->>+ P12: calls
    P12-->>- P2: return
    P1->>+ P13: calls
    P13-->>- P1: return
    P1->>+ P14: calls
    P14-->>- P1: return
    P1->>+ P15: calls
    P15-->>- P1: return
    P1->>+ P16: calls
    P16-->>- P1: return
    P1->>+ P17: calls
    P17-->>- P1: return
    P1->>+ P18: calls
    P18-->>- P1: return
    P1->>+ P19: calls
    P19-->>- P1: return
    P1->>+ P20: calls
    P20-->>- P1: return
    P1->>+ P21: calls
    P21-->>- P1: return
    P1->>+ P22: calls
    P22-->>- P1: return
    P1->>+ P23: calls
    P23-->>- P1: return
    P1->>+ P24: calls
    P24-->>- P1: return
    P1->>+ P25: calls
    P25-->>- P1: return
    P0->>+ P13: calls
    P13-->>- P0: return
    P0->>+ P26: calls
    P26-->>- P0: return
    P0->>+ P27: calls
    P27-->>- P0: return
    P0->>+ P14: calls
    P14-->>- P0: return
    P0->>+ P28: calls
    P28-->>- P0: return
    P0->>+ P15: calls
    P15-->>- P0: return
    P0->>+ P16: calls
    P16-->>- P0: return
    P0->>+ P19: calls
    P19-->>- P0: return
    P0->>+ P20: calls
    P20-->>- P0: return
    P0->>+ P29: calls
    P29-->>- P0: return
    P0->>+ P21: calls
    P21-->>- P0: return
    P0->>+ P30: calls
    P30-->>- P0: return
    P0->>+ P31: calls
    P31-->>- P0: return
    P0->>+ P32: calls
    P32-->>- P0: return
    P0->>+ P33: calls
    P33-->>- P0: return
    P0->>+ P34: calls
    P34-->>- P0: return
    P0->>+ P35: calls
    P35-->>- P0: return
    P0->>+ P36: calls
    P36-->>- P0: return
    P0->>+ P37: calls
    P37-->>- P0: return
    P0->>+ P38: calls
    P38-->>- P0: return
    P0->>+ P39: calls
    P39-->>- P0: return
    P0->>+ P40: calls
    P40-->>- P0: return
    P0->>+ P41: calls
    P41-->>- P0: return
    P0->>+ P42: calls
    P42-->>- P0: return
    P0->>+ P43: calls
    P43-->>- P0: return
```

## Connections by Relation

### calls
- [[.get_option()]] `INFERRED`
- [[fruitful_get_sliders()]] `INFERRED`
- [[fruitful_get_responsive_style()]] `INFERRED`
- [[fruitful_get_woo_sidebar()]] `INFERRED`
- [[fruitful_get_content_with_custom_sidebar()]] `INFERRED`
- [[fruitful_add_custom_fonts()]] `INFERRED`
- [[fruitful_get_slider_layout_flex()]] `INFERRED`
- [[fruitful_get_slider_layout_nivo()]] `INFERRED`
- [[fruitful_scripts()]] `INFERRED`
- [[fruitful_get_slider()]] `INFERRED`
- [[fruitful_get_footer_text()]] `INFERRED`
- [[fruitful_loop_shop_per_page()]] `INFERRED`
- [[.display_field()]] `INFERRED`
- [[fruitful_get_default_array()]] `EXTRACTED`
- [[fruitful_thumbnail_size()]] `INFERRED`
- [[fruitful_get_cart_button_html()]] `INFERRED`
- [[fruitful_get_logo()]] `INFERRED`
- [[fruitful_get_favicon()]] `INFERRED`
- [[fruitful_is_social_header()]] `INFERRED`
- [[fruitful_get_socials_icon()]] `INFERRED`

### contains
- [[fruitful-function.php]] `EXTRACTED`

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*
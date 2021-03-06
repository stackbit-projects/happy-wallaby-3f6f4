---
title: Blog
sections:
  - type: hero_section
    title: Blog rédactrice web SEO
    subtitle: >-
      Chaque semaines, retrouvez mes conseils et stratégies qui fonctionnent
      pour bâtir et optimiser votre contenu sur le web.
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
    image: images/Windows-pana.png
    media_position: right
    actions:
      - label: S'abonner
        url: 'https://happy-wallaby-3f6f4.netlify.app/blog/#newsletterform'
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: true
        type: action
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: Inscrivez-vous
    title_align: center
    content: >-
      <a name="newsletter"></a>Pour ne pas louper un seul article, abonne-toi à
      ma newsletter !
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: newsletterform
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse mail
        is_required: true
    submit_label: S'abonner
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
seo:
  title: Blog
  description: >-
    Vous souhaitez être en constante veille informationnelle sur le marketing
    digitale ? Je vous promets des articles passionnant.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Blog
      keyName: property
    - name: 'og:description'
      value: This is the blog page
      keyName: property
    - name: 'og:image'
      value: images/classic/post-5.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Blog
    - name: 'twitter:description'
      value: This is the blog page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
template: advanced
---

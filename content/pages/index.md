---
title: Home
layout: PageLayout
sections:
  - type: FeaturedPostsSection
    elementId: ''
    showDate: true
    showAuthor: true
    showExcerpt: true
    variant: variant-b
    actions:
      - type: Button
        label: View All
        altText: View All Posts
        url: /blog
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-1
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    title: Featured
    subtitle: Featured blog posts section example
    colors: colors-h
    posts:
      - content/pages/blog/issue-01.md
---

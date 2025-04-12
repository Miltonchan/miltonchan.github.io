---
# # Page title
# title: Publications
# # Page type - we want a landing page (such as a homepage)
# type: landing

# # Your landing page sections - add as many different content blocks as you like
# sections:
#   - block: markdown
#     id: section-1
#     content: 
#       title: Generative AI Curriculum Introductory Brochure
#       subtitle: This work is conducted under the CUHK Jockey Club AI for the Future Project
#       text: A supplementary chapter of pre-tertiary AI education framework on Generative AI for Hong Kong
#   - block: markdown
#     id: section-2
#     content:
#       title:  
#       subtitle: This work is conducted under the CUHK Jockey Club AI for the Future Project
#       text: 

title: Publications
type: landing
sections:
- block: features
  content:
    title: Publications
    items:
    - name: Generative AI Curriculum Introductory Brochure
      description: .[Read more](https://cuhkjc-aiforfuture.hk/index.php/en/aibrochure/)

# - block: features
#   content:
#     title: Newspaper Articles
#     items:
#     - name: Article 1 Title
#       description: Summary of Article 1. [Read more](/publication/article1)
#       image: /images/article1.jpg
#     - name: Article 2 Title
#       description: Summary of Article 2. [Read more](/publication/article2)
#       image: /images/article2.jpg
- block: markdown
  id: section-1
  content:
    title: Section 1
    subtitle: A subtitle
    text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    # Display content from the `content/post/` folder
    filters:
      folders:
        - post
  design:
    # Choose how many columns the section has. Valid values: '1' or '2'.
    columns: '1'
    # Choose your content listing view - here we use the `showcase` view
    view: compact
---
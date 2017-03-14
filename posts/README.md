# How to write a post

1. Click `Create new file` on this page
2. Give the file a name
    * Names should start with date and end with the post title `YYYY-MM-DD-put-descriptive-title-here`
    * Names must be unique - they determine the final URL of the post
    * Do not use special characters in file name (no ÆØÅ or symbols except - or _ ).
3. Copy this template to file contents
  ```
  ---
  published: false
  title: The post title
  description: The story behind the name "Eyr" and it's origin in Norse mythology.
  language: en
  date: 2017-01-13
  image: https://res.cloudinary.com/eyr/image/upload/v1489423171/1-lIma_Lenndfa30XaIPQ9iw_k4amqf.jpg
  image_desc: Menglad surrounded by her nine maidens including Eir
  ---
  
  paste_post_content_here
  ```
4. Edit the metadata
    * Keep published to false in order to preview the post without actually setting it live (it might still be indexed by search engines).
    * If you want to add a header image you should sign in to our Cloudinary and upload an image. Remember to copy the `https` link and not just `http`.
    * The image_desc doubles as the image alt text.
5. Replace `paste_post_content_here` with the markdown formatted post.
    * Markdown also supports HTML so it's possible to add embedded HTML (such as YouTube videos) or HTML styling.

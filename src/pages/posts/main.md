---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 12 Sep 2021
name: Mohamed Ehab
value: 128
description: Just a Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Hello Guys, How are you ?

# What is this?
This is a repo that you must fork in order to have your own blog.
The blog you will generate after forking this repo supports traditional Markdown *(.md)*, MDX *(.mdx)* and Google Collab *(.ipynb)* posts.

# Installation

Just fork this repository.

# How to use it.

Just upload *(or create)* .md, .mdx or .ipynb files and the blog will automatically be updated with the new content.

# How it works?

For this example, assume the blog root path to be **myuser.github.io/MyBlog/**

When you upload *(or create)* a file, there are two options.

1. The file is name as **page**
   - In this case, the entry will be posted as the name of the folder containing the file. Ex: Let the new file be **MyMarkdownPost/page.mdx**, then you will find your article posted at **myuser.github.io/MyBlog/MyMarkdownPost/**
2. The file name is not **page**
   - In this case, the entry will be posted as the name of the file itself. Ex: Let the new file be **MyMarkdownPost/MyPost.ipynb**, then you will find your article posted at **myuser.github.io/MyBlog/MyMarkdownPost/MyPost/**

After you commit the changes, GitHub Actions take care of all the work, and you can enjoy your nice blog <3

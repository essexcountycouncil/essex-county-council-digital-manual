## Essex County Council Digital Manual

### Preview environments

If you want to preview changes before they go live:

- Fork the repository to your own account
- In the forked repository, go to **Settings**-**Pages** and enable Pages from the `master` branch
- Still in **Settings**, go to the **Environments** tab
- Click **github-pages**
- Scroll down to the **Environment secrets** section
- Click **Add Secret**
- Under **Name**, enter `JEKYLL_ENV`
- Under **Value**, enter `development`

This will ensure that Google doesn't index your preview copy of the site.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JackRyan8/TestingPages/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

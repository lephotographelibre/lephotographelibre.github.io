## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/lephotographelibre/lephotographelibre.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lephotographelibre/lephotographelibre.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


===================== JM Process ==========================

Start Git Bash.
Configure Git to disable SSL, if necessary.

git config --global http.sslVerify false

Configure the proxy server, if necessary.
git config --global http.proxy http://www.testproxyserver.com:80/

git config --global user.email "lephotographelibre@yahoo.com"
git config --global user.name "lephotographelibre"


Navigate to the directory where you want to clone the Git cloud repository.
Clone the Git cloud repository using the desired protocol.
git clone https://github.com/lephotographelibre/lephotographelibre.github.io.git

Copy the application files to the cloned repository directory.

Use the git add command to add new files to the cloned repository.
git add workflow.sh

Commit all files to the cloned Git repository.
git commit -a -m "v1.0.3- Normalise et renomme fichiers source .jpg en .JPG"

Push the transaction to the Git cloud repository.
git push origin master
Username for 'https://github.com': lephotographelibre@yahoo.com
Password for 'https://lephotographelibre@yahoo.com@github.com': *********

Enter exit to close the Git Bash prompt.

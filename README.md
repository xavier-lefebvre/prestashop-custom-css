# Prestashop custom CSS (for the classic theme)

## Child Theme

### Create a child theme

It's simple : in "your_Prestashop_root/themes/", create a folder for your child theme. 

Then inside "your_child_theme/", create a config folder.
In this config folder, make a file named "theme.yml"


an example of what to put in this file
```
parent: classic
name: child_classic
display-name: Child-theme of classic theme
version: 1.0.0
assets:
    use_parent_assets: true
```

### Modify template

In "your_child_theme/", create a folder named "template"  
Copy and paste your template in "your_child_theme/template" from "your_parent_theme/template"  
In this repository, i duplicate and customize the homepage, "index.tpl"

In this file, you can paste or duplicate blocks, or write html

### Customize css

For custom css, in "your_child_theme/", create a folder named "assets", then inside him, another folder named "css"  
Put your "custom.css" inside "your_child_theme/assets/css/"

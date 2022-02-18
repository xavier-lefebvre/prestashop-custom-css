<<<<<<< HEAD
<html>
<h1>Prestashop custom CSS (for the classic theme)</h1>
=======
# Prestashop custom CSS (for the classic theme)
>>>>>>> 8f4124f0c8805f044664f085b3f6bf8cb626e9f8

## Child Theme

### Create a child theme

It's simple : in "your_Prestashop_root/themes/", create a folder for your child theme. 

Then inside "your_child_theme/", create a config folder.
In this config folder, make a file named "theme.yml"

<<<<<<< HEAD
<p>Then inside "your_child_theme/", create a config folder</p>
<p>In this config folder, make a file named "theme.yml"</p>
</html>
=======

>>>>>>> 8f4124f0c8805f044664f085b3f6bf8cb626e9f8
an example of what to put in this file
```
parent: classic
name: child_classic
display-name: Child-theme of classic theme
version: 1.0.0
assets:
    use_parent_assets: true
```
<<<<<<< HEAD
<html>
<h3>Modify template</h3>
=======

### Modify template

In "your_child_theme/", create a folder named "template"  
Copy and paste your template in "your_child_theme/template" from "your_parent_theme/template"  
In this repository, i duplicate and customize the homepage, "index.tpl"
>>>>>>> 8f4124f0c8805f044664f085b3f6bf8cb626e9f8

In this file, you can paste or duplicate blocks, or write html

### Customize css

For custom css, in "your_child_theme/", create a folder named "assets", then inside him, another folder named "css"  
Put your "custom.css" inside "your_child_theme/assets/css/"

<<<<<<< HEAD
<p>For custom css, in "<span style="color:blue">your_child_theme/</span>", create a folder named "<span style="color:blue">assets</span>", then inside him, another folder named "<span style="color:blue">css</span>"</p>
<p>Put your "<span style="color:yellow">custom.css</span>" inside "<span style="color:blue">your_child_theme/assets/css/</span>"</p>
</html>
=======
>>>>>>> 8f4124f0c8805f044664f085b3f6bf8cb626e9f8

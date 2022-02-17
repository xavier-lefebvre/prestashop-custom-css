
<h1>Prestashop custom CSS (for the classic theme)</h1>

<h2>Child Theme</h2>

<h3>Create a child theme</h3>

<p>It's simple : in "your_Prestashop_root/themes/", create a folder for your child theme. </p>

<p>Then inside "your_child_theme/", create a config folder</p>
<p>In this config folder, make a file named "theme.yml"</p>


an example of what to put in this file
```
parent: classic
name: child_classic
display-name: Child-theme of classic theme
version: 1.0.0
assets:
    use_parent_assets: true
```
<html>
<h3>Modify template</h3>

<p>In "<span style="color:blue">your_child_theme/</span>", create a folder named "<span style="color:blue">template</span>"</p>
<p>Copy and paste your template in "<span style="color:blue">your_child_theme/template</span>" from "<span style="color:blue">your_parent_theme/template</span>"</p>
<p>In this repository, i duplicate and customize the homepage, "<span style="color:yellow">index.tpl</span>"</p>

<p>In this file, you can paste or duplicate blocks, or write html<p>

<h3>Customize css</h3>

<p>For custom css, in "<span style="color:blue">your_child_theme/</span>", create a folder named "<span style="color:blue">assets</span>", then inside him, another folder named "<span style="color:blue">css</span>"</p>
<p>Put your "<span style="color:yellow">custom.css</span>" inside "<span style="color:blue">your_child_theme/assets/css/</span>"</p>
</html>

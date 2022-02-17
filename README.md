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

<h3>Modify template</h3>

<p>In "your_child_theme/", create a folder named "template"</p>
<p>Copy and paste your template in "your_child_theme/template" from "your_parent_theme/template"</p>
<p>In this repository, i duplicate and customize the homepage, "index.tpl"</p>

<p>In this file, you can paste or duplicate blocks, or write html<p>

<h3>Custom css</h3>

<p>For custom css, in "your_child_theme/", create a folder named "assets", then inside him, another folder named "css"</p>
<p>Put your "custom.css" inside "your_child_theme/assets/css/"</p>
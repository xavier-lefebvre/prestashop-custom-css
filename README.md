<h1>Prestashop custom CSS</h1>

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
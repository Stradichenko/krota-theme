# Krota-theme
This is the open repository for the template of [krotanote.xyz](https://www.krotanote.xyz) website.
This template is rendered using HUGO.

## Philosphy and _raison d'être_

### Theme
The theme is inspired in Edward Tufte, the Zettelkasten system and Gwerns' blog. There are three colorschemes thought to diversify aesthetic while reading. These are inspired by, as their name imply:  
...


## Getting started
```bash
hugo new site YOURBLOG
cd YOURBLOG
git clone https://github.com/Stradichenko/krota-template themes/krota-theme
echo "theme = 'krota-theme'" >> config.toml # Append a line to the site configuration file, indicating the current theme.
cp themes/krota-theme/style.css static/
hugo server
```

## [template-structure](/template-structure.md)

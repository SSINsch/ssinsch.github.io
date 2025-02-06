# README
Based on...
- Chester How's tale-theme(https://github.com/chesterhow/tale)
- KyeongSeob Sim's AP(https://github.com/kssim/ap)  


## Structure
* Here are the main files of the template
```bash
ap
├── _includes                  # theme includes
├── _layouts                   # theme layouts (see below for details)
├── _posts                     # Project & Portfolio posts
├── _sass                      # Sass partials 
├── portfolio                  # Main page for "portfolio"
├── assets
|  ├── css                     # font-awesome and main css
|  ├── fonts                   # Font-Awesome
|  ├── favicon.ico             # Favicon
|  └── img                     # Images used for "about" page
├── _config.yml                # sample configuration
└── index.md                   # Resume to show on "about" page
```

## Portfolio Schema
```markdown
---
layout: post
title:  [Project title to show in portfolio list]
info: [A brief introduction to show in portfolio list]
tech: [The technologies used in the project to show in portfolio list]
type: [Property of the project to be displayed in front of the project's info(toy or company name)]
---
```

## License
[The MIT License (MIT)](https://raw.githubusercontent.com/kssim/ap/master/LICENSE)

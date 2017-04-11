---
title: Site Design Settings
layout: post
categories: settings
description: Changing the main site settings
type: Document
---

This file allows you to change some of the look and feel settings of your site.

**Warning:** Just because you **can** do this, doesn't mean you **should.**  Most of the time, it's a best practice to just set this stuff up and then leave it alone.

Here are the options:

## Colors

```yaml
main_dark_color:
main_light_color: 
main_bright_color: 
secondary_bright_color: 
```
These control your sites colors.  If you want to change a color, the one to change that will have the biggest impact on how your site looks (with the least chance of making it look bad) is `main_bright_color`.

## Fonts

```yaml
main_font: "'Lora', serif"
main_font_import_code: "@import url('https://fonts.googleapis.com/css?family=Antic');"
secondary_font: "'Antic', sans-serif"
secondary_font_import_code: 
```

These settings control your fonts.  You can use any fonts from [Google Fonts](fonts.google.com).  Just be sure to follow the instructions given about the format of the codes.  A misplaced semicolon here can break your site.


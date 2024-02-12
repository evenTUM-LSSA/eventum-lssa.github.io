---
title: Color Theme
layout: default
parent: Frontend
nav_order: 2
---

The color theme is loosely orientated at the [TUM color theme](https://portal.mytum.de/corporatedesign/index_html/stylesweb/index_farben) and generated a bigger range of colors with [eva design](https://colors.eva.design/).

You can manipulate the color theme in two places:
1. Switch between dark and light mode in the entry file `App.tsx`
    - change the parameter `theme` of the Applicationprovider to a fitting design. (Defaults are `eva.light` and `eva.dark`)
2. Switch the color distribution in `styles/colortheme.json`
    - for more explanation and customizability please refer to the [UI Kitten docs](https://akveo.github.io/react-native-ui-kitten/docs/guides/branding)


# Theme: modified Catbook
Thanks to [Catbook](https://github.com/starry99/catbook) for a lovely base theme

Useful (taken from original Catbook):
## Make it yours

If you want to create a new category, you need to create `*name*.html` in the `categories` folder. And add the following content:
```html
---
layout: page
type: *name*
---

{% include archive.html %}
```
Then the number of pages in the category will be displayed.

## License

[MIT License](https://opensource.org/licenses/MIT)

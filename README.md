## MD Composer Extras

Add some formatting option in your Discourse composer : underline, strikethrough, superscript, subscript, center, align right, justify , float left, float right, and columns.

The CSS for columns and floats is disabled on mobile. By default on mobile columns and float will appear as single column content. The missing CSS can be added in again manually.

## Columns and Floats

When using columns and floats, note that the text will autobreak once an appropriate amount of content has been placed in the second column or to the side of the float.

Columns have a CSS border to for ease of viewing.

A column is broken by placing `[/wrap]` at the end of the first column's content.

**Column Example**

Place the following in your editor to see how columns work.

```
Test

[wrap="columns"]
1
2
3
[/wrap]
1
2
3

Test
```

For more informations, see : 

- English : https://meta.discourse.org/t/md-composer-extras/118912
- Français : https://www.mon-discourse.fr/themes/md-composer-extras/

## Credits

Wrap support by thw26 : https://github.com/thw26

<br>

I took some parts of the Iconified Header Links and Slick Image Gallery theme components made by Johani : 

https://meta.discourse.org/t/iconified-header-links/86307 (adding fa5 icons in the theme component)
https://meta.discourse.org/t/slick-image-gallery/81952 (manager the translations inside the theme component)

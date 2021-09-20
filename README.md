# hugo-mods: examples

Placeholders and example assets for hugo-mods example sites.

## Usage

### Texts

In a shortcode, generate 10 lorem ipsum paragraphs:

```
{{< lorem 10 >}}
```

### Images

Load image showing the alps as resource, e.g.:

```
<img src="{{ (resources.Get "images/alps.jpg").Permalink }}">
```

<img alt="Creative Commons License" align="right" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png"/>

All files in the [assets/images](./assets/images) directory are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

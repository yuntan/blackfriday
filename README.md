# yuntan/blackfriday
Markdown to HTML converter for [SyaroNote](https://github.com/OUCC/SyaroNote)

Forked from russross/blackfriday

## Features
### Math `EXTENSION_LATEX_MATH`
LaTeX inline and display math surrounded by `$` or `$$`.

```markdown
sample $x^y_z$ text _emphasis_

$$ x^y_z = X^Y_Z $$
```

```html
<p>sample \(x^y_z\) text <em>emphasis</em></p>

<p>\[ x^y_z = X^Y_Z \]</p>
```

### Task list
```markdown
- [ ] checkbox
- [X] checked
```

```html
<ul>
<li class="tasklist-item"><input type="checkbox" disabled><label>checkbox</label></li>
<li class="tasklist-item"><input type="checkbox" checked disabled><label>checked</label></li>
</ul>

```

### Figure `HTML_IMAGES_AS_FIGURE`
```markdown
![image caption](pass/to/image)
```

```html
<p><figure><img src="pass/to/image" alt="image caption"><figcaption>image caption</figcaption></figure></p>
```

### WikiLink `EXTENSION_WIKI_LINK`
```markdown
[[WikiLink]] [normal link](http://google.co.jp)

* [Home](/)
* [[Sample Page]]
```

```html
<p><a href="WikiLink">WikiLink</a> <a href="http://google.co.jp" target="_blank">normal link</a></p>

<ul>
<li><a href="/">Home</a></li>
<li><a href="Sample Page">Sample Page</a></li>
</ul>
```

## License
[Blackfriday is distributed under the Simplified BSD License](LICENSE.txt)

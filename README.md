# yuntan/blackfriday
Markdown to HTML converter for [SyaroNote](https://github.com/OUCC/SyaroNote)

Forked from russross/blackfriday

## Features
### Math
LaTeX inline and display math surrounded by `$` or `$$`.

```markdown
sample $x^y_z$ text _emphasis_

$$ x^y_z = X^Y_Z $$
```

```html
<p>sample \(x^y_z\) text <em>emphasis</em></p>

<p>\[ x^y_z = X^Y_Z \]</p>
```

### Check List
```markdown
- [ ] checkbox
- [X] checked
```

```html
<ul>
<li><input type="checkbox" disabled><label>checkbox</label></li>
<li><input type="checkbox" checked disabled><label>checked</label></li>
</ul>
```

## License
[Blackfriday is distributed under the Simplified BSD License](LICENSE.txt)

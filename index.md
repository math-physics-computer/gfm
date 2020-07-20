# GitHub Pages Markdown (GitHub Flavored Markdown, GFM)


## _config.yml
in `_config.yml`  
```yaml
kramdown:  
    hard_wrap: true
```
Kramdown is the default markdown renderer in GitHub Pages.  
This makes **newline** in editing wraps in display.  



## Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing.  
file extension **.md** is often used for markdown files.



### Line-ending
**Double spaces at the end of a line** produces a line break.



### Italic
Wrap text with \* or \_  
\*foo\* and \_foo\_  
make  
*foo* and _foo_  
Note: no spaces



### Bold
Wrap text with \*\*  or \_\_  
\*\*foo\*\*  and \_\_bar\_\_
make  
**foo**  and  __bar__  
Note: no spaces



### Headings  
```markdown
# <h1>
## <h2>  
### <h3>
#### <h4>
##### <h5>
###### <h6>
```



### Lists

#### Unordered List
\* or \- followed by a space  
```
- foo  
- bar  
* baz  
* baar
```

makes  

- foo  
- bar  
* baz
* baar

Note: same symbols are grouped  


#### Ordered List
Number followed by a dot \.  
1. foo
2. bar


#### Nested List
indent lists with spaces until the list marker character (- or *) lies directly below the first character of the text in the item above it.  
```markdown
1. foo
2. bar
   1. baz
   2. baar
3. baas
```

makes  

1. foo
2. bar
   1. baz
   2. baar
3. baas




### Links
```
[DisplayText](URL)
```

e.g.  

```
[Google](https://google.com)
```

makes  

[Google](https://google.com)

Note: target=\_blank not available in GFM, use &lt;a&gt; tag instead.  



### Images
```
\![AltText](src)
```

e.g.  

```
![BackgroundImage](https://i.ytimg.com/vi/BgIJ45HKDpw/maxresdefault.jpg)
```

makes  

![BackgroundImage](https://i.ytimg.com/vi/BgIJ45HKDpw/maxresdefault.jpg)





### code text
Wrap with ticks \`  
```
`foo()`
```

makes  

`foo()`  


### Syntax-highlighted Code Block
Open with tripple ticks \`\`\` followed by language name  
Close with tripple ticks  \`\`\`  

e.g.  
\`\`\`javascript  
console.log("Hello World");  
\`\`\`  

makes  

```javascript
console.log("Hello World");
```

NOTE: language name can be omitted.  



#### Supported Languages  
- actionscript3
- apache
- applescript
- asp
- brainfuck
- c
- cfm
- clojure
- cmake
- coffee-script, coffeescript, coffee
- cpp - C++
- cs
- csharp
- css
- csv
- bash
- diff
- elixir
- erb - HTML + Embedded Ruby
- go
- haml
- http
- java
- javascript
- json
- jsx
- less
- lolcode
- make - Makefile
- markdown
- matlab
- nginx
- objectivec
- pascal
- PHP
- Perl
- python
- profile - python profiler output
- rust
- salt, saltstate - Salt
- shell, sh, zsh, bash - Shell scripting
- sql
- scss
- sql
- svg
- swift
- rb, jruby, ruby - Ruby
- smalltalk
- vim, viml - Vim Script
- volt
- vhdl
- vue
- xml - XML and also used for HTML with inline CSS and Javascript
- yaml


### For More Details
Visit Links:  
[GitHub Basic Writing and Formatting Syntax](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)  
[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
[GitHub Pages Documentation](https://help.github.com/categories/github-pages-basics/)  

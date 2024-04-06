# What is this ?

Modified Dark Mode Warm theme.
Currently used for web development in JS/TS Vue

## Screenshot 
![](https://raw.githubusercontent.com/JayPuff/warm-despair/master/example.png)


## Chosen Colors

### Basic variables and objects
The core of what gives these theme readability is based on keeping all actual variables, objects, etc. as the only white-ish. colored text. It's only the other special syntax, such reserved keywords, constants, types, functions, strings that are colored within the theme.

### Reserved keywords, operators
The reserved keywords and operators have a muted blue-ish color as we don't want them to stand out too much, the focus is on seeing the actual variables and objects. Methods are also of a similar, but more bright blue.

![](https://raw.githubusercontent.com/JayPuff/warm-despair/master/keywords.png)

### Brackets
In order to visually parse code that is nested within methods, parens, brackets, etc. Brackets have a very distinct color as they get nested. It starts with white so that top level brackets are not visually distracting.

If this is disabled on vscode for you, you can enable it through:
`Tools > Options > Environment > Preview Features and checking "Enable Brace Pair Colorization."`

And it can be customised easily as the rest of this theme can in your settings.json
```
//...
"editorBracketHighlight.foreground1": "#ebf0ee",
"editorBracketHighlight.foreground2": "#f5c34f",
"editorBracketHighlight.foreground3": "#9dcf4d",
"editorBracketHighlight.foreground4": "#4EC9B0",
"editorBracketHighlight.foreground5": "#258ed4",
"editorBracketHighlight.foreground6": "#c56eff",
"editorBracketHighlight.unexpectedBracket.foreground": "#db0042",
///...
```

![](https://raw.githubusercontent.com/JayPuff/warm-despair/master/brackets.png)

### Strings
We want strings to stand out so they are the only pink-ish colored element within the theme.

### Types
Basic types have a unique yellow/gold color
Defined types have a dark teal color

![](https://raw.githubusercontent.com/JayPuff/warm-despair/master/types.png)

### Vue Specific

Although it's a great theme regardless of Vue, the theme will highlight Vue `v-for`, `v-if`, and other vue related shorthands like `:`, `#` or `@` in a dark teal color on templates for easier visual parsing

Expects proper language extensions to be installed before hand.
Ex: Vue Official Language extension in order to highlight vue syntax in templates (Whether pug or html)

![](https://raw.githubusercontent.com/JayPuff/warm-despair/master/vue.png)

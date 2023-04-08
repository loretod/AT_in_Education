# Welcome to your Jupyter Book

This is a small sample book to give you a feel for how book content is
structured.
It shows off a few of the major file types, as well as some sample content.
It does not go in-depth into any particular topic - check out [the Jupyter Book documentation](https://jupyterbook.org) for more information.

Check out the content pages bundled with this sample book to see more.

And here is an attempt at placing Glossary words in a tool tip? [Assistive Technology]({term}`Assistive Technology`)

```{margin} Assistive Technology
{term}`Assistive Technology`
```

## Using Tabs and Cards

And here is practice using tabs:

The following are available **Word Prediction Tools**

````{tab-set}
```{tab-item} CoWriter
CoWriter developed by Don Johnston is available on....

::::{grid}
:gutter: 2

:::{grid-item-card} Pros
- Easy to learn
- Topic Dictionaries
- Cross platform
:::

:::{grid-item-card} Cons
- Subscription based
:::
::::


```

```{tab-item} Read & Write
Read and write for google chrome developed by TextHelp...
```
````

## Adding a Table of Contents

```{tableofcontents}
```

## Working with Admonitions

```{note}
I am a note to highlight important information.
```

```{warning}
I am a warning to highlight something dangerous.
```

```{tip}
I am a helpful tip to keep in mind.
```

```{important} text
some more text...
```

## Embedding Code


```
%%html
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_gjJ80AEupHAM" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe>
```
<!-- blank line -->
<figure>
    <iframe style="width:50%;" src="https://makecode.microbit.org/#pub:_gjJ80AEupHAM" frameborder="2" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe>
</figure>
<!-- blank line -->

## Working with Mermaid
Attempt at Mermaid chart

```{mermaid}

    sequenceDiagram
      participant Alice
      participant Bob
      Alice->John: Hello John, how are you?
```

## Working with Icons

Attempt at FontAwesome Integration- works
<i class="fa-brands fa-apple" aria-hidden="true" title="apple logo"></i> <i class="fa-brands fa-chrome" aria-hidden="true" title="chrome logo"></i> <i class="fa-brands fa-windows" aria-hidden="true" title="windows logo"></i>

And here is a [^mylabel]footnote that will hopefully be included in the bottom of the page if all goes well.

[^mylabel]: I am a footnote in the book letting the reading know a bit more.

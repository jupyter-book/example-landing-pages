% Here we're using `grid` to imply grid semantics -- the actual
% formatting (including columns) is handled by CSS
:::::{grid} 1 1 2 2
:class: outer-grid col-screen

::::{div}

# Scientific Python

```{image} https://scientific-python.org/images/logo.svg
:width: 50px
:align: left
```

This is a description of our project. And a [link to its homepage](https://scientific-python.org).
::::

::::{grid} 1 2 3 3
:class: inner-grid

:::{div}

- [About](https://scientific-python.org/about/)
- [Scientific Python blog](https://blog.scientific-python.org)
- [Tools](https://tools.scientific-python.org)
  :::

:::{div}

- A second column!
- With multiple entries
  :::

:::{div}

- And what about a third
  :::

::::

:::::

% Here we're using `grid` to imply grid semantics -- the actual
% formatting (including columns) is handled by CSS
:::::{grid} 3 3 5 5:::
:class: outer-grid col-screen

<!-- Left spacer -->
::::{div}
::::

<!-- Project description -->
::::{div}

# Landing Pages

```{image} https://jupyterbook.org/en/stable/_images/logo-square.svg
:width: 50px
:align: left
```

This is a description of our project. And a [link to its homepage](https://github.com/jupyter-book/example-landing-pages).
::::

<!-- Spacer between project description and links columns -->
::::{div}
::::

<!-- Link columns -->
::::{grid} 1 1 3 3

:::{div}

- [About](https://mystmd.org/overview/ecosystem)
- [Guide](https://mystmd.org/guide)
- [Sandbox](https://mystmd.org/sandbox)
  :::

:::{div}

- A second column!
- With multiple entries
  :::

:::{div}

- And what about a third
:::

::::

<!-- Right-most spacer -->
::::{div}
::::

:::::

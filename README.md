# Documentation Guidelines
Style guide and how-to for writing documentation using Material for MkDocs in Dyalog projects.

## How to Develop Docs
We use Git submodules to include [centralised styles and assets](https://github.com/Dyalog/documentation-styles) to ensure consistent styles and enable updates from a single location that pervade all of our MkDocs-based documentation.

To make sure you have these, use the `--recurse-submodules` flag when you clone the repository:

```console
git clone git@github.com:Dyalog/documentation-guidelines.git --recurse-submodules
```

If you do a normal clone, you can still get the submodules afterwards:

```console
git submodule init
git submodule update
```

The build system takes a fresh checkout, so published documentation will get the latest updates from [Dyalog/documentation-styles](https://github.com/Dyalog/documentation-styles). However, when writing documentation, you might need to manually update the submodule.

```console
git submodule update
```

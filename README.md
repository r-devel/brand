A [brand.yml](https://posit-dev.github.io/brand-yml/) brand that can be used across R Contributor projects.

Add to a project with

```
quarto add brand r-devel/brand
```

This provides:

- [img/Rlogo-hex.png](img/Rlogo-hex.png): Hex style logo for R.
- [_brand.yml](_brand.yml): From the [brand.yml website](https://posit-dev.github.io/brand-yml/), "brand.yml is a simple, portable YAML file that codifies your company’s brand guidelines into a format that can be used by Quarto, Python and R tooling to create branded outputs."

Adding the brand will copy the contents of the repo (minus the README) into a `_brand` directory.
Any Quarto project will detect this directory and automatically apply the brand.
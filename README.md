![tea](https://tea.xyz/banner.png)

Deploys to [tea.xyz].


# Legal

You may not publish this website in an attempt to masquerade as tea.inc.
Trademark law has our back here.


# Contributing

* The site is built with [Bootstrap] and [Hugo].
* Each HTML page ([`layouts/page`]) must have a corresponding Markdown file in the [`content`] folder.
* Repeated components are in [`layouts/partials`].

## Getting Started

hugo can render your edits while you work:

```sh
hugo serve --watch --buildDrafts --source src
```

## Dependencies

Install hugo yourself or use tea: `sh <(curl tea.xyz)`.

| Project    | Version |
|------------|---------|
| gohugo.io  |  >=0.99 |


# Build

Builds a static, deployable version of the website.

```sh
hugo --source src --destination ../public --minify
```


[tea.xyz]: https://tea.xyz
[Bootstrap]: https://getbootstrap.com/docs/5.2/getting-started/introduction/
[Hugo]: https://gohugo.io/documentation/
[`layouts/page`]: src/layouts/page
[`content`]: src/content
[`layouts/partials`]: src/layouts/partials

# Angular Tailwind CSS Schematics

This schematic will add [Tailwind CSS](https://tailwindcss.com/) to your [Angular](https://angular.io) application.

![Angular Tailwind CSS Schematics][demo]

[demo]: assets/tailwind-gif.gif

## Usage

```
ng add @ngneat/tailwind
```

## Usage with Nx

In Nx, you can either use `nx add` or `ng add` (same as above) to use the schematics.

```
nx add @ngneat/tailwind
```

#### Caveats

This schematic only works with **Nx Workspace** powered by [AngularCLI](https://cli.angular.io/) at the moment. If you rely on **Nx CLI** with `workspace.json`, this schematic won't work correctly. This is due to some discrepancies between `NxCLI` helpers and `AngularCLI` helpers which are quite hard to combine. (Discussed [here](https://github.com/ngneat/tailwind/issues/6))

## Purge

`@ngneat/tailwind` uses built-in `purge` functionality by `tailwindcss` (under the hood, it is [postcss-purgecss](https://github.com/FullHuman/purgecss/tree/master/packages/postcss-purgecss)). By default, `@ngneat/tailwind` sets the `content` to any **HTML** and any **TS** files in the project.

This behavior can be modified as the consumers see fit.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://nartc.me/"><img src="https://avatars1.githubusercontent.com/u/25516557?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Chau Tran</b></sub></a><br /><a href="https://github.com/nartc/tailwindcss-schematics/commits?author=nartc" title="Code">💻</a> <a href="https://github.com/nartc/tailwindcss-schematics/commits?author=nartc" title="Documentation">📖</a> <a href="#ideas-nartc" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://www.netbasal.com/"><img src="https://avatars1.githubusercontent.com/u/6745730?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Netanel Basal</b></sub></a><br /><a href="https://github.com/nartc/tailwindcss-schematics/commits?author=NetanelBasal" title="Code">💻</a> <a href="#ideas-NetanelBasal" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://www.santoshyadav.dev/"><img src="https://avatars3.githubusercontent.com/u/11923975?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Santosh Yadav</b></sub></a><br /><a href="#ideas-santoshyadavdev" title="Ideas, Planning, & Feedback">🤔</a> <a href="#mentoring-santoshyadavdev" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://bilalkhoukhi.com/"><img src="https://avatars1.githubusercontent.com/u/4480581?v=4?s=100" width="100px;" alt=""/><br /><sub><b>BK</b></sub></a><br /><a href="https://github.com/nartc/tailwindcss-schematics/commits?author=Bilal-io" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

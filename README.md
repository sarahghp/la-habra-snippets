### Snippets for La Habra in Atom

This repo contains files to make it easier to use [La Habra](https://github.com/sarahgp/la-habra) in Atom.

Someday, it will be available directly from Atom. In the meantime, cloning the repo and then adding the files into `~/.atom/packages` should allow for local use.

This package makes available the shortcuts listed in `snippets`; the `prefix` is shortcut name.

It also makes the `#_` macro for commenting out complete s-expressions highlight as expected. The following CSS must be added to your user stylesheet — `Atom > Stylysheet` — to complete the effect:

```css
.syntax--comment.syntax--la-habra span {
  color: #5c6370 !important;
}
```

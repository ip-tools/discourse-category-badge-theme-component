## discourse-category-badge-theme-component

## About
Category badge adjustments for [Discourse].
Allows to specify the border-radius for category badges and more.
Primarily made for [Material Design for Discourse].

## Details
- Vanilla font sizes
- Larger category titles
- Larger avatar images
- Remove size limit from topic status icon
- Larger _narrow_ and _verbose_ topic items
- Smaller font size for topic subject on topic page

## Settings
```yaml
border_radius:
  default: '6px'
transform_enabled:
  default: true
```
- border_radius:
  The border radius to apply to all category badges.
- transform_enabled
  Whether to apply shrink transformation to category badges on e.g. `/latest`.

## See also
- [Ample layout adjustments for Material Design for Discourse]

## Example
- [IP Software Community Helpdesk]

## Credits
- Material Master [Maya Ma]
- The whole [Discourse Team]

Thanks for all your hard work on [Discourse] and [Material Design for Discourse]!

[Discourse]: https://discourse.org
[Material Design for Discourse]: https://github.com/Daemonite/discourse-material-theme
[Maya Ma]: https://github.com/sesemaya
[Discourse Team]: https://www.discourse.org/team
[IP Software Community Helpdesk]: https://meta.ip-tools.org/

[Ample layout adjustments for Material Design for Discourse]: https://github.com/ip-tools/discourse-material-theme-ample
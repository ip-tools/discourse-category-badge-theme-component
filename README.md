# Category badge adjustments for Discourse

## About
This is a theme component which allows you to adjust
the CSS parameters of category badges in [Discourse].
Primarily made for [Material Design for Discourse],
it might be useful for other themes too.
See also article [Category badge adjustment component] on meta.discourse.org.

## Synopsis
- Optionally adjust `border-radius` css attribute of category badges.
  Use `border_radius = 6px` for a more flat / less globular appearance.
- Optionally prevent shrinked badges on e.g. `/latest`.

## Screenshots
### Before
![image](https://meta-s3-cdn.freetls.fastly.net/original/3X/0/a/0a73aec62ca1c53aca9aaafba3450b7ff99b1977.png)
### After
![image](https://meta-s3-cdn.freetls.fastly.net/original/3X/0/e/0ef28f3c081d31e5aefbc5411636b62701133b95.png)

## Settings
![image](https://meta-s3-cdn.freetls.fastly.net/original/3X/3/6/36476bdecd138dd9ff524105cf6d1681f6ff9a7f.png)
- **border_radius**:
  The `border-radius` css attribute to apply to all category badges.
- **transform_enabled**:
  Whether to apply shrink transformation to category badges on e.g. `/latest`.
- **emphasize_label**:
  Whether to display category name with `font-weight: bolder`.

### Defaults
```yaml
border_radius:
  default: ''
transform_enabled:
  default: true
emphasize_label:
  default: false
```

## See also
- [Daemonite Material Theme: Ample layout adjustments]

## Example
- [IP Software Community Helpdesk]

## Credits
- Material Master [Maya Ma]
- The whole [Discourse Team] and all contributors

Thanks for all your hard work on [Discourse] and [Material Design for Discourse]!

[Discourse]: https://discourse.org
[Material Design for Discourse]: https://github.com/Daemonite/discourse-material-theme
[Maya Ma]: https://github.com/sesemaya
[Discourse Team]: https://www.discourse.org/team
[IP Software Community Helpdesk]: https://meta.ip-tools.org/

[Category badge adjustment component]: https://meta.discourse.org/t/category-badge-adjustment-component/106366
[Daemonite Material Theme: Ample layout adjustments]: https://meta.discourse.org/t/daemonite-material-theme-ample-layout-adjustments/106379

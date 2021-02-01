# hugo-shortcodes-soundcloud

Hugo shortcodes to embed SoundCloud on your site.

## Shortcodes

### User widget

Copy [soundcloud-user.html](./layouts/shortcodes/soundcloud-user.html) into your `layouts/shortcode/` directory.

#### Usage

```markdown
{{< soundcloud-user UserID >}}
```

#### Example

![Soundcloud user](./images/soundcloud-user.png)

### Playlist widget

Copy [soundcloud-playlist.html](./layouts/shortcodes/soundcloud-playlist.html) into your `layouts/shortcode/` directory.

#### Usage

```markdown
{{< soundcloud-playlist PlaylistID >}}
```

#### Example

![Soundcloud playlist](./images/soundcloud-playlist.png)

## Notes

You can confirm `UserID` and `PlaylistID` by [SoundCloud HTTP API](https://developers.soundcloud.com/docs/api/reference).

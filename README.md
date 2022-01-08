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

### Track widget

Copy [soundcloud-track.html](./layouts/shortcodes/soundcloud-track.html) into your `layouts/shortcode/` directory.

#### Usage

```markdown
{{< soundcloud-track TrackID >}}
```

#### Example

![Soundcloud track](./images/soundcloud-track.png)

## Notes

You can confirm `UserID`, `PlaylistID` or `TrackID` from the following URL (Paste your SoundCloud URL).

```
https://w.soundcloud.com/player/?url=<PASTE YOUR SOUNDCLOUD URL HERE>
```

Or you can use [SoundCloud HTTP API](https://developers.soundcloud.com/docs/api/reference) to get the IDs.

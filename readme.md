# Arc-style Find Bar

Moves Zen's find-in-page bar (Cmd/Ctrl+F) from the bottom of the page to a
floating card in the top-right corner, styled after Arc Browser:

- an off-white card, whatever your browser theme
- a magnifying glass, a borderless search field and a close button
- previous/next arrows and the match count only once you've typed something
- no "Reached end of page" or "Phrase not found" messages: search wraps
  around silently, and the text turns red when nothing matches
- a quick fade-and-slide when the bar opens and closes

## Preferences

| Pref | Default | Effect |
| --- | --- | --- |
| `zen.mods.arc-findbar.show-options` | `false` | Shows the Highlight All, Match Case, Match Diacritics and Whole Words checkboxes on a second row |

## Install

- **Sine:** enter this repository's `owner/name` in Sine's install field in
  Zen's Settings.
- **userChrome.css:** set `toolkit.legacyUserProfileCustomizations.stylesheets`
  to `true`, paste `chrome.css` into `<profile>/chrome/userChrome.css`, then
  restart Zen.

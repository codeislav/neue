<p align="center">
  <img src="images/neue.png" alt="Neue — redesign for YouTube" width="640">
</p>

<p align="center">
  <b>A whole new YouTube interface, in one glass style.</b><br>
  A Chrome extension: free, no ads, no analytics, no servers.
</p>

**[Install from the Chrome Web Store](https://chromewebstore.google.com/detail/pbhodocjfoobobjkkenimpibhbedjkpb)** · [Русская версия](README.ru.md)

---

Neue changes how YouTube looks and works: a floating glass header, a video grid with as many videos per row as you like, videos that open in a pop-up player over the page, with their chapters and comments, comments over a fullscreen video, channel pages that use the whole window — and pages that appear whole and move smoothly, with no jumps. Everything else stays YouTube: your account, subscriptions, recommendations and history work as before.

Settings are in Chrome's side panel, next to YouTube, and apply at once in every open tab.

![The YouTube home page with Neue](images/1-home.png)

<a id="whats-new"></a>

## What's new in 1.2 and 1.2.1

### 1.2.1

- **Comment threads open and close smoothly.** Opened the first time, the "N replies" row waits while the replies load — no spinner, no empty space — then they open whole, the thread's line drawn down with them. A click on the line folds them back up. The thread lines are Neue's own. Fixed: replies were sometimes shown twice.
- **A new loading line at the top:** smooth, it never stalls and reaches the end just as the page is shown — also when the home feed is refreshed from the logo.
- **Margins from the screen edge** (Appearance): 24 to 240 px, on every page.
- **Neue's own thin scrollbar** over the page: the window's no longer takes width, so the page doesn't shift when it comes or goes.
- **A video page opened directly** (a reload, a link): the player has the video's shape (21:9, 4:3, vertical) and its place from the first frame, in theater mode too.
- **Home from a video page** no longer flashes the old feed before the new one.
- **Search:** icons, ⋮ and verified ticks from the first frame; a search within the site arrives whole.
- **Streams:** a replay's chat appears at once. In fullscreen the Chat button opens the chat beside the video — narrower than before and as tall as the video.

### 1.2

- **Pages appear whole, all at once:** home, channels, the video page, search, History, playlists and You — the header, cards, pictures and badges in one frame, with no grey placeholders.
- **The splash screen is off by default:** pages appear whole without it. It can be turned on (Appearance → Loading); with it, the video on its page starts with the page.
- **From the pop-up player to the video page in one smooth move:** the video goes on from the same instant, with no repeated or clicking sound.
- **Theater mode** without a doubled column or a grey band around the player.
- **Smoother scrolling** of the feed and the comments: the next videos load ahead.
- **Search results** appear in place at once; refreshing the home feed from the logo leaves no empty screen.
- **YouTube's new playlist pages** look right; the Watch later sort button no longer shows through.

### 1.1

- **Chapters in the pop-up player:** on the timeline, as on the video's page. The chapter's title next to the time opens the list of chapters above the timeline, which stays in view: the chapter playing is marked, a click jumps to a chapter, and each one can be shared.
- **Comments in the pop-up player:** the wheel down or V raises the comments card over the video, as in fullscreen. A time in a comment plays the video from there.
- **The tab is titled by the video** while the pop-up player shows it, as on the video's page.
- **Wide videos** (21:9 and wider) open in their own shape at once, as the narrow ones already did.
- **Hide Shorts** also clears the Shorts from a channel's "For you" shelf, while a channel's Shorts tab and the search's Shorts filter keep showing them.
- **Share** in the pop-up player is dark in both themes; a chapter's share opens within the card.

## Contents

- [What's new in 1.2 and 1.2.1](#whats-new)
- [Smooth and steady](#smooth)
- [Header](#header)
- [☰ menu](#menu)
- [Home page](#home-page)
- [Pop-up player](#pop-up-player)
- [Video page](#video-page)
- [Fullscreen](#fullscreen)
- [Channels](#channels)
- [Playlists, history and search](#playlists-history-and-search)
- [Theme and glass](#theme-and-glass)
- [Settings](#settings)
- [Hotkeys](#hotkeys)
- [Languages](#languages)
- [Privacy](#privacy)
- [Requirements](#requirements)
- [Feedback](#feedback)

<a id="smooth"></a>

## Smooth and steady

- **Pages appear whole.** YouTube shows a page in pieces: grey placeholders, then the text, then pictures and icons one by one. Neue waits until what is on screen is ready and shows it in one go — home, channels, the video page, search, History, playlists and You.
- **Nothing jumps.** The player has the video's shape and place from the first frame, on a reload and in theater mode; the header is in place from its first frame; a channel's header and tabs and the search results stay put.
- **Within the site:** a video's details and recommendations come together, not in steps; a video of another shape doesn't move the page; the old feed is never shown before the new one.
- **From the pop-up player to the video page** in one move, from the same frame, with no repeated sound.
- **Comment threads** open and close smoothly, with their own lines.
- **The loading line** at the top runs smoothly and finishes as the page shows.
- **Scrolling:** the next videos, comments and pictures load ahead, and Neue's own thin scrollbar never shifts the page sideways.

## Header

- **Floating glass buttons.** The flat top bar becomes a row of glass buttons and pills that line up with the edges of the video grid.
- **The logo** is a glass pill of the same height as the buttons.
- **Shorts, Subscriptions and You** move from the left column to the header, next to ☰.
- **Their menus** open on hover as a glass card right under the button, with rounded items.
- **"My channel" and "Studio"** become buttons before "Create" instead of hiding in the account menu.
- **Search bar width** is yours to choose: 320 to 1400 px. In a narrow window it gets shorter and never runs into the buttons.
- **One style for every button:** the same size, the same glass, the same shadow. The microphone loses its grey disc.
- **Icons are there at once.** YouTube loads its header icons a few seconds after the page appears; Neue draws them itself, so they are in place from the first frame.
- **Tooltips** are small glass captions under the button: after a short delay, and instantly when you move from one button to the next. Where names are already visible (the menus), there are none.
- **Narrow windows:** the header gives way in steps — first "My channel" and "Studio" hide, then Shorts, Subscriptions and You, and the search bar shrinks.

<a id="menu"></a>

## ☰ menu

- **A floating glass card** at the level of the first row of videos, aligned with the left part of the header, instead of a sidebar glued to the window's edge.
- **Docked**, the card pushes the page to the right and covers nothing.
- **Menu items** are pills with even gaps; the current, hovered, pressed and focused item all keep the same shape.

## Home page

- **Videos per row: 1 to 12**, applied at once, without reloading. The number is a maximum: a narrow window shows fewer, so the cards don't get too small.
- **The topic bar** ("All", "Music", "Gaming"…) is hidden. Turned back on, it becomes glass pills that scroll away with the page.
- **Shorts shelves** can be hidden with one switch — on the home page, in search, in recommendations and in a channel's "For you" shelf. Where you asked for Shorts, they stay: a channel's Shorts tab and the search's Shorts filter.
- **The topics shelf** (a shelf of topic buttons with a few videos) can be hidden too, whatever YouTube's language.
- **A calm splash screen** with the logo can cover the page while YouTube rebuilds it on a full load. Off by default since 1.2: pages appear whole without it.

## Pop-up player

![A video in the pop-up player over the home page](images/2-quick-view.png)

- **A click on a video** on the home page or a channel page opens it in a pop-up player over the page. The page stays where it was.
- **The player takes the video's shape** from the start: 16:9, 21:9 and wider, 4:3, square or vertical, no jump from 16:9.
- **Chapters** are on the timeline, as on the video's page. The chapter's title next to the time opens the list of chapters above the timeline: the chapter playing is marked, a click jumps to a chapter, and its share opens within the card.
- **Comments over the video:** the wheel down or V raises them in a card, as in fullscreen; the wheel up at the top of the list, V, Esc or a click beside the card lowers it. A time in a comment plays the video from there.
- **The tab's title** is the video's while it plays in the player, and the page's again once it closes.
- **Under the video:** the channel, Subscribe, like, share, save and ⋯ — YouTube's own buttons, working with your account.
- **↗ opens the video's page** from the same second, in one movement: the picture moves into the page's player, sound and picture stay together. Middle click or Ctrl+click on ↗ opens it in a new tab; on a video card they work as usual on YouTube.
- **↗ and ×** look and hide like the player's own round buttons.
- **Save (E):** the playlist card opens in the corner of the player, and the "Saved" notice appears there too.
- **F** puts the pop-up player in full screen — the same player, only bigger.
- **History:** videos watched in the player count in your YouTube history, and the card on the page gets the red bar of what you watched.
- **Mixes and playlists** open in the player too; ↗ takes you to the mix with its queue.
- **Closing:** ×, Esc, or a click outside the video (that last one can be turned off).

## Video page

- **The same margins as the home page and channels**, instead of the page running almost to the screen's edges (set in Appearance: 24–240 px from the screen edge).
- **The player** has the video's shape and place from the first frame, even on a reload.
- **Live chat** sits exactly in the recommendations column and follows window and theater-mode changes; a stream replay's chat appears at once.
- **Comment threads** open and close smoothly: the replies open whole, with the thread's line, and a click on the line folds them back.
- **Save (E)** works here too: the playlist card opens in the corner of the player, without darkening the page.
- **Comment sorting** opens a single clean menu: "Top" and "Newest".

## Fullscreen

![Comments over a fullscreen video](images/3-comments.png)

- **Comments instead of recommendations.** In fullscreen, scrolling down raises a card of comments over the video instead of YouTube's grid of recommendations. V or the ⌃ button do the same.
- **The card** is glass, centred, with the comment box at the top; the list scrolls inside it.
- **The wheel** scrolls the comments from anywhere on the screen; scrolling up at the top of the list (a new gesture) closes the card.
- **Reply without leaving the video:** clicks in the comments don't pause it, and typing doesn't trigger the player's keys (k, f, m…).
- **Card size** is adjustable: width 700–1800 px, height 40–90% of the screen.
- At the end of a video, YouTube's end screen with recommendations stays as it is.
- **Streams:** the Chat button opens the chat beside the video, as tall as the video.

## Channels

![A channel page with Neue](images/4-channel.png)

- **The whole window width:** banner, header, tabs and videos run to the edges of the grid, on one line with the logo.
- **Channel info on the banner:** avatar, name, description and buttons sit on the banner's lower left over a dark gradient; the rest of the banner stays clear.
- **Tabs** are glass pills; search is a round button that opens into a field.
- **Shelves** show exactly 6 videos, and the arrows page by exactly 6; posts by 3; playlists in 6 columns.
- **"Welcome" button:** the trailer that YouTube autoplays on the channel page (muted, with captions) is removed from the page and opens from a button next to Subscribe — in the pop-up player, with sound.
- **Channel videos** open in the pop-up player, one after another, without leaving the channel.

## Playlists, history and search

- **Playlists, Watch later and Liked videos:** the playlist card starts at the page's edge next to the ☰ card instead of being pinned to the window's edge; cards and list start at the level of the first row.
- **History** starts at the page's edge, with search and actions on the right, under the avatar.
- **Search results** and filters start from the left edge of the search bar.

## Theme and glass

![Neue in the light and the dark theme](images/5-themes.png)

- **Light and dark:** Neue follows YouTube's theme, the settings panel included. What sits over video — the pop-up player, the comments card, a channel header on its banner — stays dark.
- **Glass:** opacity (30–95%) and blur (0–40 px) are set once for the whole interface.
- **Margins:** the distance from the screen edge to the content, 24–240 px, on every page; the header follows it.

## Settings

The extension's button opens the settings in Chrome's side panel, next to YouTube: one page per section, with icon tabs. Changes apply at once in all open YouTube tabs and sync through your Chrome account.

| Section | Setting | Values | Default |
|---|---|---|---|
| **Home** | Videos per row | 1–12 | 4 |
| | Pop-up player | on / off | on |
| | Close by clicking outside | on / off | on |
| | Topic bar | on / off | off |
| | Hide Shorts | on / off | off |
| | Hide the topics shelf | on / off | off |
| **Header** | Shorts, Subscriptions, You | on / off | on |
| | My channel and Studio | on / off | on |
| | Search bar width | 320–1400 px | 640 px |
| **Fullscreen** | Comments over the video | on / off | on |
| | Card width | 700–1800 px | 1200 px |
| | Height | 40–90% | 70% |
| **Channels** | "Welcome" button | on / off | on |
| **Appearance** | Margins from the screen edge | 24–240 px | 66 px |
| | Glass opacity | 30–95% | 60% |
| | Blur under the glass | 0–40 px | 20 px |
| | Splash screen on load | on / off | off |

The **More** page has the hotkeys, export of all settings to a JSON file, import from a file and "Reset all".

## Hotkeys

| Key | Action |
|---|---|
| <kbd>V</kbd> | Open or close the comments (fullscreen and pop-up player) |
| Wheel ↓ | Open the comments (fullscreen and pop-up player) |
| <kbd>E</kbd> | Save to a playlist (pop-up player and the video's page) |
| <kbd>F</kbd> | Pop-up player in full screen |
| <kbd>Esc</kbd> | Close the pop-up player |

## Languages

The interface follows YouTube's language, not the browser's: English, Spanish, Portuguese, German, French, Italian, Russian, Polish, Turkish, Ukrainian, Japanese, Korean, Chinese (Simplified and Traditional), Indonesian, Vietnamese and Hindi.

## Privacy

Neue collects nothing and sends nothing to anyone. It has no servers, analytics or ads, runs only on www.youtube.com and talks only to YouTube itself. Settings are stored in Chrome. Details: [privacy policy](privacy-policy.md).

## Requirements

- Chrome 125 or later on a computer, including one connected to a TV; the full site www.youtube.com.
- Does not change m.youtube.com, YouTube Music or YouTube players embedded in other sites.

## Feedback

Found a bug, have an idea, want a setting? Write — all of it is read.

- [GitHub Issues](https://github.com/codeislav/neue/issues)
- [Discord](https://discord.gg/7kBZKnp9DJ)
- E-mail: codeislav@gmail.com

---

Neue is an independent project and is not affiliated with or endorsed by YouTube or Google. YouTube is a trademark of Google LLC.

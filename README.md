# rclovis.github.io

The pages Google Play and AdMob require an app to have, served from GitHub
Pages at <https://rclovis.github.io>.

- `minesweeper/privacy/` : privacy policy for `com.rclovis.minesweeper`, in the
  four languages the app ships (en, fr, es, zh).
- `clock-in/privacy/` : privacy policy for `com.rclovis.clockin`, in the two
  languages the game ships (en, fr).
- `knock-lane/privacy/` : privacy policy for `com.rclovis.knocklane`, in the
  two languages of its store listing (en, fr). The game collects nothing and
  has no internet permission; the policy says so.
- `app-ads.txt` : declares the AdMob publisher account authorised to sell this
  developer's inventory. Must stay at the domain root, and the Play listing's
  website field must point at this domain for AdMob to crawl it.

Plain HTML, no build step. Edit and push.

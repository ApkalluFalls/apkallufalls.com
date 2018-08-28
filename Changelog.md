# Changelog

## 2.1 - August 2018

### New Features
* Orchestrion Rolls and Chocobo Barding is now listed. ([Blog entry](https://www.patreon.com/posts/did-someone-say-20213110))
* https://apkallufalls.com/connect - Users can now log in to Apkallu Falls with email, Facebook, Google and Twitter. ([Blog entry](https://www.patreon.com/posts/sign-in-page-19563395))
  * Logged-in users can verify ownership their characters by visiting their character profile pages.
  * Logged-in users can manually track content like Emotes, which are not automatically trackable. ([Blog entry](https://www.patreon.com/posts/19810553))
  * Removed the Patreon tracker and 'Become a Patron' button in the navigation menu for users who have verified with a supporter character.
* XIVDB has been completely dropped in favour of [XIVAPI](https://xivapi.com).
* The home page has had a revamp to be a lot more informative, and an experimental Dark Mode now exists, and can be toggled on or off on the home page. ([Blog entry](https://www.patreon.com/posts/better-welcome-20859845), [Tweet](https://twitter.com/ApkalluFalls/status/1030533575039496192))
* Content which is available on the in-game Market Board is now marked as "tradeable". ([Blog entry](https://www.patreon.com/posts/sometimes-of-can-21003548))

### Minor Tweaks
* Counts are now visible on character profiles. They weren't visible on the sidebar on smaller screens.
* The 'Show' (obtained/unobtained) filter has been removed from list pages when not tracking a character.
* The navigation menu has been condenced to allow for more content listings. ([Blog entry](https://www.patreon.com/posts/condensed-and-20041197))
* Minion and Mount pages now include a link through to [Minion Guide](https://minionguide.com).
* Prevented in-app links from causing an unnecessary full page reload.
* Resolved an issue whereby the Achievements page did not load correctly after visiting the Titles list has been resolved.
* Additional stats are now available on character profiles, tracking the progress of Relic Weapons, Anima Weapons, Aetherpool Gear upgrades and Eureka Weapons. ([Tweet](https://twitter.com/ApkalluFalls/status/1028971060669149184))
* Resolved a Safari-specific issue whereby some date-related numbers were not being properly calculated.
* Added Donate link to footer (https://donorbox.org/apkallufalls). Patreon is definitely preferred, but I've seen other apps use this recently so figured I'd give it a go.

### Known Issues

* Tracked characters are stored on the browser, not on the signed-in account. This means if you hop between accounts, your tracked characters list will remain the same.
* Whilst multiple characters can be verified against a signed-in profile, currently there is no mechanism in place to change the default one (which appears above your avatar in the bottom right corner when logged in).
* The forgotten password functionality generates an email which Hotmail sometimes treats as spam. This issue does not appear to be present with other email providers. If you are a Hotmail user and you forget your password, make sure to check your spam folder.
* It's not currently possible to manually track promotional, unavailable or unknown content. This will be available at a later date.
* The three starting city achievements, Gone from Gridania, Leaving Limsa Lominsa and Out of Ul'dah are currently included within the progress bar for Quests on the top-level achievements page. These should be filtered out as it's not possible to have all three of these unlocked together.
* It's possible to verify ownership of the same character with different accounts. This may in some cases be desirable, however.

## Version 2.2 Roadmap

* Make levequests trackable.
* Implement a content search mechanism.
* Work towards implementing an achievement ranking (to compete with/replace XIVDB's ranking).
* Separate languages into their own localisation files (currently they're all bundled into one).

### Discussion Points

#### When will the census be implemented?
Due to the news about XIVDB, and the fact it still hasn't updated to patch 4.6, this is currently on hold until further notice.

#### You said hairstyles would be trackable, where are they?
There are only 8 hairstyles available in-game that aren't available by default. Dedicating a section of the site to track such a small quantity of content would be expensive with little reward. For now, this is on hold.
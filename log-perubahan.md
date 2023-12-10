# <p align="center"><img src="https://i.imgur.com/lUyeJp9.png"  width="360" height="143">
# <p align="center">The entire JawiCraft changelog!<br />

[Back to the wiki](https://github.com/Minecraft-EdisiMelayu/MCEM-Wiki/wiki)

---
# v1.9 (??/12/2023)
- Changed the language code from `ms_arab_my` to `zlm_arab`, so it would be cross-compatible between versions before and after 1.19
- Support for pre-1.13 version has been re-introduced!
  - For versions 1.7 - 1.10, after applying the pack, restart your game to apply the font changes properly (due to the [MC-41270](https://bugs.mojang.com/browse/MC-41270) bug)
- Added Malay translations for splash texts, credits and the End Poem, which are taken from the [MCSplahes](https://github.com/SmajloSlovakian/MinecraftSplashTextTranslation) project, by SmajloSlovakian
  - Added Jawi translations for most of the splash texts! Some are kept in Rumi Malay due to problems with punctuations marks and stuff
    - Some of splash texts with diacritics will look broken due to how Minecraft's Unifont system works, especially in pre-1.20 versions
  - Credits' and End Poem's translation are kept in Rumi Malay due to possiblities of having problems with reading Jawi texts on top of the dirt background
    - Might be reconsidered at some point, but for now, enjoy the Rumi translations!
- Un-Jawi-fied the "Copyright Mojang AB." text, due to alignment problems which cause some characters to be rendered out of bounds (1.20.2+)
- Fixed some untranslated painting names (both Rumi & Jawi, 1.19.3+)
- Updated both in-game credits and credits within the zip file

---
# 1.8

## v1.8.4 (19/7/2023)
[​All Versions]

* Changed every Arabic hamzas in the language files to Jawi's "three\-quarter high hamzas"
  * Used the "Arabic Letter High Hamza", and changed the font texture to closely match the three-quarter high hamza
* Base translations updated to 1\.20\.1
* Updated credits both in\-game and in the pack's txt file

[​1.20]
* Added support for 1\.20
* Added support for the new logo format

[​1.19]
* Some clients and/or launchers \(such as Prism Launcher\) seems to natively fix the Arabic splash text bug for me
* An additional pack is now released to use when playing the game using Prism Launcher [here](https://legacy.curseforge.com/minecraft/texture-packs/jawicraft-language-pack/files/4653376)! (can't confirm for MultiMC and other clients)
* Added name fixes for some untranslated painting names \(both in Latin and Jawi Malay\)

See you on August 31st for the next update!

## v1.8.3 (4/1/2023)
[​1.13.x - 1.18.x]

* Base translations have been updated to 1\.19\.3

[​1.19.x]
[​Ignore the warning when loading up the pack in 1.19.3]
* Base translations have been updated to 1\.19\.3
* Language file now includes all the strings instead of just the modified ones
  * This is to make it easier for me as I don't have to filter newly updated translations every time I make an update
* Re\-added the Jawi versions of the splash texts\, thanks to a workaround I recently found
* Removed the ZWNJ fix provided in the pack\, as it is already fixed in\-game
* Removed the credits for the ZWNJ fix from the credits both in the zip file and in\-game
* Slight changes to the pack\.mcmeta file

## v1.8.2 (17/9/2022)
* Removed all the reference to the independence month \(as it is already over unfortunately\)
* Reverted the Merdeka\-fied logo on the resource pack icon \(for the same reason\)

## v1.8.2-65 (31/8/2022) / v1.8.2 (17/9/2022) [1.13-1.19]

* Added Merdeka\-themed splash text\, among a few others
* Merdeka\-themed splash texts will be removed on September 17th
* \[​1\.13 \- 1\.16\] Added pack's credits to the in\-game credits \(with colored texts\)
* Uses 1\.16\.5's credits as the base
* \[​1\.17 \- 1\.19\] Updated the credits to have colored texts
* Updated all pack's logo with the Merdeka\-fied version of the JawiCraft logo
* Will be reverted to normal on September 17th

Happy Birthday JawiCraft!
(this pack was released a year ago, on August 31st 2021 :0)

## v1.8.1 (13/8/2022)
[​1.13 - 1.18]
* Updated base translations to the MC 1\.19\.1 revision
* Changed the translation of "Lava" from "لاۏا/Lava" to "لاهر/Lahar"
* Added splash texts referencing the independence month of Malaysia and a few others\.\.\.
* Added missing translations for older versions
* Base for the in\-game pack credits is now updated to the one used in MC 1\.19\.1
* Also fixed the spelling error: Penerjemah/ڤنرجمه \-\> Penterjemah/ڤنترجمه
* In\-game pack credits for pre\-1\.17 packs will be readded in 1\.8\.2 \(I'm already tired updating this version and also because of other stuffs T\-T\)
* Added back the Combat Test 8c texts into the 1\.16\.2\-1\.16\.5 pack \(including the regular Malay translations of those strings\)
[​1.19.x]
* Added new translations for "Lava"\, "Singleplayer"\, and "Multiplayer" only
* This uses/replaces the zlm\_arab file\, instead of the ms\_arab\_my that the pack uses
* Removed all splash texts written in Jawi
* Some texts that are only or partially written in Jawi in the original list are replaced with their Rumi counterparts \(which are also added to the original list\)
* This is done due to not be able to set the 'bidirectional' tag to 'true' for existing languages via pack\.mcmeta\, which caused the Jawi texts to be reversed and disconnected
* Updated the pack's logo

## v1.8 [1.13-1.18] (9/7/2022)
* And the backport phase of the project has begun\!
  * Now the project will backport the translations from the latest version of Minecraft to the older versions
  * This phase will come to the Pre\-1\.13 versions soon \(hopefully\)
* This project is also now part of a collection project that I will start which I'll announce when its fully ready
* Renamed the language to "بهاس ملايو \(مليسيا\)" to match the name in 1\.19

---
# 1.7

## v1.7.3 [1.13-1.18 + 1.19 Pre-release] (02/06/2022)
* Updates translations

* Will be further updated with the next major version\, 1\.8
* Removed splash text referencing Eid Al\-Fitr \(since its over at this point\)
* Added splash texts which references the addition of Jawi into Minecraft in 1\.19 Pre\-release 4
  * The splash texts are "Kini di Minecraft\!" and "کيني دماءينکرف‌ت\!" \(both means "Now in Minecraft\!"\)
* 1\.11\-1\.12 version of the pack are now removed from the download list\, and will be re\-added in a future update

## v1.7.2(.0) [1.11-1.18 + 1.19 Snapshot] (01/05/2022)
* Added support for the latest 1\.19 snapshot
  * Versions for snapshots will have an extra number at the end of the version number
* Removed the regional compliancies' Malaysia locale support from the previous version
  * To be honest I felt that it was unnecessary to be added
* Removed a few splash texts
* Added splash texts\, most of which Eid al\-Fitr celebration references \(which is on May 2nd :0\)
  * Will be removed from the pack after Syawal ends \(which is on May 31st\)
* Also added splash texts referencing some new features in 1\.19 in the pack's version for 1\.19 snapshots\, and more will be added in the next version\! :0
* Added a custom Mojang Studios loading screen logo \(will not work in vanilla\)
* Updated and fixes some translations \(for 1\.13\+ versions\, more will be hopefuly fixed in the next updates\)

## v1.7.1 (01/03/2022)
[​1.18.x]

* Updated the pack to 1\.18\.2
* Added new strings from the pre\-releases
* Added proper support for the South Korean regional compliancies \(added in 22w06a\) with the Malaysia locale
  * Unconfirmed whether this works or not
* Added support for the 1\.19 Deep Dark Experimental Snapshot 1 \(fork of 1\.18\.1\)
  * All translations are provided by Ahmad Ali Karim
  * Roman Malay translations for this snapshot is also available [here](https://www.curseforge.com/minecraft/texture-packs/jawicraft-language-pack/files/3668221)! (also provided by Ahmad Ali Karim)

[​1.16.2 - 1.16.5]
* Added support for the Combat Test 8c version \(fork of 1\.16\.2\)
* Translations provided by Ahmad Ali Karim
  * Roman Malay translations for this version is also available [here](https://www.curseforge.com/minecraft/texture-packs/jawicraft-language-pack/files/3668373)! (also provided by Ahmad Ali Karim)

## v1.7 [1.13-1.18] (13/02/2022)
[​1.13 - 1.18]

* Updated the translation revision to the new "Ahmad Ali's Revision"
* I named it that because of Ahmad's dedication of going through all of the Minecraft strings\, fixing and approving all of it in just 3 days
* Added a custom language option in the Language option menu\, called "جاوي \(ماليسيا\)"\, located right above "Bahasa Melayu \(Malaysia\)"
  * Uses the custom "ms\_arab\_my" language code
  * The language will fallback to English when the pack is unloaded\, and will be applied again when you reload the pack \(if you didn't change the language prior to reloading it\)
* The ZWNJ bug \([MC-226359](https://www.curseforge.com/linkout?remoteUrl=https%253a%252f%252fbugs.mojang.com%252fbrowse%252fMC-226359)) is now fixed in snapshot 22w03a for 1.18.2
  * The temporary fix provided in the pack for previous versions will now be ignored when loaded in the 1\.18\.2 snapshots
* Added a credits section for JawiCraft above the Minecraft credits in the 1\.17 and 1\.18 credits\. The Minecraft credits is not touched at all
* Added a credits text file in all version's pack folder
* Updated the 1\.18 pack logo
* Added a few splash texts to the pack

[​1.6 - 1.12]
* Added the custom "جاوي \(ماليسيا\)" language option \(explained in the 1\.7 changelog\)
* Updated some translations to the new revision
* This pack now no longer officially supports 1\.6 due to a bug with the Arabic writing system in that version
  * Links to download the 1\.6\-1\.8 and 1\.9\-1\.10 packs is now removed\, and might be added back later \(or not\)\. Use the 1\.11 \- 1\.12 versions for the time being
  * This is done to keep compatability with the added custom language\, and also with CurseForge\, as they won't accept format 1 and 2 packs for some reason
* Added a credits text file in the version's pack folder
* Added a few splash texts to the pack


---
# 1.6

## v1.6.1 [1.18-1.18.1] (11/12/2021)
* Updated the pack to 1\.18\.1
* Added a new string to the realms' language file
* Fixed an error in the realms' language file

## v1.6 - Major Update #1 [1.6-1.18] (2/12/2021)
-Project now updated to the 1.18 release

* Translation Updates
* Base translations for version 1\.13 \- 1\.18 is now updated to the 1\.18 pre\-5 translations
* Translations for the "Singleplayer" and "Multiplayer" now changed for all versions
* "Singleplayer" \- "Permainan Tunggal/ڤرماءينن توڠڬل" \-\> "Ekapemain/ايكاڤماءين"
* "Multiplayer" \- "Permainan Jamak/ڤرماءينن جمع" \-\> "Multipemain/مولتيڤيماءين"
* Implemented a fix for the ZWNJ bug [(MC-226359)](https://www.curseforge.com/linkout?remoteUrl=https%253a%252f%252fbugs.mojang.com%252fbrowse%252fMC-226359) by modifying the glyph\_sizes.bin and the unicode\_page\_20.png files
* But it cannot be properly implemented into the 1\.6\-1\.8 and 1\.9\-1\.10 version because of the [MC-41270](https://www.curseforge.com/linkout?remoteUrl=https%253a%252f%252fbugs.mojang.com%252fbrowse%252fMC-41270) bug, which cause inconsistencies in loading the resource packs' glyph\_sizes.bin file

---
# 1.5

## v1.5.3 [1.18 Pre-release] (17/11/2021)
* Added string from the Pre\-release 2
* Fixes a tiny error in the translations from the previous hotfix

## v1.5.2 Hotfix [1.18 Pre-release]
* Added the 21w44a strings which for some reason I completely forgot to add to the v1\.5\.1 language file ;\\

## v1.5.1 [1.6-1.17 & 1.18 Pre-release]
* Updated the pack to 1\.18 Pre\-release
  * Might no longer updating this version unless there is new strings added during the upcoming pre\-releases
* Updated all the pack icons \(other than the 1\.6 \- 1\.8 version\)

## v1.5 [​31/10/2021] (1.6-1.17, 21w43a)

* Add support for version 1\.6 \- 1\.12
* Will have their own version number seperate to the main one
* For the 1\.6\-1\.8 and 1\.9\-1\.10 version\, you have to extract the zip file first before using
* Add support for 1\.18 snapshot \(21w43a\, will be updated everytime a new snapshot released\)
* Fixes a lot of translation errors
* Updated all resource pack logos
* Might be updated again soon \(or not\)

---


# v1.4 Hotfix [12/9/2021] (1.13-1.17)


* Fixes a tiny typo... The typo was in the name of the " A Terrible Fortress" advancement, which is spelled as "بوکو/buku" (book) instead of "کوبو/kubu" (fortress)


![width=356](https://i.imgur.com/UEZgxEq.png)

---

# v1.3 [10/9/2021] (1.13-1.17)

* Fixes some translations error (in the language file, not on Crowdin)
* Adds the new Jawi version of the title screen logo, thanks to Ahmad Ali Karim!
* Updated the resource pack logo
* Adds the new Jawi version of the pack name in the resource pack logo, also thanks to Ahmad Ali Karim!

---

# v1.2 [03/09/21] (1.13-1.17)
* Fixes a lot of the translations
* Adds more translations

---


# v1.1 Hotfix [01/09/21] (1.17)
* Fixes a tiny error in the language file

---


# v1.0 [31/08/21]
The Pack's Initial Release

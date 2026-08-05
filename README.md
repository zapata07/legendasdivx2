Kodi subtitle addon for Legendasdivx.pt. Changed to comply with Kodi v21. Several corrections.
Based on Highlander's work, v.1.6.0 
Tested on Kodi 21.3. Probably not compatible with previous major releases.

*** Code generated via Gemini Pro AI ***

Notable changes:
- Correction of results presentation: emoval of extraneous string "document.currentScript.previousElementSibling.querySelector" present on all results.
- More complete compatibility with Kodi 21, e.g. removal of obsolete function xbmc.getCleanMovieTitle).
- Many improvements and corrections to the search function. E.g. the TV show search was bugged since a long time ago.
- New search option, "Search by IMDb ID" (see addon Advanced Settings). Option activated by default. This option resolves 99.9% of search issues.
- When searching by name, instead of the new default, by IMDb ID, correction to the search string algorithm.
- Changed the User-Agent to use a more modern one to work around possible connectivity blocks.

To install the addon:
1. Download repository -> https://raw.githubusercontent.com/zapata07/legendasdivx2/main/repository.zapata07/repository.zapata07-1.0.0.zip
2. Add the repository to Kodi via the the "Install from zip file" option.
3. Go to the just added repository ("Zapata07 repo") and install the Subtitle addon.
4. Don't forget that you need go to the addon settings and insert your username and password to access the legendasdivx.pt website. 

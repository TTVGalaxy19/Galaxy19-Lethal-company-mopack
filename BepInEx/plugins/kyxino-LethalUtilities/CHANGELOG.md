
<details open>
<summary>
<b>
1.2.x (LATEST)
</b>
</summary>
<h1 id="1-2-8-latest">1.2.8 (Latest)</h1>
<ul>
<li>Fixed teleporting settings. Teleporters may behavior slightly different if it was misused.</li>
</ul>
<h3 id="1-2-7-latest">1.2.7 (Bug Fixes)</h3>
<ul>
<li>Did some small bug fixes, things shouldn't be too crazy now.</li>
</ul>
<h3 id="1-2-6-new-readme-md-format-">1.2.6 (New README.md Format)</h3>
<ul>
<li>Made the README section look a lot nicer (after breaking it in 1.2.5, whoops.)</li>
</ul>
<h3 id="1-2-5-scrap-multiplier-fix-">1.2.5 (Scrap Multiplier Fix)</h3>
<ul>
<li>Fixed some scrap multipliers not undoing when switching maps/weather. + I'm working on a new mod/API that LU will use so that I'm not constantly accidentally messing things up as easily.</li>
</ul>
<h3 id="1-2-4-auto-offensive-value-fix-">1.2.4 (Auto Offensive Value Fix)</h3>
<ul>
<li>Fixed the auto Offense fix, it was really stupid.</li>
</ul>
<h3 id="-1-2-3-the-auto-fix-that-needed-a-fix-in-1-2-4-"><del>1.2.3 (The Auto Fix That Needed a Fix in 1.2.4)</del></h3>
<ul>
<li>Forgot that I should make it fix the old default values being set to 0 for Offense (along with some other things), so I did that, and now I have an excuse for 123.</li>
</ul>
<h3 id="1-2-2-fixed-offense-spawn-values-">1.2.2 (Fixed Offense Spawn Values)</h3>
<ul>
<li>Fixed the issue with Offense having a bunch of values set to 0. I accidentally had the Company Building settings overwrite it.</li>
<li>Changed when monster spawn weights apply, hopefully should apply any other mod so that they can overwrite my settings, if needed.</li>
<li>Getting ready to change more variable names and make descriptions more pronounced.</li>
</ul>
<h3 id="1-2-1-mapscalar-crash-fix-">1.2.1 (MapScalar Crash Fix)</h3>
<ul>
<li>Added a cap to mapSizeMultiplier (aka MapScalar) to be capped at 1, otherwise crashes will likely happen.</li>
</ul>
<h2 id="1-2-0-major-map-weather-spawn-settings-update-more-">1.2.0 (Major Map/Weather/Spawn Settings Update+More!)</h2>
<ul>
<li>Reformatted the CHANGELOG.md to have the latest updates upwards rather than downwards.</li>
<li>Fixed the mod version within the DLL, forgot to change it ever since v1.0.1, doesn't really change anything anyway.</li>
<li>Automatically converting all other variables with part of their category names being prefixed into the individual variables. (Like the diff ConfigEnabled vars and map/weather settings.)</li>
<li>Fixed the key door locking feature that didn't work unless both types of reuseable keys were enabled. (I think this happened during v1.1.2.)</li>
<li>Got more than 5 hours of sleep 4 nights in a row.</li>
<li>Huge map values customization.</li>
<li>Added settings for monster spawn weights, INCLUDING MONSTERS FROM ANY MAP AND LASSO MAN.</li>
<li>Added settings for the weather to change monster spawn weights. (Ex: Giants on Experimentation when Eclipsed... the struggle is real.)</li>
<li>Added new items as gears for the TeleportSettings, along with new items coming out in LC soon.</li>
<li>Added new settings for the new spray can item. (I will be updating sooner after the game updates next time, just was working on v1.2.0 for a while and stablizing it.)</li>
<li>Adding proper time speed multipliers, DayScalar will remain around as it has a separate purpose, though confusing, I think it is just how far into the day you want to spawn along with actual time speed. TimeSpeedScalar will be the more obvious value for changing... well, the speed of time. Both can be paired together for better time results.</li>
<li>Working on a new settings format for v2.0.0 that will be completely different and a LOT bigger/more expansive, which will allow for more additions even after this mod is outdated. (This may come out at the end of the month unless it gets too big, then I will likely have to turn it into a new mod entirely.)</li>
<li>New teleporter setting for dropping everything but your held item and another for dropping everything that isn't gear and isn't your held item.</li>
<li>Will be condensing the code to be better and more flexible.</li>
<li><del>Rename planets, change descriptions, risk levels</del> (Next update, needs more testing to see if it is even stable.)</li>
</ul>
</details>
<details>
<summary>1.1.x</summary>
<h3 id="1-1-2-the-light-i-see-the-light-">1.1.2 (The Light, I See the Light!)</h3>
<ul>
<li>Made the CHANGELOG.md nicer looking to show all of my updates and idiocy.</li>
<li>Forgot to re-add the config folder with the new changes.</li>
<li>Also not entirely sure if the DLL properly applied in v1.1.1, so I confirmed it applied in this version.</li>
<li>Goodnight, ladies and gentlemen, I will finally get some sleep. (Updates will no longer be rushed since the mod is already fulfilling its purpose of being able to edit a bunch of the games variables.)</li>
</ul>
<h3 id="-1-1-1-dll-might-not-have-been-updated-do-not-download-"><del>1.1.1 (DLL might not have been updated, do not download.)</del></h3>
<ul>
<li>Fixed CHANGELOG.md again... (Reminder, I'm getting sleep now.)</li>
</ul>
<h2 id="1-1-0-dayscalar-update-">1.1.0 (DayScalar Update)</h2>
<ul>
<li>Made things EXTREMELY compatible with other mods, so only if you have values changed from their default values will it actually apply ANY changes for that thing unless it is messes with another value that is modified that directly ties with it in the code.</li>
<li>Fixed DayScalar (It was originally supposed to be removed, but I accidentally left it in along with code that errors MapMultipliers (and WeatherMultipliers if enabled) because of some config values I also removed, it was because it needed more testing, but I will leave it as it is until 1.2.0.)</li>
<li>Readded my pre-release DayScalar values for each map.</li>
<li>Added DayScalar per weather type. (You could make Eclipses long and insufferable, great idea, yes yes.)</li>
<li>Fixed both README.md and CHANGELOG.md files to reflect recent changes.</li>
<li>I'm getting more than 5 hours of sleep! (Greatest feature... starting today.)</li>
</ul>
</details>
<details>
<summary>1.0.x (NOT RECOMMENDED FOR DOWNLOAD.)</summary>
<h3 id="-1-0-3-manual-instruction-fix-"><del>1.0.3 (Manual Instruction Fix)</del></h3>
<ul>
<li>Fixed the Manual Installation instructions for the fixed config file structure. No redownload/update required.</li>
</ul>
<h3 id="-1-0-2-default-config-fix-"><del>1.0.2 (Default Config Fix)</del></h3>
<ul>
<li>Fixed the default config files from being directly in the BepInEx/config folder, will now be in BepInEx/config/LethalUtilities upon download, I was sleep deprived and didn't see documentation, apologies for any inconveniences. Updates for v45 will be coming out soon.</li>
</ul>
<h3 id="-1-0-1-config-file-discrepancy-do-not-download-"><del>1.0.1 (Config file discrepancy, do not download.)</del></h3>
<ul>
<li>Moved all ConfigEnabled from ConfigSettings to each individual config for simplicity. It still won't execute any code other than the settings, which won't interfere with any mods.</li>
<li>Also added the default config files so you don't have to load the game up first.</li>
</ul>
<h1 id="1-0-0-release-">1.0.0 (Release)</h1>
<p>Funnily enough, more stable than every version up to 1.1.1.</p>
<ul>
<li>Initial release.</li>
</ul>
</details>
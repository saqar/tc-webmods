# Module: mod\_realmcore\_v2/mod\_realmcore\_v2\_simple #

Compatibility: Joomla 1.5.x<br>
Mod. version: 2.0<br>
Module name: Server Status<br>

<h2>How to install?</h2>

<ul><li>First you should make a clone of the repository.<br>
</li><li>Once you have the repository cloned, you must edit file "mod_realmcore.php" in either <b>"mod_realmcore_v2"</b> or <b>"mod_realmcore_v2_simple"</b> so it reflects your servers settings.</li></ul>

<b>Example:</b>
<hr />
<pre><code>// General server settings<br>
$address = "your.domain.name";<br>
// Enter your Core server IP or Domain<br>
$ip_world = "x.x.x.x";<br>
// Enter your Core server port (8085 = Deafult TC World Port)<br>
$port_world = "8085";<br>
// Enter your Realm server IP or Domain<br>
$ip_auth = "x.x.x.x";<br>
// Enter your Realm server port (3724 = Deafult TC Realm Port)<br>
$port_auth = "3724";<br>
<br>
and<br>
<br>
// MySQL settings<br>
$WoWHostname = "x.x.x.x"; // MySQL server address<br>
$WoWUsername = "user"; // MySQL username<br>
$WoWPassword = "pass"; // MySQL password<br>
$CharacterDatabase = 'characters'; // TC characters database<br>
$RealmDatabase = 'realmd'; // TC relamd database<br>
$WorldDatabase = 'world'; // TC world database<br>
$CharacterDatabaseEncoding = 'utf8'; // database character encoding<br>
</code></pre>
<hr />

<ul><li>Once done, save and close the file.<br>
</li><li>Archive the whole directory "mod_realmcore_v2" to file named "mod_realmcore_v2.zip".<br>
</li><li>Go to you website and login to Joomla Administrator, then go to "Extensions -> Install/Uninstall".<br>
</li><li>Now browse to your .zip as "Upload Package File" and hit "Upload".<br>
</li><li>If you didnt change anything else it should say "Module Installed Successfuly".<br>
</li><li>Now go to "Extensions -> Module Manager" and search for "Server Status" module, click on its name in the list to access settings.<br>
</li><li>Set "Position:" to right (nothing else will work at the moment, sorry).<br>
</li><li>Set "Order:" to be the last item listed and don't forget to set "Enabled:" to Yes.<br>
</li><li>Click "Save" and voila, you have Server Status on your Joomla page.
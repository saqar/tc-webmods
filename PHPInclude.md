# How to use modules on PHP powered web site? #

Compatibility:
**PHP 5+**<br>
This guide applis to the following modules:<br>
<ul><li><b>Server Status</b> (mod_realmcore_x)<br>
</li><li><b>Top Richest</b> (mod_richest)</li></ul>

<h2>Usage Instructions</h2>

<h3>Installation:</h3>
<ul><li>First make a clone of the repository.<br>
</li><li>Once you have the repository cloned, you must edit file "mod_realmcore.php" in either "mod_realmcore_v2" or "mod_realmcore_v2_simple" so it reflects your servers settings.<br>
</li><li>Upload the whole folder (mod_realmcore_v2 or mod_realmcore_v2_simple) in the root folder of your web page.<br>
</li><li>Open a .php page on which you want this module to be shown on.<br>
</li><li>Use PHP include to place the module where you want it on the web site.<br></li></ul>

<b>PHP include example:</b>
<ul><li>Open "index.php"<br>
</li><li>Add the following line on your page where you want the module to be shown:<br>
<pre><code>&lt;?php include 'mod_realmcore/mod_reamcore.php' ?&gt;<br>
</code></pre>
</li><li>Save and close "index.php".<br>
</li><li>Upload to your web server and watch the results.
# BanglaTranslationForTWRP - A effort to make TWRP Recovery accessible for Bengali Language

<br />
<br />

If you would like to translate TWRP custom Recovery in Bengali Language, than it is right place!

<br />

Just edit the bd.xml file and provide translation and make a pull request. I will than review and marge in master brench if your translation is good. <br />
<br />
For your refernce I have added english translation of this Recovery Image. You have to edit and provide bengali translation.

<br />

<b>Some notes: </b> Do not change String string Strating with % and followed end by % for instance: 
<pre><code>%tw_version%</code></pre> as this will creates problem and never show right information associated with this String, instead It will show static String what you have written.

<br />

To work with such String or values for instance: 

<pre><code><string name="twrp_watch_header">TWRP %tw_version%</string></code></pre> 

This means this String Will show Current TWRP version on screen. To provide a bengali Translation for this, We can do following:

<pre><code><string name="twrp_watch_header">টিডাব্লুআরপি %tw_version%</string></code></pre> 

I hope you got it!

<br />
<b> As soon this translation is completed, I will soon share a TWRP recovery that will support Bengali Language, Stay Tuned. </b>



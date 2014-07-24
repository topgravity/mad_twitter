Mad Twitter jQuery Plugin
===========

<div id="how-to-use">
<p>Mad twitter is a highly user friendly button, that produces different animations on hover effect. Six different effects makes the twitter angry and it goes wild, which is the most interesting feature of mad twitter button. </p>

<strong><a href="http://topgravity.com/mad-twitter-jquery-plugin/">Demo</a></strong>

<h2>How to use</h2>
<p>Mad twitter is an easy to use jquery plugin. A css file must be included to make it work properly.
	<br>
	<div id="code-cantainer">
	<code>
	 &lt;link href="css/mad_twitter.css" rel="stylesheet" media="all" /&gt;<br>
    </code>
</div>

Any latest version of jquery works perfectly, it can be added easily.
<div id="code-cantainer">
<code>
&lt;script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"&gt;&lt;/script&gt;
</code>
</div>
A separate js file is added with the demo content in case if user don't want to make hands dirty with code. The file <code>mad_twitter.js</code> will work perfectly. 
</p>

<h3>HTML</h3>
<p>
<div id="code-cantainer">
<code>
&lt;div class="mad_twitter" id="mad_twitter_1"&gt;<br>
&lt;ul&gt;<br>
  &lt;li id="written"&gt;Follow us&lt;/li&gt;<br>
  &lt;li id="twitter"&gt;&lt;center&gt;&lt;i class="fa fa-twitter fa-2x"&gt;&lt;/center&gt;&lt;/i&gt;&lt;/li&gt;<br>
&lt;/ul&gt;<br>
&lt;/div&gt;<br>
</code>
</div>
</p>

<h3>Script</h3>
<div id="code-cantainer">
<code>
       $("#mad_twitter_1").hover(function(){<br>
          $("#mad_twitter_1 .fa-twitter").toggleClass("magictime foolishIn");
        <br>});
</code>  
</div>

<h2>Change Animation</h2>
<p>There are six unique animations and can be chaged as follows;<br>
Insead of using "follishIn" in the above script user can use following animations
   <ul>
       <li>twisterInDown</li>
       <li>magic</li>
       <li>bombLeftOut</li>
       <li>tinUpIn</li>
       <li>tinRightOut</li>
   </ul>
Just add any of the above classes on hover, and it will give make twitter angry. );
</p>

<h2>Usage</h2>
<p>
Mad Twitter is created by <span><a href="http://topgravity.com/">Top Gravity</a></span>, licensed under MIT and is free to use.
</p>

</div>

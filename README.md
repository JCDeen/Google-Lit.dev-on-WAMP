# Google-Lit.dev-on-WAMP

Read the source in deen.html to see exactly how this was installed on a typical WAMP setup on Windows 10 PC.

The code in <b>deen.html</B> yields the screen seen below, after the gray horizontal rule, in a Firefox browser.<br />
The code in <b>deen-using-cdn.html</b> does the same as <i>deen.html</i>, but imports the <i>lit.dev</i> code from a CDN, and therefore avoids the need to run npm to install lit.dev.<br />

<p>The code in <b>deen-using-cdn-timers.html</b> is the timers example from <i>lit.dev</i>, and it also imports the <i>lit.dev</i> code from a CDN.<br>
  It also requires the two files <b><i>icons.js<i></b> and <b><i>my-timer.js</i></b> . The CDN </i>(Content Delivery Network)</i> is pulled in by those two Javascript files. <i>The "timers" code is found at <a HREF="https://lit.dev/docs/#what-is-it-like-to-develop-with-lit" target="_blank"> https://lit.dev/docs/#what-is-it-like-to-develop-with-lit</a></i>
</p>
All 3 of those example HTML files ran perfectly on my WAMP installation on Windows 10. <i>(as of 12/07/2022)</i>

<hr >
<img src="lit.dev-rendered.png">

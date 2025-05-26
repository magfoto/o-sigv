# o-sigv
Configuration support repository for sigv: https://magfoto.itch.io/sigv

<p>NOTE: <em>To use&nbsp;<strong>o-sigv</strong>&nbsp;(below) it is perhaps required that you get&nbsp;familiar with&nbsp;<a href="https://100r.co/site/orca.html" target="_blank">Orca</a>&nbsp;first.</em>
    </p>
<p>As a live coder, I primarily use <a href="https://100r.co/site/orca.html" target="_blank">Orca</a>, a popular live coding language by <a href="https://100r.co/" target="_blank">Hundred Rabbits</a>. I&nbsp;have added 8 additional operators to the original Orca operators with the following characters:<br></p>
<table><tbody><tr><td>`</td><td>ANIM</td><td><br></td></tr><tr><td>|</td><td>MAT</td></tr><tr><td>^</td><td>TRANS</td></tr><tr><td>_</td><td>AUDIO</td></tr><tr><td>º</td><td>LIGHTS</td></tr><tr><td>&hellip;</td><td>SYSTEM</td></tr><tr><td>∆</td><td>SERIAL</td></tr><tr><td>∞</td><td>CHAO</td></tr><tr><td>ß</td><td>BUFFER</td></tr></tbody></table>

<p>Here is the o-sigv table I&nbsp;created for entering the operators and their values:&nbsp;<a href="https://magfoto.dev/nbcli/table.html" target="_blank">https://magfoto.dev/nbcli/table.html</a>.
    </p>
<p><strong>Hello Monde
</strong>To start using o-sigv (Orca + sigv together):
    </p>
<ol><li>Launch sigv.app (this will likely trigger permission prompts, and more will come)
</li><li>Launch  Orca (that uses custom library.js above and normally located in the  Orca.app/Contents/Resources/app/sources/scripts/core directory of the  application).
</li><li>In Orca, launch the commander (CMD+K) and enter the OSC command and address to use:&nbsp;<strong>osc:4444</strong>.
</li><li>Now  you're ready to use the new operators, begin anywhere on the grid with  (this will open a window of 1800x1169 in size, will update this soon): 
<strong>&hellip; n 5</strong>
</li><li>Somewhere else on the grid write:
<strong>&hellip; n 0</strong>
</li><li>Next, somewhere else on the grid write: 
<strong>` r 0 0 0</strong>
</li></ol>
<p>Triggering the Orca code of step 4 loads a display window, and triggering step 5&nbsp;loads an sigv primitive called <strong>geo</strong>.  Triggering the step 6 code reveals the geo primitive as&nbsp;a wireframe 3D  plane, by setting the objects' rotation xyz values to 0 0 0.
</p>
loopdir
=======

Execute a bash command in multiple directories at once

###Usage

<pre>
loopdir [-R] &lt;cmd&gt; [&lt;dir&gt;]
</pre>

Loop through the directories in the current directory, or, optionally, the specified directory, `dir`. Change into each directory and execute `cmd`. Optionally, do this recursively inside each directory using the `-R` flag.
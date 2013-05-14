loopdir
=======

Execute a bash command in multiple directories at once

###Usage

<pre>
	loopdir [-R] &lt;cmd&gt; [&lt;dir&gt;]
</pre>

Loop through the directories in the current directory, or, optionally, the specified directory, `dir`. `cd` into each directory and end execute `cmd`. Optionally, do this recursively inside each directory.
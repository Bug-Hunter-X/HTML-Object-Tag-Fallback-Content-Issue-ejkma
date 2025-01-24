# HTML Object Tag Fallback Content Issue

This repository demonstrates an uncommon bug related to the HTML &lt;object&gt; tag and its fallback content.  When embedding PDFs (or other files) using &lt;object&gt;, if the browser does not recognize the MIME type, the fallback content (typically shown within the &lt;object&gt; tags) might not display as expected.

The bug is reproduced in `bug.html`.  The solution is provided in `solution.html`.
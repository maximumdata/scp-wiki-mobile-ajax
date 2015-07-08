# scp-wiki-mobile-ajax
I love reading the SCP wiki, especially before I fall asleep. It's a great repository of short form horror stories, all set within the same loosely coherent universe. Check it out!

The problem is, the site uses wikidot, which has had a pretty bad mobile layout since Google's mobile-friendly update.

This small, self-hosted app uses ajax and forced insertion of CORS headers to pull in data from the wiki (their API is a mess), and display it in a more mobile friendly way.

It's not styled intentionally. If you'd like to use this yourself, you can style the output by starting with targeting `#viewer`. That's where all of the HTML output is deposited.

Cheers!

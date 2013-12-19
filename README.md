
License Distribution
====================

License Distribution is a WordPress plugin that allows an admin to create, distribute and manage user license for thier products.

KNOWN BUGS
==========

	- For some reason when setting the header to JSON in the API a server "Header already sent is displayed". This should not be an issue but for some reason there is output before setting the header.

		ACTIONS TAKEN
		-------------

			Commented out setting the header to JSON. Return on call in not HTML and not JSON.

		SOLUTION
		--------

			Remove output or possibly buffer output before setting the header. Patch will be realesed as soon as the fix in place and is stable.

	- Not able to parse the post meta on occasion. Not sure why yet

CHANGELOG
=========

	1.0.0
	-----
		- Inital stable release.
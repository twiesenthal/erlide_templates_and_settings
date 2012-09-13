erlide_templates_and_settings
=============================

Templates for the erlide eclipse plugin (I will add the settings later)

Basic usage:
-------------
	0. Download and install eclipse (http://www.eclipse.org/downloads/)
	1. Install erlide (http://erlide.org/#installation)
	2. In Eclipse open "Windows -> Preferences -> Erlang -> Editor -> Templates
	3. Import templates.xml from this repository

Advanced (?) usage:
--------------------
If you want to change the templates yourself, take a look at the src/*/ folders. The module templates have an .erl extension so you can edit them in your favorite editor (erlide?) with syntax highlighting.

I've created some basic tests, which try to compile and create docs for each module template.

Once you're done editing the template sources run "make", which will run the tests and will afterwards convert the sources to an xml file you can import into erlide again.

ToDos:
--------
- Bring my settings into an "importable" form

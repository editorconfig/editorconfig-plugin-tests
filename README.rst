Tests for EditorConfig Plugins
==============================

There is currently no way to automate tests for EditorConfig plugins like there
is for the EditorConfig core libraries.  This repository contains instructions
to help developers manually test their EditorConfig plugins.

Running Tests
-------------

The ``tests`` directory contains instructions for testing various EditorConfig
properties.  The ``test_files`` directory contains the test files referenced in
these instructions.

Tests should be run by opening up each relevant file in the ``tests``
directory, running through the tests in the file and verifying that the
expected behavior is observed.

After running each test the files in the git repository should be reverted and
any newly created files should be deleted.  To revert files in the git
repository use:

	git checkout -- test_files/

License
-------

This work is licensed under the Creative Commons Attribution 4.0 International
License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/
or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

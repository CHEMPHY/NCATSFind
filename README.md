NCATSFind
=========

In process of merging firefox and chrome into single extension
Interim build:
	Chrome:
		run build script
		run 1-3 above, and select "chrome_bundle"
	Firefox:
		run build script
		use sdk tools in "firefox_bundle"
		
====LEGACY====

Chrome plugin for resolving / rendering chemical structures from names and images.

To deploy on chrome:

	1) In a chrome browser, navigate to : chrome://extensions/
	2) Make sure "Development Mode" is selected
	3) Click "Load unpacked extension..."
	4) Find the src directory of this project, and select it

Chrome will then "compile" and install the extension. 

You can alternatively package the extension as a crx file in the same tab. Installation then requires dragging the crx file from an explorer window into the extensions window.

		
Feed Reader Testing
===================

This project uses [Jasmine](https://jasmine.github.io) to test the functionality of a feed reader.

## How to run
* Download the Github zip file or clone the repository.
* Open the index.html file in a browser.

## List of testing
* RSS Feeds
	* are defined
	* each feed should have a url, and the url should not be null
	* each feed should have a name, and the name should not be null
* The menu
	* should be hidden by default
	* A spy, when clicked the menu icon
		* when clicked shows the menu, when clicked again hides the menu
* Initial Entries
	* .feed container should have at least 1 .entry element
* New Feed Selection
	* when new feed selected the content should change


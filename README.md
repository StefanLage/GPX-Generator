GPX-Generator
=============

This is a script to generate a GPX file, kind of file used to simulate a location with Xcode.

How To Use
----------

gpx-generator required some arguments:

	-	-ci , --city
	-	-co , --country
	
and others optionals :

  	-	-o , --output 		Output file name
  	-	-p , --path 		Path to save gpx generated
  	-	-pc, --postalcode

Here is a simple example of how to use gpx-generator:

	python gpx-generator.py -ci "San Francisco" -co USA -o MyFile -p "MyPath"
Cordova Config Properties
=========================

Not all properties displayed on the Phonegap website are actually usable. Some are only usable if your use PhoneGap build. The purpose of this repo is to keep a list of all found properties that are actually being used by scanning Cordova's source code for each platform.

One notable property that exists for PhoneGap build but not for CLI is the Orientation property.

The properties for each platform can be found in an XML file in this repo. I've done my (almost) best to describe each property.

When you read through the property list, you'll also find some properties that can't even be found on PhoneGaps's website.

Currently only two platforms have been scanned:

* [Android](android.xml)
* [iOS](ios.xml)

Feel free to fork this, make updates, and do a pull request.

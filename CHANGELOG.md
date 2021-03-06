0.7.0 (Apr 19 2018)
-----
- Added the ability to retrieve the resulting Bitmap for custom use on your RecordBuilder
- Removed the runtime dependency on Dexmaker, this will resolve any issues of using frameworks such as Mockito in your screenshot tests
- Added a a check to fail when resultant screenshots are extremely large
- Rewrote the client plugin to provide screenshot test tasks per applicable variant
- Re-license to Apache 2

0.6.0 (Feb 06 2018)
-----
- Added the ability to run screenshot tests on multiple devices at once
  - Set `multipleDevices` to `true` in your `screenshots` config in your Gradle file to enable this.
- The core module no longer depends on junit
- Upgraded to Gradle 4.4.1
- Removed R and BuildConfig classes from release artifacts
- Added a Buck file for the Python module

0.5.0 (Nov 20 2017)
-----
- Upgraded to AGP 3
- Upgraded to Gradle 4.3
- Added layout-hierarchy-litho module for Litho support in LayoutHierarchy dumps
- Rewrote the entire Layout Hierarchy dump system
- Added more TextView information in hierarchy output
- Added a param for custom Python executables
- Fixed WindowAttachmentTest for API 26+
- Implemented a view hierarchy overlay for screenshots
- Changed the dump output to use JSON instead of XML
- Spruced up the results page (#117)
- Added a dark background toggle button (#116)

0.4.3 (Jul 13 2017)
-----
- Added more examples
- Fixed a longstanding issue where we showed a horizontal break in the screenshots every 512 pixels.

0.4.2 (Sep 28 2016)
-----
- Support for Android gradle plugin 2.2.0
- Make ViewHierarchy dump more useful information

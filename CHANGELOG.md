5/3/2021: v0.1
	- Bug 1: v0.1's '.cs' file extension battery is missing data.
	
5/4/2021: v0.2
	- Fixed bug 1 from v0.1.
	- Added this CHANGELOG.md.
	- Added TODO.md.
	- Added '.gradle', '.json', '.properties', '.xml', and '.yml' extensions.
	- Created 'results' folder. This will contain subfolders with version numbers, each of which will contain subfolders of the secret scanning solutions ran against that version. These will contain information, and possibly raw output from the tooling, about the performance. To be standarized further in the future.
    - Uploaded first results, these are from GitGuardian, which notified me automatically over email shortly after I uploaded v0.1.

5/7/2021: v0.3
	- Added gitignore, currently just a set of API keys that shouldn't be shared
	- Added a big change to the battery, a new folder of files that contain one secret per line. This is to overcome limitations on some tools of a detection cap.
	- Added some stuff to TODO

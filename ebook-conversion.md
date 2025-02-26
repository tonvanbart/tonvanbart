## Converting downloaded Kindle ebooks

For future reference, as of 26-02-2025 apparently it is no longer possible to download ebooks from the Amazon website; go 
to [your books](https://www.amazon.nl/hz/mycd/digital-console/contentlist/booksSamples/dateDsc?pageNumber=1) and for each book choose
"More Actions" --> "Download and transfer via USB".

This page is a quick recap of https://epubor.com/3-ways-to-remove-drm-from-kindle-books.html, in case that one goes away; following method 1 "Remove DRM with Calibre plugin".
Tried these steps and was able to convert one of my own purchased ebooks from `.azw3` to PDF format at least.

Steps after downloading the ebooks:
1. install Calibre from the [download page](https://calibre-ebook.com/download)
2. download [DeDRM_tools](https://github.com/noDRM/DeDRM_tools/releases/download/v10.0.9/DeDRM_tools_10.0.9.zip) and unzip the archive somewhere - the zip contains another zip which is the actual plugin, leave that as is
3. download [KFX Input.zip](https://www.mobileread.com/forums/attachment.php?attachmentid=213770&d=1740055683), do not unzip
4. start Calibre, do not import ebooks; under "preferences" find "change Calibre behavior", find "Plugins" under "Advanced" and click "Load plugin from file".
5. do this for the plugin zip insize the unzipped DeDRM archive, and for the KFX Input zip.
6. restart Calibre, go to plugins again, find the DeDRM plugin (under "file type"), click "customize plugin" and enter the serial number of your (pre 2024) Kindle device under "eInk".
7. import the ebooks, you should be able to convert them now.

Bonus: [this article](https://www.tomsguide.com/tablets/e-readers/no-kindle-no-problem-5-places-to-buy-drm-free-e-books) on Tom's Guide has several links to sources of DRM-free ebooks (`.epub`). [Howto-geek](https://www.howtogeek.com/these-are-the-best-sites-for-drm-free-ebooks-and-comics/) has another one.


   

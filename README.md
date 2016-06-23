# Liferay-6.2-with-Bootstrap-3.x-theme (Currently Bootstrap 3.3.6)

This project provide one of ways to remove Bootstrap 2.3.2 from Liferay 6.2 and use Bootstrap 3.x.
For this I created a new directory called "bs3" into AUI directory, here "Bootstrap 3 SASS" files are placed, and two custom files:

+ _bs2_extender.scss: This file extend Bootstrap 2.3.2 classes with equals from Bootstrap 3.x
+ _bs_liferay_fixes.scss: some fixes in Liferay componets based on BS2

This theme does not require any change in portal code, it is only a Liferay 6.2 theme.

## Using these CSS files in a Lieray theme

- If you are using new SDK based on Gulp, please, copy CSS files to *src/css*
- If instead you are using the normal SDK, please, copy CSS files to *_diffs/css*


![Example of this theme applied in Liferay 6.2 GA6](https://raw.githubusercontent.com/marcoscv-work/Liferay-6.2-with-Bootstrap-3.x-theme/master/Liferay_6.2_with_BS3_preview.gif)

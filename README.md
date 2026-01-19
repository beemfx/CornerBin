# CornerBin

[CornerBin - The system tray recycle bin.](https://www.beemsoft.com/CornerBin)

&copy; 2011 Beem Media. All rights reserved.

CornerBin was originally release on SourceForge.net
(http://cornerbin.sourceforge.net), but going forward this is the official
release, though I don't think the application will change since I've been using
it since 2011 and haven't had any issues.

## Building

The environment variable BEEMOUT should be set prior to building. This variable 
determines where the compiled data is built to. Go to advanced system settings
->environment variables and set BEEMOUT=D:\CornerBinOut (or similar).

The Release build will copy the executable back to the dist directory.

CornerBin uses MFC so you must install MFC alongside Visual Studio. This is
included with Visual Studio 2015 Community Edition, but is not installed by
default so make sure to run the Visual Studio setup utility with that option
checked. (You can modify existing Visual Studio 2015 installations to install
this.)

## License
CornerBin was originally licensed under GNU General Public License (GPL), but
going forward its license is goverened by the the LICENSE file. (Which as of
this README being updated is the MIT license.

CornerBin uses IconDlg by PJ Naughter. That source code is licensed according to
CornerBin/IconDlg/README.TXT and also as described on http://www.naughter.com.
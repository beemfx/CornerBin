# [CornerBin - The System Tray Recycle Bin](https://www.beemsoft.com/CornerBin)

&copy; 2011 Beem Media. All rights reserved.

CornerBin was originally release on SourceForge.net
(http://cornerbin.sourceforge.net), but going forward this is the official
release, though I don't think the application will change since I've been using
it since 2011 and haven't had any issues.

## Building

CornerBin is now built with Visual Studio 2022. Open CornerBin.sln and build the CornerBin project. The project will be built to the _BUILD directory.

The Release version will be copied to the _DIST directory.

CornerBin requires MFC so you must install MFC alongside Visual Studio. This is
not installed by default so make sure to run the Visual Studio setup utility with that option
checked. (You can modify existing Visual Studio installations to install this.)

## License
CornerBin was originally licensed under GNU General Public License (GPL), but
going forward its license is goverened by the the LICENSE file. (Which as of
this README being updated is the MIT license.)

CornerBin uses IconDlg by PJ Naughter. That source code is licensed according to
CornerBin/IconDlg/README.TXT and also as described on http://www.naughter.com.
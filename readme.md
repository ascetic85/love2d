LÖVE is an *awesome* framework you can use to make 2D games in Lua. It's free, open-source, and works on Windows, Mac OS X and Linux.

Documentation
-------------

We use our [wiki][wiki] for documentation.
If you need further help, feel free to ask on our [forums][forums], and last but not least there's the irc channel [#love on OFTC][irc].

Compilation
-----------

###Windows
Use the project files for Visual Studio 2010 located in the platform dir.

###*nix
Run platform/unix/automagic, then run ./configure and make.

###OSX
Use the XCode project in platform/macosx.

For both Windows and OSX there are dependencies available [here][dependencies].

Repository information
----------------------

We use the 'default' branch for development, and therefore it should not be considered stable.
Also used is the 'minor' branch, which is used for features in the next minor version and it is
not our development target (which would be the next revision). (Version numbers formatted major.minor.revision.)

We tag all our releases (since we started using mercurial), and have binary downloads available for them.

Builds
------

Releases are found in the 'downloads' section on bitbucket, are linked on [the site][site],
and there's a ppa for ubuntu, [ppa:bartbes/love-stable][stableppa].

There are also unstable/nightly builds:

- For windows they are located [here][winbuilds].
- For ubuntu linux they are in [ppa:bartbes/love-unstable][unstableppa]
- For arch linux there's [love-hg][aur] in the AUR.
- For other linuxes and OSX there are currently no official builds.

Dependencies
------------

- SDL	- 各平台事件支持
- OpenGL- 渲染支持
- OpenAL- 音频支持
- Lua / LuaJIT / LLVM-lua 	- Lua 支持
- DevIL with MNG and TIFF	- 图片读取, [cimg][cimg] ?
- FreeType					- 字体支持
- PhysicsFS					- 虚拟文件系统支持(zip,..)
- ModPlug					- 音乐
- mpg123					- 音乐
- Vorbisfile				- 音乐

[site]: http://love2d.org
[wiki]: http://love2d.org/wiki
[forums]: http://love2d.org/forums
[irc]: irc://irc.oftc.net/love
[dependencies]: http://love2d.org/sdk
[winbuilds]: http://love2d.org/builds
[stableppa]: https://launchpad.net/~bartbes/+archive/love-stable
[unstableppa]: https://launchpad.net/~bartbes/+archive/love-unstable
[aur]: http://aur.archlinux.org/packages.php?ID=35279
[cimg]: http://cimg.sourceforge.net


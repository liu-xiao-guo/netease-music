This is the snap application for the most famous netease cloud music application. 

The original deb comes from:

http://s1.music.126.net/download/pc/netease-cloud-music_1.0.0_amd64_ubuntu16.04.deb

Known issues:
  - the current snap file is a little big. If using platform interface, there is an error like:

 (process:16273): Gtk-WARNING **: Locale not supported by C library.
	Using the fallback 'C' locale.

Currently, the platform interface is not used

You can install the app from the store:

sudo snap install netease-music —devmode —beta

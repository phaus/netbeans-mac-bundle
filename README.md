# Netbeans 9.0 Mac OS App Bundle

## Download the latest release

* Go to the [Netbeans Download Page](http://netbeans.apache.org/download/index.html)
* Download the most recent release (e.g. [9.0 beta](http://netbeans.apache.org/download/nb90/nb90-beta.html))
* Extract the Archive
* Copy the content of `netbeans/` to `NetBeans\ 9.app/Contents/Resources/NetBeans/`

## Create the Icon

* Download the Image from [here](https://blogs.apache.org/netbeans/entry/new-apache-netbeans-incubating-logo).
* Save it as `icons/Icon1024.png`.
* Run `source CreateICNS.src` => the file `netbeans.icns` will be created.
* Copy `netbeans.icns` to 
  * `NetBeans\ 9.app/Contents/Resources/netbeans.icns`
  * `NetBeans\ 9.app/Contents/Resources/NetBeans/nb/netbeans.icns`
* Copy `icons/Icon1024.png` to `NetBeans\ 9.app/Contents/Resources/NetBeans/nb/netbeans.png` (optional: resize it to 64x64).

You are done!



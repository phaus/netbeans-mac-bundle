# Netbeans 10 Mac OS App Bundle

Follow these steps to create the Mac OS app bundle for the NetBeans application.

* Go to the [Netbeans Download Page](http://netbeans.apache.org/download/index.html)
  and download the most recent release.

* Extract the archive, this will create a `netbeans` directory.

* Copy the content of `netbeans` to the `NetBeans` resources directory:

  ```
  cp -pRH netbeans/* NetBeans\ 10.app/Contents/Resources/NetBeans/
  ```

* Copy the application icon to the root of the resources directory:

  ```
  cp -p NetBeans\ 10.app/Contents/Resources/NetBeans/nb/netbeans.icns NetBeans\ 10.app/Contents/Resources/
  ```

* Move the NetBeans 10 application to your Applications folder:

  ```
  sudo mv NetBeans\ 10.app /Applications
  ```

You are done!

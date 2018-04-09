# imdisk-ramdisk
personal fork of http://www.ltr-data.se/opencode.html/#ImDisk


#### Additional build advice from @boomsya
```
boomsya commented on Feb 16
hi. thanks for answer:

download file http://www112.zippyshare.com/v/ZlWKKl7Y/file.html - here is very helpful CMD file to configure WINDDK Builder
i was copied this file to C:\WinDDK\7600.16385.1\bin
inside CMD file i was configure path set BASEDIR=%SystemDrive%\winddk\7600.16385.1
run CMD and select 1-2-3-4 to build x32 version or 5-6-7 to x64
at second question in CMD (Checked(1) or Free(2)) select 2 for release and 1 for debug version. I was selecting always Free
cmd configuring builder and start WINDDK builder in second console window
go to project directory (e.g. cd d:\project)
type "build" ad press enter
exit from winddk and run file d:\project\install.cmd with disabled signature check in windows x64
run file d:\project\cpl\amd64\imdisk.cpl or \i386\imdisk.cpl
```

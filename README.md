# Zoom-dll-hijacking
A dll injection vulnerability in zoom meeting &lt; 5.1.3
<br />
### Affected Windows version
Windows 7 or less
<br/>
Windows Server 2008

### Usage
* Copy the `dbghelper.dll` and `SHCore.dll` to following location
  `C:\Users\$user\AppData\Roaming\Zoom\bin\`
* Start the zoom application or do any activity like turning on/off camera inside zoom meeting.

 **Note**: You can modify the code of SHCore.dll by opening `shcore dll.sln` project in Visual studio.
 <br/>
 **Reference**: https://blog.0patch.com/2020/07/remote-code-execution-vulnerability-in.html

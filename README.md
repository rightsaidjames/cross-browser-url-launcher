# Cross-browser URL launcher
Need to quickly test a URL (or site) in **ALL THE BROWSERS**? This repository is for you. 

Windows-only (batch file) for now, but other scripting languages and operating systems to follow. Also in the pipeline is the ability to launch more than one URL from a single command.

# Usage

Navigate to the directory where you've put the script, then:
```batch
url-builder http://testers.io
```

If you don't want to test in a certain browser, remove that line from the script.

If you leave out the protocol (`http://`, `https://` etc.) then it won't work in Microsoft Edge. All other browsers don't care about the protocol.

# Credits

Thanks to fellow testers on the [Testers.io Slack](http://testers.io) #tools channel for suggesting an approach and help with batch files and/or command line options for browser launching:
* Dominic Kua - [@dominic-kua](https://github.com/dominic-kua)
* Gustavo Rivera - [@gustavoriveray](https://github.com/gustavoriveray)

Also [this StackOverflow thread](http://stackoverflow.com/questions/31164253/how-to-open-url-in-microsoft-edge-from-the-command-line) for giving me the correct syntax for Microsoft Edge.


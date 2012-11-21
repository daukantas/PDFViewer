##PDFViewer for Cordova iOS

Usage is exactly like ChildBrowser except you send a bundled pdf file name instead of an external url

    <button onclick="cordova.exec('PDFViewerCommand.showPDF', 'CordovaBot.pdf');">Click to open  CordovaBot.pdf!</button>

    <button onclick="cordova.exec('PDFViewerCommand.showPDF', 'readme.pdf');">Click to open  readme.pdf!</button>



Add PDFViewerCommand | PDFViewerCommand to Cordova.plist

![image](https://raw.github.com/RandyMcMillan/PDFViewer/master/Cordova.plist.png)

This code is completely dependent on the Apache Cordova (formerly PhoneGap) project, hosted on [GitHub](https://github.com/RandyMcMillan/PDFViewer)

The MIT License

Copyright (c) 2012 Randy McMillan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
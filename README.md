# Barcode Scanner App

<p> The API works with static images and live video use cases. During live video, the API will leverage output from previous frames to return smoother segmentation results.</p>
<p>With ML Kit's barcode scanning API, you can read data encoded using most standard barcode formats. Barcode scanning happens on the device, and doesn't require a network connection. </p>
<p>arcodes are a convenient way to pass information from the real world to your app. In particular, when using 2D formats such as QR code, you can encode structured data such as contact information or WiFi network credentials. Because ML Kit can automatically recognize and parse this data, your app can respond intelligently when a user scans a barcode.  </p>

<img src="https://raw.githubusercontent.com/icanerdogan/BarcodeScannerApp-MLKit/master/Documents/Barcode%20Scanner%20Banner.png">

<h2> Key capabilities </h2>
<ul>
<li>Linear formats: Codabar, Code 39, Code 93, Code 128, EAN-8, EAN-13, ITF, UPC-A, UPC-E</li>
<li>2D formats: Aztec, Data Matrix, PDF417, QR Code</li>
<li>Scan for all supported barcode formats at once without having to specify the format you're looking for, or boost scanning speed by restricting the detector to only the formats you're interested in.</li>
<li>Structured data that's stored using one of the supported 2D formats is automatically parsed. Supported information types include URLs, contact information, calendar events, email addresses, phone numbers, SMS message prompts, ISBNs, WiFi connection information, geographic location, and AAMVA-standard driver information.</li>
<li>Barcodes are recognized and scanned regardless of their orientation: right-side-up, upside-down, or sideways.</li>
<li>Barcode scanning is performed completely on the device, and doesn't require a network connection.</li>
</ul>

<h2> Barcode Scanner App Preview </h2>

Main Screen       |  Info Screen
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/icanerdogan/BarcodeScannerApp-MLKit/master/Documents/App%20Image%20-%201.png)  |  ![](https://raw.githubusercontent.com/icanerdogan/BarcodeScannerApp-MLKit/master/Documents/App%20Image%20-%202.png)

<h2> LICENSE </h2>

````
MIT License

Copyright (c) 2023 İbrahim Can Erdoğan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

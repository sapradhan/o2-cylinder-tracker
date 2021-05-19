# o2-cylinder-tracker

Simple form aid quick check in/check out of oxygen cylinders. QR codes will be put oxygen cylinder. Those QR codes will be scanned on refill depos and/or hospitals. This will create a stream of data - which cylinder was where at what time. This data stream can be used later to answer questions like which cylinder is out of circulation, what is the churn rate of cylinders etc.

Uses [Web Media Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API) to access device camera and [jsQR](https://github.com/cozmo/jsQR) to scan. [Geo location API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) for location

Web media capture and Geo location requires site to be served over `https` to work.


[Try it](https://alliance4nep.github.io/o2-cylinder-tracker/)

![https://alliance4nep.github.io/o2-cylinder-tracker/](https://chart.googleapis.com/chart?chs=200x200&cht=qr&chl=https://alliance4nep.github.io/o2-cylinder-tracker/&chld=L|1&choe=UTF-8)


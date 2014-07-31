Gonalytics (tracking script)
==========================

Gonalytic is a open source web analytics application. It consists of:
- tracker: https://github.com/piotrkowalczuk/gonalytics-tracker
- tracking script (this repository)
- dashboard: https://github.com/piotrkowalczuk/gonalytics-dashboard

Installation
------------
    <script type="text/javascript" src="/path-to/gonalytics.min.js"></script>
    var gonalytics = new Gonalytics('http://tracker.addres', siteId);
    gonalytics.push();

Grunt tasks
--------

#### Build

    grunt

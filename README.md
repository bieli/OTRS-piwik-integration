OTRS-piwik-integration
======================

OTRS 3 package for Piwik Open Web Analytics [http://piwik.org/] Integration.
This package adding tracking code into footer for

About PIWIK
----------
[http://www.slideshare.net/matthieua/piwik-presentation] - PIWIK presentation
[http://en.wikipedia.org/wiki/Piwik] - More information
[http://demo.piwik.org/] - Online demo
[http://www.statstory.com/some-reasons-to-choose-piwik-analytics-over-google-analytics/] - Some Reasons To Choose Piwik Analytics over Google Analytics

How to install PIWIK extension package in OTRS 3 ?
--------------------------------------------

from console:
/opt/otrs/$ perl bin/otrs.PackageManager.pl -a install -p ./OTRS-piwik-integration.opm

from admin panel:
http://OTRS-LOCATION/otrs/index.pl?Action=AdminPackageManager


How to build OTRS package from source ?
----------------------------------
/opt/otrs/$ perl bin/otrs.PackageManager.pl -a build -p <BASE_PATH>/OTRS-piwik-integration/src/OtrsPiwikIntegration.sopm -d <BASE_PATH>/OTRS-piwik-integration/src/
...
Writing /tmp/OtrsPiwikIntegration-1.0.0.opm

/opt/otrs$ ls /tmp/OtrsPiwikIntegration-1.0.0.opm -a
/tmp/OtrsPiwikIntegration-1.0.0.opm

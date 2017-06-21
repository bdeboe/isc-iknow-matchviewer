# isc-iknow-matchviewer
A sample interface for browsing match results for a given page. Compatible with 2017.1 and up (requires iKnow REST APIs).

To set up the associated REST interface (extending the default iKnow one), use the following command:
```
do ##class(Demo.MatchViewer.Utils).Setup()
```

Then access the results for a given domain with id 12 and source with id 345:
http://localhost:57772/csp/matching/MatchViewer.csp?namespace=matching&domain=12&source=345

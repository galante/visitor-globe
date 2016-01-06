# visitor-globe

SMS Sending Visualizer
This is a tool which shows the Emarsys SMS traffic on a rotating globe.  This tool takes a mobile number from a REST API, validates the mobile number and places a marker on the globe


Usage

<monospace>
curl https://sms-global.herokuapp.com/phonenumber/+1-847-254-9151
result
{"data":{"timestamp":"2016-01-06T18:17:24.213Z","latitude":37.09024,"longitude":-95.712891,"country":"United States","RegionCode":"US","valid":true,"isMobile":true}}Davids-MacBook-Pro-3:visitor-globe dgalante$ 
</monospace>

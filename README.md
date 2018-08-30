# Splunk_Forwarder_Troubleshooter
Help troubleshoot forwarders: Version, last contact, xfer rates, 'interesting' messages and other bits

Many pieces of data on the page, including the throughput by sourcetype panel, will require metrics logs *from your forwarders* being searchable.

**Panel 1**: host name, IP, Splunk version, last indexer to receive data, number of indexers receiving, number of indexers that returned data for this forwarder for this search, outputs defined, depliyment server, event rate, and KBps

**Panel 2**: Throughput by sourcetype.

**Panel 3**: Total data by source, with optional replacement and matching regex patterns

**Panel 4**: Recent restarts, app updates, latest DS phone home

**Panel 5**: Other 'interesting' messages

Improvements and suggestions welcome.

TODO:

* Improve matching wildcards and partial forwarder names
* Improve heavy forward handling

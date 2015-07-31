This is a collection of DNSSEC tools written in Java.  They are
intended to be an addition or replacement for the DNSSEC tools that
are part of BIND 9.


The tools included in this package are:

**jdnssec-signzone**

This is a dnssec zone signer. It supports normal RFC 4035 signing, as well as signing using NSEC3.

**jdnssec-keygen**

This is a DNSSEC key generation tool.

**jdnssec-verifyzone**

This is a tool to verify all of the signatures in a zone for cryptographic validity. It does not check to see if the zone is otherwise correctly signed.

**jdnssec-zoneformat**

This is a simple tool for reformatting a zone (possibly signed by another set of tools) into a known format, to make it easier to compare zones via tools like 'diff'.

**jdnssec-dstool**

This is a simple tool for generating DS (or DLV) records from DNSKEY records.

**jdnssec-keyinfo**

This is a simple DNSKEY introspection tool.

**jdnssec-signkeyset**

A tool for (self) signing bare DNSKEY RRsets.


Fork of the original work by David Blacka.
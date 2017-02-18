# srx-chords
Interactive web visualization of Juniper SRX firewall rules.

Input for this script is made from SRX config by first downloading the configuration with NETCONF (in XML)
and then converting it to JSON with [xmltodict](https://pypi.python.org/pypi/xmltodict) package.

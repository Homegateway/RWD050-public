# RWD050-public - SDT 2.0.1

This repository contains public information and code for the Smart Device Template (SDT) 2.0 modeling tools.

The SDT is a formal representation of device characteristic that are comprehensive enough to base APIs and protocols upon them.

Comments are appreciated. Please send comments via the GitHub "issues" feature.

## Documentation 
You can find further Information here:

- [SDT Components](SDT2.0/docs/SDT_Components.md)
- [Links & References](SDT2.0/docs/Links.md)
- [LICENSE](LICENSE)


## Overview of Files 
- [domain.rng](SDT2.0/domain.rng)  
The SDT schema in Relax NG notation, which is a little more reader friendly. See [http://relaxng.org/](http://relaxng.org/) for details.

- [domain.xsd](SDT2.0/domain.xsd), [xml.xsd](SDT2.0/xml.xsd)  
Generated XML schemas (ready to use).

## Version History
### SDT 2.0.1
Jun 01, 2015

- Added missing "uri" datatype.

### SDT 2.0
May 18, 2015

- Introduced RootDevice to support hierarchical embedded devices.
- Added new data types (byte, float, array, enum, date, time, datetime, blob, uri)
- Added ``readable`` and ``eventable`` to data points.
- Added otional ``<SerialNumber>``, ``<VendorURL>`` and ``<FirmwareVersion>`` elements to DeviceInfo
- Added optional ``<Doc>`` element to Event
- Changed the optionality of the ``<DataPoint>``'s ``type`` attribute to "required".
- Added [UML diagram](SDT2.0/docs/SDT_Components.md)
- Changed the namespace for the XSD from "hgi.org" to "homegatewayinitiative.org".

### SDT 1.0
Jan 20, 2015

- Initial public snapshot. Note this is not at all final.


## License
Note that this project runs under Apache 2.0 license. Read the [LICENSE](LICENSE) in this repository, or refer to [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0) .

Any contributions made to this project must comply with the forementioned license.


* [Service Information](#service-information)
  * [For services connected directly to an interfsce](#for-services-connected-directly-to-an-interface)
  * [For each end of the service](#for-each-end-of-the-service)
* [Related Service Information](#related-service-information)
* [Circuit Hierarchy Information](#circuit-hierarchy-information)
* [Pop Information](#pop-information)


# Service Information
## For services connected directly to an interface
 * name
 * status
 * circuit type - need to be able to identify 'path', 'service', 'l2circuit', 'link-aggr-group'
 * service type
 * project

## For each end of the service
 * pop info
 * equipment
 * card
 * port
 * logical unit
 
# Related Service Information

This is for services that are indirectly on an interface e.g. given an interface of ae12 related services would contain info for those connected to an lu of ae12 such as ae12.123
 * name
 * status
 * circuit type
 * project

 
# Circuit Hierarchy Information
Tightly related to the Related Service information. Currently this is used to build the related service information and finding Path information as they are not on the exact interface that a trap may be sent from.  This is used to work out which traps are related to one another and to display with alarms.

 
# Pop Information
 * name
 * abbreviation
 * city
 * country
 * longitude
 * latitude


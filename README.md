
* [Service Information](#service-information)
  * [For services connected directly to an interfsce](#for-services-connected-directly-to-an-interface)
  * [For each end of the service](#for-each-end-of-the-service)
* [Related Service Information](#related-service-information)
* [Circuit Hierarchy Information](#circuit-hierarchy-information)
* [Pop Information](#pop-information)
* [List Of All Routers](#list-of-all-routers)
# [List Of All Services](#list-of-all-services)
* [Interface Information](#interface-information)


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
 * country code
 * longitude
 * latitude

# List Of All Routers
 * hostname
 * pop
 * visibility: internal (e.g. an office/lab router) or externally visible (e.g. a backbone router)

# List of All Services
 * associated interfaces
 * customer
 * project
 * service categories (e.g. mdvpn, lhcone, etc.)

# Interface Information
 * equipment
 * physical info (rack/card/port)
 * circuit info
 * service/related-service info
 * customer info




## dorks

* Collection of ghdb dorks and other dorks i found across internet

## Readme

This repo contains dorks that i found across internet, but most part contains
dorks from ghdb. dorks are modified to make use of extra information so that 
they can be automated more easily, That extra information is `category`, and
`severity`. 

* Category
Categories are used to further narrow it down, apart from 7-8 categories 
listed on ghdb.

* Severity
Severity range from 1 to 10. Lower severity means more informational, or 
information can be extracted from the urls you fetch using those dorks, so 
require extra work on the results. Higher severity means, urls you fetch using
dork are directly usable, or you can say they are the information. 

Lower severity doesn't means low risk. But where the risk is present is used 
to assume severity, Lower severity means risk is present at 2nd or higher level
ie. into the pages you fetch from the urls you retrived using dork. Higher 
severity means risk is at 1st level or urls are the risk.

* Do not consider severity as the measure of criticality.
* Presence of dork is the risk in itself.
* This repo can be used to quickly filter out dork as per requirement.
* Low severity dorks can be quickly utilized with 'info hungry' tools.
* High severity dorks can be quickly utilized with 'action first' tools.
* Dorks on the basis of type, can be use to found leaked info in timely manner.

## credits

* All credit and copyrights goes to respective dork owners and ghdb

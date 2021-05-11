# EXPRESSCLUSTER X for SAP in a nutshell
## Why ECX for SAP HANA?
SAP HANA has HSR ( HANA System Replication) as its Database replication function. However it does not have automatic failover function for database and IP/Hostname. ECX provides failover function for those and controlling direction of the HSR replication. SAP has made no certification for HA solution for SAP HANA.

## Why NEC ECX and Why people going to choose ECX specifically for SAP?
ABAP platform in S/4HANA requires certified 3rd party solution for HA, and there are some choices for [certified HA solutions for S/4HANA](https://wiki.scn.sap.com/wiki/display/SI/Certified+HA-Interface+Partners), such like VERITAS, SIOS and NEC. Only one characteristic of ECX is that supports S/4HANA on both Windows and Linux while others support Linux or UNIX and none except ECX supports Windows.


## Licensing
In [EXPRESSCLUSTER X Product Introduction](https://www.nec.com/en/global/prod/expresscluster/en/collaterals/pdf/EXPRESSCLUSTER_x43_salestool_for_cloud.pdf#page=13), there is no information about support lineup for the product. But in the brochure [SAP NetWeaver Clustering Pack](https://www.nec.com/en/global/prod/expresscluster/en/collaterals/pdf/EXPRESSCLUSTER_sap_netweaver_nec_en.pdf), 1 to 10 years support packs are described and these could be thought as CAPEX model.

"Fixed Term License" exists not for "ECX for SAP" but for basic lineup of ECX, and by adding a bit idea on to Fixed Term License, it might be applicable to OPEX model because it can be purchased on monthly basis.
If OPEX model cannot be realized, contact ECX product team.

---- 
2021.05.11 Miyamoto Kazuyuki
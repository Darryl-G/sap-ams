# sap-ams
The file Z_AMS_NETWEAVER_MONITORING.SAP is an authorisation role for RFC metric extraction from SAP Netweaver or S/4HANA systems for use with the Azure Monitor for SAP (AMS) v2.0.
Micorosoft keep losing the link, so I've put the role here fore safekeeping.
If/when Microsoft update the tool and change the role requirements, then I may need to update this role, but there's no guarantee it is 100% correct.

25-Jan-2024: Updated role.
SU53 was showing that it needed lots of specific S_DEVELOP auth objects and also a worrying SE38 S_TCODE auth object.
It is not apparent what it needs some of these auths for.
Please ensure you validate your local security requirements when implementing this role.
It's rather annoying that the developers chose to need SE38, when SA38 could have been used.  Shows a lack of knowledge I feel.

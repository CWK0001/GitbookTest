# 17 July 2025 Clarity LIMS Hosted Instance Interruption – Resolved 
{% SET-14240 %}

Published: Aug 15, 2025 

We want to provide an update to you about a recent service interruption that affected Clarity hosted instances. The issue was first reported on 17 July 2025 (0210 UTC) and fully resolved on 17 July 2025 (1315 UTC). You might have had encountered slowness within Clarity LIMS or Clarity LIMS failed to start during the period.  

The issue was due to Illumina's managed HashiCorp Vault cluster service outage.  The HashiCorp Vault outage was caused by surge in the number of active leases&#185;. All services have been restored with corrective and preventive actions in place.  Additional monitoring and alerting have been added to ensure future stability. 

We sincerely apologize for the disruption and impact that was caused to your operations. 

{% hint style="danger" %}
**Important Recommendations**

We strongly recommend you to have your instance upgraded to the latest Clarity LIMS version 6.3.2 which has a fix to prevent similar issues. Release notes can be found at [https://help.claritylims.illumina.com/clarity-lims-v6.3-and-lablink-v2.5/readme/release-notes-clarity-lims-v6.3.2](https://help.claritylims.illumina.com/clarity-lims-v6.3-and-lablink-v2.5/readme/release-notes-clarity-lims-v6.3.2).
{% endhint %}

Please contact Illumina tech support team should you have any question.  

&#185; [https://developer.hashicorp.com/vault/docs/concepts/lease](https://developer.hashicorp.com/vault/docs/concepts/lease)  





Cleanup of StorSimple volumes after Test Failover (TFO)
=======================================================

            

 

 

This runbook is a cleanup script for the StorSimple TFO (Test Failover) scenario using Azure Site Recovery. This deletes all the volumes, backups, backup policies temporarily created on the target StorSimple device for TFO. It also shuts down the StorSimple
 virtual appliance after the manual action in case of TFO. This powershell workflow needs to be used in the context of ASR recovery plan for workloads hosted on StorSimple devices.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

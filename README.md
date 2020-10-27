Utility runbook to control monitor runbooks to run at specific intervals
========================================================================

            

It is quite common to leverage Azure Automation to monitor other systems for events that will trigger processes.  This is a popular approach, because it does not require any changes to the external system, and you can keep
 all of your event-reaction logic in one place.


This runbook is designed to run on scheduled intervals and resume any monitor runbooks that have a specific tag.



There is a sample runbook (Watch-EventID) in the Azure Automation gallery that demonstrates a monitor solution that this runbook would manage.


Please refer to [http://azure.microsoft.com/blog/2014/11/17/monitoring-azure-services-and-external-systems-with-azure-automation/](http://azure.microsoft.com/blog/2014/11/17/monitoring-azure-services-and-external-systems-with-azure-automation/) for additional details on using this runbook.






        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

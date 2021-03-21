# openmediavault_scripts
<h1>snapRAID notifications for Openmediavault</h1>
<p>Small script to enable notifications for snapRAID syncs.</p>
<p>This script was created because I wanted hourly checks for snapraid syncs to be triggered, but only 24 hourly synced when necessary. I put my openmediavault box in standby when not in use, so cannot rely on specific times to start the syncronisation. Also I do not want to spinup my drives hourly or each time a sync is triggered even though there is nothing to sync. When snapraid effectively syncs each 24 hour period, this is sufficient for me. If the previous sync was not succesfull, then I want a sync to occur the next hour.</p>
<p>The script checks the last modified date of the sync output file and syncs when older than specified seconds.</p>
<p>When last sync was not without errors, it retries the sync.</p>
<p>The script is to be scheduled as a task depending how frequently you want to sync.</p>
<p>The default effective sync interval is 24 hours.</p>

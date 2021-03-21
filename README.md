# openmediavault_scripts
<h1>snapRAID notifications for Openmediavault</h1>
Small script to enable notifications for snapRAID syncs.

The script checks the last modified date of the sync output file and syncs when older than specified seconds.

When last sync was not without errors, it retries the sync.

The script is to be scheduled as a task depending how frequently you want to sync.

The default sync interval is 24 hours.

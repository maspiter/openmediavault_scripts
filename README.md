# openmediavault_scripts
<h1>snapRAID notifications for Openmediavault</h1>
<p>Small script to enable notifications for snapRAID syncs.</p>
<p>The script checks the last modified date of the sync output file and syncs when older than specified seconds.</p>
<p>When last sync was not without errors, it retries the sync.</p>
<p>The script is to be scheduled as a task depending how frequently you want to sync.</p>
<p>The default sync interval is 24 hours.</p>

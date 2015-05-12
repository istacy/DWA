# DWA Portfolio Deployment Plan
---
## By Stacy Faude
<p>We are using Digital Ocean for Server Hosting and Git Hub for our Local Code Repository.</p>
---
###From Local Repo
<ol>
<li>Add changes to existing files as necessary and add new ones as needed.</li>
<li>$git add -A</li>
<li>$git commit -m "Commit Message"</li>
<li>Push to Staging Server: $git push stagingServer master</li>
</ol>
---
###From Staging Server
<ol>
<li>Perform Testing on Staging Server to ensure code works properly.</li>
<li>Push to Production Server: $git push prodServer master</li>
</ol>

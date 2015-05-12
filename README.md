# DWA Portfolio Deployment Plan
---
## By Stacy Faude
<p>We are using Digital Ocean for Server Hosting and Git Hub for our Local Code Repository.</p>
---
##The plan for Deployment
<ol>
<li>Making any changes</li>
<li>Check for errors</li>
<li>Updating and committing</li>
<li>Merging changes</li>
<li>Version control</li>
<li>Pushing to the test server</li>
</ol>

###1. Making Changes
<ol>
<li>Changes can be done with any editor of your choosing.</li>
<li>Changes can NOT be saved unless properly documented as to avoid confusion</li>
</ol>
###2. Check For Conflicts
<ol>
<li>Type git checkout master and the press Enter</li>
<li>Type git pull remoteRepo master and then press Enter</li>
<li>If there are erros - fix it and commit accordingly and pull again</li>
</li>
</ol>
###3. Updating and Committing
<ol>
<li>Type git add -A and Enter</li>
<li>Type git commit -am ' Something helpful ' and press Enter</li>
<li>Type git pull remoteRepo master and then press Enter</li>
</ol>
###4. Merging
<ol>
<li>Type git merge changeName a.
 <ul><li>Check for errors and make changes.</li></ul>
</li>Type git push remoteRepo master and Enter</li>
</ol>
###5. Version Contorl
<ol>
<li>Type git tag -a v Ma.Mi.R -m 'name of code and press Enter'</li>
<li>Version numbering system: Major Version.Minor Version.Revision</li>
<li>Type git push remoteRepo --tags</li>
</ol>
###6. Test Server
1. Notify the team via agreed upon messeging service of projected upload to server.
2. Type git push staging server master
3. Fix any issues
4. Test Again
5. Promote to Production


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

# integrate-covidnet
This repository contains a single WDL Workflow for syncing with Dockstore and then running on the Terra Cloud Computing Platform

After an unexpected computer glitch momentarily broke the usual method I use to upload new versions of this workflow into Terra,
I decided that I would create a dedicated GitHub repo whose only purpose was to contain the most recent version of our production
workflow so that it could be synced with Dockstore, etc.

So, we have a completely separate GitHub repo for developing and building code, and after each successful build the plan is
to copy that complete Workflow into this repo, and then commit the new file to GitHub.  That _should_ trigger the GitHub
actions sync with Dockstore, and thence we can update the workflow inside Terra without relying on the Broad institute's 
method and mechanism for editing and uploading modified workflows.

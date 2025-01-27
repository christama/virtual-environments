# GitHub Actions Virtual Environments
This repository will contain the code that we use to create the GitHub Actions [virtual environments](https://help.github.com/en/articles/software-in-virtual-environments-for-github-actions).
We're not quite ready to share the code and accept contributions yet. However, we want to gather your software requests and bug reports.
Please use the issue templates to submit requests and bug reports related to the installed software.

If you need help with how to set up your workflow file or use a specific tool, 
check out the [GitHub Actions Community Forum](https://github.community/t5/GitHub-Actions/bd-p/actions).

## Guidelines for what's installed
We follow these rough guidelines when deciding what to pre-install:

- Tools and ecosystems that are more popular and widely-used will be given priority.
- More recent versions of tools will be given priority over older versions.
- Tools and versions that are deprecated or have reached end-of-life will not be added.
- Tools and versions will be removed 6 months after they are deprecated or have reached end-of-life.
- If a tool can be installed during the build, we will evaluate how much time is saved
and how much space is used by having the tool pre-installed.

## Updates to the virtual environments
_Cadence_

You can expect approximately weekly updates to the software on the virtual environments.
For some tools, we always install the latest at the time of the deployment; for others,
we pin the tool to specific version(s).

_Notifications_

Right now, we don't have a great way for you to know when updates to the images are coming.
When we have the code available here, you can watch the Releases for when we generate
candidate environments, and when we deploy new ones.
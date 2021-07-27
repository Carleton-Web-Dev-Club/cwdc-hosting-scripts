# CWDC Hosting Scripts

## run-cwdc-script
This script is preinstalled on all hosts. Simply invoke it on a host, along with the path to the script from the main cwdc domain. Since this repo is cloned to cwdc.scs.carleton.ca/shared/scripts, you could run `run-cwdc-script shared/scripts/cwdc-echo Hello World`, and the correct script will be downloaded and run.

## why?
Since we are extremely space constrained, doing it this way means we don't have to have git installed on all the hosts and keep a local repository of the scripts.

It also allows for scripts to be updated quickly and efficiently.
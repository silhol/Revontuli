# Revontuli
Python script that checks for northern lights close to the user and sends e-mail, if something is to see. This script is only for Finland and will not work with other countries. It is customized to use the finnish space weather observation website.

This repository consists out of an python script that checks every 10 minutes the finnish FMI website https://en.ilmatieteenlaitos.fi/auroras-and-space-weather for electromagnetical disturbances. If a disturbance (i.e. there might be some aurora borealis to see) then an e-mail is sent. 

For this to work, you need:
- to create during the first run a configuration file (i.e. you will be asked which station to monitor and your e-mail). We created a gmail account for this purpose and added in this repository a description (we did our best with that one) how to set it up properly with API keys and authorization. If you want to use some other e-mail type you need to modify the code. If you want a different email or location, just delete the configuration file
- schedule the python script to run in the background (we worked on a windows machine, so we give the desription for that)

Improvements are welcome.

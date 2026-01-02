# README</br>
# xtreamui_mirror</br>
This is an installation mirror for xtream ui software.</br>

How do I install?</br>
update your ubuntu first, then install panel</br></br>

sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install software-properties-common libxslt1-dev libcurl3 libgeoip-dev python -y;
rm install.py; wget https://github.com/dalibor26/xtream-ui/blob/xtream-ui_installation/install.py;
sudo python install.py</br></br>
If you want to install main server with admin panel, choose MAIN.</br>
If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.</br>


Files Hashes</br>
main_xtreamcodes_reborn.tar</br>

sub_xtreamcodes_reborn.tar</br>

release_22f.zip</br>

newstuff.zip</br></br>


note: newstuff.zip has same files from my xtreamui_things repo, i won't update this zip file anymore. if i change something on those files, you can download them.</br>
note2: also i still use same release_22f.zip file. if you want to use old install.py, go to bitbucket mirror page.</br>

note,</br>
i forked this install.py is from https://xtream-ui.com/install/install.py</br>
you can compare my install.py with original one.</br>

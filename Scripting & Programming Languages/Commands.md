📁 1. Directory and File Management
Command	Purpose
pwd  	📍 Show current directory
ls	    📂 List files and directories
cd	    🚪 Change directory
mkdir	🏗️ Create a new directory
rmdir	🧹 Remove an empty directory
touch	✨ Create a new empty file
cp	    📄 Copy files/directories
mv   	🚚 Move/Rename files/directories
rm	    🗑️ Remove files or directories
cat	    📖 Display file content
more / less	        📜 View file content page by page
file	            🔍 Identify file type


🛠️ 2. File Permissions
Command	Purpose
chmod   	🔐 Change file permissions
chown	    👑 Change file owner and group
chgrp	    👥 Change group ownership


🔎 3. Viewing and Searching Files
Command	Purpose
head	🔼 View first lines of a file
tail	🔽 View last lines of a file
grep	🧲 Search text using patterns
find	🕵️ Search files and directories
wc   	🧮 Count lines, words, characters


🚀 4. Process Management
Command	Purpose
ps	          🖥️ Show running processes
top / htop	  📈 Monitor system processes
kill	      💥 Terminate a process by PID
killall	      🛑 Terminate processes by name
bg	          🔙 Resume a suspended process in background
fg	          🔛 Bring a background process to foreground


🛡️ 5. Networking
Command	Purpose
ping	🌐 Check network connectivity
curl	📡 Transfer data from a URL
wget	📥 Download files from the web
ssh 	🔐 Remote login to another machine
scp	    📤 Secure copy files between systems


📦 6. Package Management (Debian/Ubuntu)
Command	Purpose
apt update      	       ♻️ Update package list
apt upgrade	               ⬆️ Upgrade installed packages
apt install <package>	   ➕ Install new package
apt remove <package>	   ➖ Remove a package
(for RedHat/CentOS, use yum  or dnf)


🧹 7. Disk and System Monitoring
Command	Purpose
df -h       	💾 Show disk space usage
du -sh *	    📦 Show folder size
free -h	        🧠 Show memory usage
uptime      	⏳ System running time
who	            👤 List logged-in users
uname -a	    🛠️ Show system info
hostname    	🖥️ Show or set system hostname



🔄 8. Redirection and Pipes
Concept	Purpose         
>	➡️ Redirect output to a file (overwrite)
>>	➡️ Append output to a file
<>	⬅️ Take input from a file


🔥 9. Shell Scripting Specific
Command/Concept	Purpose
#!/bin/bash	                               ✍️ Shebang to define interpreter
echo   	                                   📣 Print text to screen
read	                                   📝 Take user input
$1, $2, ...	                               📥 Access script arguments
$#	                                       🔢 Number of arguments passed
$@	                                       📋 All arguments passed
if [ condition ]; then ... fi	           🧠 Conditional execution
for var in list; do ... done	           🔄 Loop over items
while [ condition ]; do ... done	       🔁 Repeat until false
function myfunc() { ... }	               🧩 Define reusable blocks

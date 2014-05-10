## command line


* **Tip**

	If we want to see the modification date or no of bytes 	of file just do ls -l


*  ###less

	Less will allow us to view text files
	It will display the file 1 page at a time
	
	*example* 
	
	* less text_file
	
	* Then use b, space, G, 1G, /search features
	
	* b->scroll back,  space is scroll forward
	
* ##file
	
	file tells you what type of file it is
	
	file name_of_file 
	
* ##Linux Directory Structure

	* /boot
		
		* kernel and boot loader are kept here
		* kernel is called vmlinuz
		
	* /etc
		
		* all config files are here
		* all the files here are text files
		* ** points of interest **
			* /etc/passwd -> user info
			* /etc/fstab -> defines disk drives
			* /etc/host -> lists host names and IP known to system
			* /etc/init.d -> scripts that start system services at boot time
			
	* /bin , /usr/bin
	
		* /bin -> programs required by system
		* /usr/bin -> programs required by user
		
	* /sbin, /usr/sbin
		* programs for system administration, mostly for superuser
	
	* /usr
		* contains lot of things
			* /usr/share/X11 -> supprt file for X Window system
			* /usr/share/dict -> spell schecker Dictionary. Linux has a spell checker look aspell
			* /usr/share/doc -> documentation files
			* /usr/share/man -> man pages
			* /usr/src -> linux kernel source code
	* /usr/local
		* used to install software local to machine. Usually we install it in /usr/local/bin
	
	* /var
	 	* contains file that change as system is running
	 	few files to view are /var/log /var/spool(queued up files for process)
	 
	 * /lib
	 	* shared libraries
	 
	 * /home
	 	* users keep personel work
	 	
	 * /root
	 	* superusers home
	 	
	 * /tmp
	 	* directory where programs can write temp files
	 	
	 * /dev
	 	* contains devices(devices are considered files in linux)
	 	
	 * /proc
	 	* virtual directory(dosent exists). contains little peep holes into kernel. /proc/cpuinfo. There are some numbered entries that correspond to the processes running in system. It also consist of current config info of the system
	 	
	 *  /media, /mnt
	 	* /media is used for mount points. The process of attaching a device to the tree(file system) is called mounting. For a device to be available it must first be mounted.
	 	
 		* When your system boots, it reads a list of mounting instructions in the file /etc/fstab, which describes which device is mounted at which mount point in the directory tree. This takes care of the hard drives, but you may also have devices that are considered temporary, such as CD-ROMs, thumb drives, and floppy disks. Since these are removable, they do not stay mounted all the time. The /media directory is used by the automatic device mounting mechanisms found in modern desktop oriented Linux distributions. On systems that require manual mounting of removable devices, the /mnt directory provides a convenient place for mounting these temporary devices. You will often see the directories /mnt/floppy and /mnt/cdrom. To see what devices and mount points are used, type mount.
		
		
	
		
		



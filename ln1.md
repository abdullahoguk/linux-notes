#Pre-Installation
* Create unallocated space by shrinking/deleting partition (**Minimum:** 20GB or 30GB  **Recommended:**  100GB)   
* Create bootable USB by using unetbootin or any other USB tool.  

#Installation
* Follow normal process
* In Installation type select 'Something Else' if you don't want to delete all HDD.
* Select unallocated space and click '+'  
	```
	Size: 15GB or 20GB   
	Type: Primary   
	Use as: Ext4 journaling file system   
	Mount point: /   
	```
* Select unallocated space and click '+'  
	```
	Size: [Size of RAM you are using]   
	Type: Primary   
	Use as: Swap Area   
	```
* Select unallocated space and click '+'  
	```
	Size:[All left space]   
	Type: Primary   
	Use as: Ext4 journaling file system   
	Mount point: home   
	```
* Device for boot loader installation;if you have  only one HDD on your PC left as it is. If you ve more than one, select one where previous/current boot loader in.
* Continue to installation
#After-Installation
* Update System
* If you have 2 display drive in your PC(nVidia/Intel), install bumblebee
```

TODO installation of bumblebee
```
* Install restricted extras(Ubuntu)
* Install Java and JDK
* Apps I am using >>> apps.md
* Command line basics >>> cli1.md

# Nessus Vulnerability Scanning and Management


<h2>Description</h2>
Project consists of a setting up a virtual machine with VirtualBox and scanning for vulnerabilities with Nessus. 
<br />


<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Project walk-through:</h2>


Set network adapter settings to bridged: <br/>
<img width="608" alt="bridged adapter" src="https://user-images.githubusercontent.com/118764174/203607233-2d51a389-45cf-4fb0-86d1-7d2a01d405d7.png">
<br />
<br />

Make sure the VM has enough RAM:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203609125-75f42e77-bb42-418b-a8a7-85c47b17d9d8.png)
<br />
<br />
Enable Remote Registry in Services: <br/>
![image](https://user-images.githubusercontent.com/118764174/203610533-56fbca72-8717-40a2-b744-5f88ad9ae260.png)
<br />
<br />
Enable printer and file sharing:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203610630-9eb46fe5-1a71-4bfe-a17a-7a275ad6d316.png)
<br />
<br />
Disable firewall:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203610723-fe606993-2f79-4a93-95f1-470dc7390aff.png)
<br />
<br />
Disable User Account Control:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203610803-b7f3b994-a98a-4ff9-a74c-c64e7d20c5d7.png)
<br />
Scan VM:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203611023-537126fe-f925-4c0e-9324-3abc1bc61ce9.png)
</p>
Install old software and scan VM:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203611212-f752883a-92b1-4071-ba48-e45ec9dba8f2.png)
</p>
Run windows updates and uninstall old software and scan VM:  <br/>
![image](https://user-images.githubusercontent.com/118764174/203611347-31c28df9-e317-4c5a-8e35-f2831e98fc97.png)
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

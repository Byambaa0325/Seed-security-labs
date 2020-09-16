# Seed-security-labs
Labs used in ICSI448 InfoSec Course in NUM


## Lab Setup:
<div id="single_side">

<h3>Virtual Machine Software (VirtualBox)</h3>
<p>
Install the free <a href="https://www.virtualbox.org/wiki/Download_Old_Builds_6_0">VirtualBox</a>. 
Please stay away from the newest version, as they tend to have  
minor issues with our VMs, based on our past experience. If the current version is 
6.0.22, go for 6.0.18 will be safer. 
Although our instructions are only for VirtualBox,
the pre-built VM images can also run on VMWare. 
</p>
      

<h3>Pre-built Virtual Machine Images (Ubuntu)</h3>
<p>
All the SEED labs should be conducted in our pre-built virtual machine image,
because we have installed all the necessary tools, software, and
libraries that are needed by the SEED labs. Students just need to download the VM, and 
run it using VirtualBox (or VMWare).
</p>
     
<ul>
  <li><b>SEED Ubuntu16.04 VM (32-bit)</b>: This VM was built in June 2019. 
  We have made some small changes based on the 2018-May version. 
  <ul>
  <li> Download the image from one of the following servers:
    <ul>
        <li>Google Drive: <a href="https://drive.google.com/file/d/12l8OO3PXHjUsf9vfjkAf7-I6bsixvMUa/view?usp=sharing">SEEDUbuntu-16.04-32bit.zip</a></li> 
        <li>DigitalOcean: <a href="https://seed.nyc3.cdn.digitaloceanspaces.com/SEEDUbuntu-16.04-32bit.zip">
            SEEDUbuntu-16.04-32bit.zip</a></li>
	<li>Cybersecurty.com: <a href="https://www.cybersecurty.com/seeddownload">
			SEEDUbuntu-16.04-32bit.zip</a></li>
        <li>Syracuse University (New York, US): <a href="http://www.cis.syr.edu/~wedu/SEEDUbuntu-16.04-32bit.zip">SEEDUbuntu-16.04-32bit.zip</a></li>
        <li>Zhejiang University (Zhejiang, China): <a href="https://pan.zju.edu.cn/share/6c72d40cdc0877833c6b96bd2d">SEEDUbuntu-16.04-32bit.zip</a></li>
        <li>MD5 value: 12c48542c29c233580a23589b72b71b8</li>
    </ul></li>

  <p></p>
  <li> Unzip SEEDUbuntu-16.04-32bit.zip and you should be able to see a folder that contains the VM files.
    <ul>
       <li>Follow <a href="./Labs_16.04/Documents/SEEDVM_VirtualBoxManual.pdf">this 
       document</a> to run and configure the VM on VirtualBox.</li>
       <li>You will be logged into an account called <b><tt>seed</tt></b>, and 
            its password is <b><tt>dees</tt></b> (the reverse order of <tt>seed</tt>). 
    </li></ul></li>
  </ul></li>
<!--
  <li><b>SEEDUbuntu16.04.zip</b>: This VM was built in May 2018 
  <ul>
  <li> Download the image from one of the following servers:
  <ul>    <li>Google Drive: <a href="https://drive.google.com/file/d/1HxdUhq-J_-_QKyjngpH9m6Kmuvy0_68a/view?usp=sharing">SEEDUbuntu-16.04-32bit.zip</a></li> 
          <li>A server at Zhejiang University: <a href="https://pan.zju.edu.cn/share/547f050498c0b4ed34d4284f0b">SEEDUbuntu-16.04-32bit.zip</a></li>
          <li>MD5 value: 2d4aefc4624f4676674dc8e19cf7cfec</li>
       </ul></li>
  <li> Unzip SEEDUbuntu-16.04-32bit.zip and you should be able to see a folder.
       Follow the <a href="./Labs_16.04/Documents/SEEDVM_VirtualBoxManual.pdf">this document</a> to load the image into VirtualBox.</a>
  </ul></li>
-->


<p></p>
  <li><b>SEED Ubuntu12.04 VM (32-bit)</b>: This VM was built in Jaunary 2016; it has been phased out. However,
      two of the SEED labs still depend on this VM. 
  <ul>
  <li> Download the image from the following server
       (the MD5 checksum of the file is 6ec9c429a2f4a9163530ada20f0621dc):
    <ul>
      <li> Syracuse University: <a href="http://www.cis.syr.edu/~wedu/SEEDUbuntu12.04.zip">
	   SEEDUbuntu12.04.zip</a></li>
      <li> DigitalOcean: <a href="https://seed.nyc3.cdn.digitaloceanspaces.com/SEEDUbuntu12.04.zip">
	   SEEDUbuntu12.04.zip</a></li>
      <li> Zhejiang University: <a href="https://pan.zju.edu.cn/share/f2a4d37206eee87798702b3cc2 ">SEEDUbuntu12.04.zip</a></li>
    </ul></li>
  <li> <a href="http://www.cis.syr.edu/~wedu/seed/Documentation/Ubuntu12_04_VM/Ubuntu12_04_VM_Manual.pdf">
       User Manual</a>: includes the account
       and password information, list of software and servers installed, and configuration.</li>
<!--
  <li> <a href="http://www.cis.syr.edu/~wedu/seed/Documentation/Ubuntu12_04_VM/CustomizationInstruction.pdf">
       VM Customization</a>: Some labs require multiple VMs; to help you easily identify which VMs you are
       in, you can do some simple customization. You need to download
       this file (<a  href="http://www.cis.syr.edu/~wedu/seed/Documentation/Ubuntu12_04_VM/Customization.zip">Customization.zip</a>) as well.</a></li>
-->
  </ul></li>


<!--
<p></p>
<li>(<font color="red"><b>Cloud Approach</b></font>) 
If you prefer to run the above SEEDUbuntu12.04 VM from <b>Amazon Cloud (AWS)</b>, you can find 
it (SEEDUbuntu12.04-Generic) in AWS's community AMIs. Once you 
have launched the VM, you can either use RDC (Remote Desktop Connection) or 
SSH to connect to your VM instance. This approach is very good for students who do not have their 
own computers or their computers are not powerful enough to run VM locally.
<ul>
   <li><a href="http://www.cis.syr.edu/~wedu/seed/Documentation/Cloud/SEEDVM_Cloud.pdf">
        Instructions for both students and instructors.</li>
</ul>
-->

</ul>



<div id="page_footer" class="green">
<p>
Copyright © Wenliang Du, Syracuse University
</p>
</div>

</div>

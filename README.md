<h1 align="center">Dirk Oshel Home Lab Doc</h1>
<p align="left">Developing a home lab documentation for anyone to follow along </p>
<h2 align="left">Overview</h2>
<p align="left">Built system off of Truenas OS. Main reason for this was the various storage devices that would be utilized in this machine. 
  <br> The apps running on the machine are Jellyfin, with a media library accessible to friend, Tailscale for remote access, and more to come <br>Had this setup in another Truenas machine but decided to upgrade the motherboard and CPU. acting like this is a fresh install for the sake of documentation.</br>
</p>
<h2 align="left">Environment</h2>
<h3 align="left">Hardware</h3>
<ul>
  <li>ROG B550-F GAMING WIFI II</li>
  <li>Ryzen 9 5900X</li>
  <li>32 GB DDR4 RAM @ 2400Mhz</li>
  <li>1x 512GB NVMe SSD, Gen3x4</li>
  <li>3x 1TB NVMe SSD, Gen3x4*</li>
  <li>2x 1TB SATA SSD, Samsung EVO 870</li>
  <li>1x 1TB HDD </li> 
</ul>
<p>*2 of the 1TB NVMe drives are on a PCIe to M.2 card. I need to still set them up to be detected in Truenas</p>
<h3 align="left">Software*</h3>
<ul>
  <li>Truenas OS</li>
  <li>Tailscale</li>
  <li>Jellyfin</li>
</ul>
<p>*More software will be installed in the future. This is just the setup so far</p>
<h2>Setup process</h2>
<h3>Physical Installtion of drives</h3>
<p>Not much to say here I will probably input a picture of the physical device. Built the PC myself.
  <br>Connected ethernet cable
  <br>Include picture of physical network setup here
</p>
<h3>OS Installation</h3>
<p>Downloaded Truenas Scale OS. 
  <br>Used Rufus to create a bootable install of the OS on a thumbdrive.
  <br>Put thumbrdive in computer and powered on PC
  <br>Spammed F12 to get into BIOS.
  <br>Changed device configuration for PCIE16_1 to x8/x4/x4
  <br>Changed boot media to thumbdrive
  <br>Loaded into GRUB menu
  <br>Installed Truenas OS to M.2_1 device
  <br>Set up admin account
  <br>Restarted
</p>
<h3>Truenas setup</h3>



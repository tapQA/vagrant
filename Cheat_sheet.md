# Publicly available VMs

After you have installed VirtualBox, you have access to pull down publicly posted VMs from [Atlas](https://atlas.hashicorp.com/boxes/search).

Atlas works very much like Github, once someone has created something, they post it and make it freely available for download.

### Windows VMs for browser testing

Microsoft provides [this](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) tool to help you specify your box & browser combo.

Or you can find the same VMs through Atlas, under user ModernIE.

##### Cheat sheet

A quick list of the command you need to execute to pull & build a Windows VM for browser testing:

- Windows 10 with Edge: vagrant init modernIE/w10-edge; vagrant up --provider virtualbox
- Windows 7 with IE 11: vagrant init modernIE/w7-ie11; vagrant up --provider virtualbox
- Windows 8.1 with IE 11: vagrant init modernIE/w8.1-ie11; vagrant up --provider virtualbox

A couple Mac VMs:

- OS X 10.11: vagrant init carbon/osx-elcapitan-10.11; vagrant up --provider virtualbox
- OS X 10.10: vagrant init AndrewDryga/vagrant-box-osx; vagrant up --provider virtualbox

And Linux:

- Ubuntu Trusty 14.04: vagrant init box-cutter/ubuntu1404-desktop; vagrant up --provider virtualbox
- Mint 17 Cinnamon: vagrant init npalm/mint17-amd64-cinnamon; vagrant up --provider virtualbox
- Red Hat Fedora: vagrant init jclingan/fedora22-desktop; vagrant up --provider virtualbox
- CentOS: vagrant init box-cutter/centos65-desktop; vagrant up --provider virtualbox

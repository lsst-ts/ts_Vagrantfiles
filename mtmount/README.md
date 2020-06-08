======================
Building NSV Simulator
======================

* Install Vagrant and VirtualBox
* Obtain access to IT network shared drive
* Copy the file from `TSS-Share/TMA/TMASoftwareWindows10` onto the virtualbox. You can accomplish this by placing the file in the same as directory as the vagrantfile. 
* Download 32bit LabVIEW 2018 SP1 Runtime, you can find that here Run the NSVSimulator https://www.ni.com/es-cl/support/downloads/software-products/download.labview.html#309627
* Copy all the files (LV2018, TMASoftwareWindows10) into the root folder of Vagrant
* Do `vagrant up` 
* Inside of the virtual box navigate to `C Drive` and move Lv2018 and TMASoftwareWindows into `desktop`
* Run the LabVIEW installer
* Unzip the contents of TMASoftwareWindows and run TMASoftwareWindows/ATSSimulatorAndTools/SimulateLimits/SimulateLimites.exe
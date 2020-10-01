# How to Resize Droplets in Digital Ocean

## Two Types

* CPU and RAM only
* Disk, CPU and RAM

## Precautions before Resizing

1. Take a backup of the droplet prefreably. Or take a snspshot
2. Always try to shutdown the Droplet from within the OS by logging into it to avoid OS corruption. _Try avoiding to shutdown from control panel or console._

3. Canclulate downtime based on the disk consumption of droplet. Roughly one minitue per GB of used disk space.

## Steps to Resize

1. Login to DO control panel
2. Click on the Droplet and on make sure it is powered off.

3. Once it is powered off state, on the menu left side click on "Resize" by choosing new CPU/Memory config required.

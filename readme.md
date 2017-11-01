# Set up Raspberry pi Development board

### what is raspberry pi-

* Raspberry pi is development board which is similar to a mini computer. It is of the size about a credit card.
* Raspberry pi widely used for learning Hardware and Software development. 
* The first Raspberry model was "Raspberry Pi 1 Model B"
* After which Many models of raspberry pi 1 launched like - Model A, Model B+ etc
* Then further raspberry pi 2 and raspberry pi 3 were launched
* The pi 3 model was also include Bluetooth and Wi-Fi which were not present in previous versions.
* we will discuss projects based on pi 3 version.
* The "Raspberry pi 3" board with its features shown in figure below.


![alt tag](https://i.stack.imgur.com/jAlDp.png)
                                          
                                          
                                          
                                          Figure:1 Raspberry pi 3

## Material Required for setup
If you have a laptop than only following things required
* Ofcousre a Raspberry Pi 3.
* A Memory card of 16GB.
* An Ethernet cable for accessing raspberry pi.
* Data cable for power supply.
### Material required for some basic hardware projects.
* some jumper wires (male and female both).
* LEDs.
* (Optional) ADC and some sensors ( This depends up on project you are going to build ).

## Step-1: To prepare sd card for for booting the operating system ( installing operating system on SD card using Windows os )
* First of all [Download](https://www.raspberrypi.org/downloads/raspbian/) he raspbian desktop OS from the official website of   raspberry pi. you can download either with torrent or directly zip file.
* Download the  [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/) to write the os file into sd card.
* Unzip i.e extract the zip file of the os then you will get file something like "distribution-name.img".
* insert the memory card on which you are going to write the os image into card reader and attach to your Laptop. Format the memory card.
* open the Win32DiskImager as adminstrator.

![alt tag](http://www.servethehome.com/wp-content/uploads/2013/03/Win32-Disk-Imager-Raspbian-Image-Selection-from-Synology-NAS.png)
                                            
                                            
               Figure:2 Win32DiskImager
* Select the image file of raspbian os extracted from zip file. Then select the memory card (be careful "do not select another disk by accident"). write the OS image by clicking the "write" button of Win32DiskImager and wait for complete writing.
* Now you can insert the memory card into respberry pi's card slot. (shown in figure 1.) 
* For detail about accessing the pi consider the tab above.

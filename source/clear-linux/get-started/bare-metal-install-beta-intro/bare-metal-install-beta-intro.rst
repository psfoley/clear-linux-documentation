.. _bare-metal-install-beta-intro: 

Install from the live desktop beta image
########################################

The live desktop beta image allows you to boot |CL-ATTR| into a GNOME 
desktop without modifying the host system. Using the live image, you can 
explore the possibilities of developing with |CL|. You can also launch the 
new installer and install |CL| on your target system. 

.. contents:: :local:
   :depth: 1

Prerequisites
*************

Assure that your target system supports the installation: 

* :ref:`system-requirements`
* :ref:`compatibility-check`

Preliminary steps 
*****************

#. `Navigate to the image directory`_. 

#. Download :file:`clear-<release number>-live-desktop-beta.img.xz`

   .. note:: 

      ``<release-number>`` is the latest |CL| auto-numbered release.

#. Follow your OS instructions to create a bootable USB drive.

   * :ref:`bootable-usb-linux-all`
   * :ref:`bootable-usb-mac-all`
   * :ref:`bootable-usb-windows-all`

.. _install-from-live-image:

Install from live image
***********************

After you've downloaded and burned the live desktop image on a
USB drive, follow these steps. 

#. Insert the USB drive into an available USB slot.

#. Power on the system.

#. Open the system BIOS setup menu by pressing the F2 key. 

   .. note:: 

   	Your BIOS setup menu entry point may vary.

#. In the setup menu, enable the UEFI boot and set the USB drive as the
   first option in the device boot order.

#. Save these settings and exit.

#. Reboot the target system.

Launch the installer
********************

#. After the |CL| live desktop image boots, select the :guilabel:`Activities`   menu in the upper left. 

#. Select the icon, :guilabel:`Install Clear Linux OS`, shown in Figure 1. 

   .. figure:: figures/bare-metal-install-beta-intro-1.png
	   :scale: 50 %
	   :alt: Install Clear Linux OS icon

	   Figure 1: Install Clear Linux OS icon

#. Upon selecting the icon, the installer is launched, as shown in Figure 2.

   .. figure:: figures/bare-metal-install-beta-intro-2.png
	   :scale: 50 %
	   :alt: Clear Linux OS Installer

	   Figure 2: Clear Linux OS Installer

#. Continue to :ref:`bare-metal-install-beta`

.. _Navigate to the image directory: https://download.clearlinux.org/image/

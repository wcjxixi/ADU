# Setting

## Settings Menu Overview

## Firmware Upgrade (OTA)

After entering the 「Setup Menu」 → 「Firmware Upgrade (OTA)」 interface, the Bluetooth of the ADU device will be turned off and WiFi will be turned on automatically, and the ADU device will be used as an AP (Access Point) to receive OTA firmware.

### Connection Parameters&#x20;

* SSID Name: `ADU-WiFi`
* SSID Password: `12345678`
* IP Address: `192.168.99.1`

### Upgrade Steps

1. Download the compiled firmware (.bin file) to your cell phone or other devices.
2. Go to 「Setting Menu」 → 「Firmware Upgrade (OTA)」 interface of ADU.
3. After the cell phone and other devices are connected to `ADU-WiFi` network, open `192.168.99.1` in the browser and upload the firmware (.bin file) according to the instructions on the page.
4. Wait for about 30 seconds, after the ADU device reboots automatically, it indicates that the firmware upgrade is complete.

{% hint style="warning" %}
If the ADU does not reboot automatically for a long time, it means the upgrade has failed. You need to reboot the ADU manually (using the supplied power switch or car re-lighting), and then re-enter the 「Firmware Upgrade (OTA)」 interface to try the upgrade again.

Don't worry! A failed upgrade will not render the ADU unusable!
{% endhint %}

## Reset Device

After resetting the device, it will return to its default values. Modify the setup parameters as needed (especially **Selecting the Bluetooth Adapter Model**, as well as **Modifying the gyro Orientation** and **Calibrating the Gyroscope**).

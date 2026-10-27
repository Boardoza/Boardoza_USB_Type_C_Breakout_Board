# Boardoza USB Type-C USB 2.0 Breakout Board

The **Boardoza USB Type-C Breakout Board** is a simple adapter board for a **USB Type-C connector**. It converts the small surface-mount pins of the USB Type-C connector into standard **2.54 mm through-hole pins**, making the connector easier to use with development boards, breadboards, and custom electronics projects.

It supports **USB 2.0** connections and can be used for USB Type-C prototyping, power connections, data communication, and testing without having to solder directly to the small pins of a USB Type-C connector.

|Front Side|Back Side|
|:---:|:---:|
|![Front](./assets/USB_TYPE_C%20Front.png)|![Back](./assets/USB_TYPE_C%20Back.png)|

---

## Key Features

- **Easy USB Type-C Connection:** Converts the small USB Type-C connector pins into easy-to-use **2.54 mm through-hole pins**.
- **USB 2.0 Support:** Provides access to **D+** and **D-** pins for USB 2.0 data communication.
- **CC Pin Access:** Provides access to **CC1** and **CC2** pins for USB Type-C connection and cable detection.
- **SB Pin Access:** Provides access to **SB1** and **SB2** pins for projects that require alternate modes.
- **Power Connections:** Provides easy access to **VBUS** and **GND** pins for USB power connections.
- **Easy Prototyping:** Makes the USB Type-C connector easier to use with breadboards, development boards, and custom electronic projects.

---

## Technical Specifications

**Model:** USB Type C  
**Manufacturer:** Boardoza   
**Connector Type:** USB Type-C Receptacle  
**Connector Pin Count:** 16  
**Interface:** USB 2.0  
**Functions:** USB Type-C SMD-to-THT Breakout  
**Operating Temperature:** -40°C to +85°C  
**Board Dimensions:** 20mm x 20mm

---

## Board Pinout

### ( J2 ) USB Data, Configuration & Sideband Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1, 2 | CC2 | USB Type-C Configuration Channel 2 for cable orientation and connection detection |
| 3, 4 | SB1 | USB Type-C Sideband Use 1 Signal |
| 5, 6 | D+ | USB 2.0 Positive Differential Data Line |
| 7, 8 | D- | USB 2.0 Negative Differential Data Line |
| 9, 10 | CC1 | USB Type-C Configuration Channel 1 for cable orientation and connection detection |
| 11, 12 | SB2 | USB Type-C Sideband Use 2 Signal |

### ( J3 ) USB Power Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1, 2 | VBUS | USB Bus Power Supply Rail |
| 3, 4 | GND | Ground Reference |

### ( J4 ) USB Power Extension Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1, 2 | VBUS | USB Bus Power Supply Rail |
| 3, 4 | GND | Ground Reference |

---

## Board Dimensions

<img src="./assets/USB_TYPE_C Dimensions.png" alt="USB Type C Dimension" width="450"/>

---

## Step Files

[Boardoza USB Type C.step](./assets/USB_TYPE_C%20Step.step)

---

## Sensor Datasheet

[USB Type-C User Manual.pdf](./assets/USB_TYPE_C%20User%20Manual.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact <support@boardoza.com>

---

## **License**
### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

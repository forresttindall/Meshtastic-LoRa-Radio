# Meshtastic-LoRa-Radio

![piggyback1.jpg](/meshtastic-project-photos/piggyback1.jpg)

  
# Meshtastic Texting Radio Device

This device was made to be a portable off-grid communication method for my wife and I to use for backcountry adventures. It uses the open source meshtastic technology to form a mesh network over LoRa radio frequency to allow for text messages to be transmitted between devices with the meshtastic app when paired to your phone via bluetooth. It magnets to the back of your phone with a magsafe ring making it nice and portable.

---

This device is an open source device the real credit goes to the Meshtastic team and phspman.

---

**Caveat:** I am not sure of the range on this device as it's highly dependent on antenna, number of devices on the mesh network and terrain. I've included some antenna options for increased range.

---

I'd recommend reading more about the meshtastic technology [here](https://meshtastic.org/).

---

## Materials List:

- Case
- Heltec V3 Board - battery connector included [Link](https://www.amazon.com/dp/B07FYWFH4C?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- Antennas (small) - [Link](https://www.amazon.com/dp/B0BX2NFM9B?ref=ppx_yo2ov_dt_b_product_details&th=1)
- Antenna long range - [Link](https://www.amazon.com/gp/product/B0D3KPFVH3/ref=ox_sc_saved_image_4?smid=AQ0B8JRQY8X0X&psc=1)
- 3.7v 1100mAh battery - [Link](https://www.amazon.com/dp/B08FD39Y5R?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- Screws - #6 x ½” self tapping (7mm x 13mm) - [Link](https://www.amazon.com/dp/B0B5CNQXMN?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- Magsafe ring - [Link](https://www.amazon.com/gp/product/B0CSVXD888/ref=ox_sc_saved_image_3?smid=A1M11WW4NKTCL&psc=1)
- Magnets - 5mm x 2mm - [Link](https://www.amazon.com/gp/product/B09DC8KG2C/ref=sw_img_1?smid=AZ3H0P0UI6KGB&psc=1)
- Switch - [Link](https://www.amazon.com/dp/B07RTJDW27?psc=1&ref=ppx_yo2ov_dt_b_product_details)

---

## Assembly:

1. Print case
   ![Chrome Browser](./images/meshtasticflasher.png)
   - Download [Chrome browser](https://www.google.com/chrome/)
   
2. Using Chrome, flash latest meshtastic firmware to the main board. Select Heltec V3 [Link](https://meshtastic.org/docs/getting-started/flashing-firmware/esp32/web-flasher/)

   ![Meshtastic Flasher](./images/meshtasticflasher.png)

3. Download meshtastic app from the AppStore or Google Play Store

4. Cut ends of battery harness included in heltec V3 box.

5. Cut ends of 1100mAh battery cables

   ![Battery Harness](./images/harness.JPG)

6. Solder battery wires, switch and heltec harness together as shown. Battery to middle post on switch.

7. Insert switch into switch opening in case

8. Install SMA connector into antenna hole on casein onto V3 board

   ![SMA Connector](./images/smatocase.jpg)

9. Connect antenna wire to board

   ![Antenna to Board](./images/smatoboard.JPG)

10. Insert battery

11. Configure wires so case closes

   ![Align Wires](./images/alignwires.jpg)

12. Close case halves and screw together

   ![Screws](./images//screws.jpg)

13. Press magnets in back of the case.

14. Enjoy off grid encrypted text messaging!

   ![Finished Device](./images/finished.jpg)

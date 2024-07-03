# Meshtastic-LoRa-Radio

![the device](meshtastic%20project%20photos/piggyback1.jpg)


  
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
- Antenna long range (reccomended)- [Link](https://www.amazon.com/gp/product/B0CTXL61LY/ref=ox_sc_act_title_1?smid=A1SL54BY2F0SS5&th=1)
- 3.7v 1100mAh battery - [Link](https://www.amazon.com/dp/B08FD39Y5R?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- Screws - #6 x ½” self tapping (7mm x 13mm) - [Link](https://www.amazon.com/dp/B0B5CNQXMN?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- Magsafe ring - [Link](https://www.amazon.com/gp/product/B0CSVXD888/ref=ox_sc_saved_image_3?smid=A1M11WW4NKTCL&psc=1)
- Magnets - 5mm x 2mm - [Link](https://www.amazon.com/gp/product/B09DC8KG2C/ref=sw_img_1?smid=AZ3H0P0UI6KGB&psc=1)
- Switch - [Link](https://www.amazon.com/dp/B07RTJDW27?psc=1&ref=ppx_yo2ov_dt_b_product_details)

---

## Assembly:

1. Print case.
   
2. Download [Chrome browser](https://www.google.com/chrome/)
   
3. Using Chrome, flash latest meshtastic firmware to the main board. Select Heltec V3. [Link](https://meshtastic.org/docs/getting-started/flashing-firmware/esp32/web-flasher/)

   ![flasher](meshtastic%20project%20photos/meshtasticflasher.png)

4. Download meshtastic app from the AppStore or Google Play Store.

5. Cut ends of battery harness included in heltec V3 box.

6. Cut ends of 1100mAh battery cables

   ![battery harness](meshtastic%20project%20photos/harness.JPG)

7. Solder battery wires, switch and heltec harness together as shown. Battery to middle post on switch.

8. Insert switch into switch opening in case.

9. Install SMA connector into antenna hole on case.

   ![sma to case](meshtastic%20project%20photos/smatocase.jpg)

10. Connect antenna wire to board.

  ![sma to board](meshtastic%20project%20photos/smatoboard.JPG)

11. Insert battery.

12. Configure wires so case closes.

   ![sma to case](meshtastic%20project%20photos/alignwires.jpg)

13. Close case halves and screw together.

   ![screws](meshtastic%20project%20photos/screws.jpg)

14. Press magnets in back of the case.

15. Enjoy off grid encrypted text messaging!

   ![finished devices](meshtastic%20project%20photos/finished.jpg)

# ANCS-CCU-PANEL
ANCS CCU PANEL







# Uploading Firmware

In my design of the CCU Panel i used 4 ESP32 to achieve the resault i have now. 
1x Waveshare ESP32 S3 ETH (With POE Module mounted)
1x ESP32 S3 8x8 RGB Matrix
2x ESP32 C3 Super mini


**Board:** ESP32S3 Dev Module
**Power:** via PoE or USB-C
**Select COM Port:** Each board has a unique, consistent COM port.

> [!CAUTION]
> Only when uploading first time use "Erase All Flash Before Sketch Upload" as enabeled.
> 
> Next upload will clear all stored settings done in Web Setup!

<img width="492" height="686" alt="image" src="https://github.com/user-attachments/assets/6f949b59-9206-4541-ac31-7644b4ff46b2" />

**Upload:**
- Base code → controller ESP32-S3
- Camera code → all receiver ESP32-S3s

📦 [Download Code](https://github.com/Magnusvals/ANCS/releases) (Releases Tab)

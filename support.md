# HelioFleet for iOS – Support

HelioFleet lets a computer send photos, videos and files to an iPhone through a small
server that runs inside the app. The computer can also read device status, flash the
screen to find the device, set brightness and open a link on it. It's built for
developers and QA teams preparing test devices, and anyone can use it from a web browser.

## Getting started

1. Open **HelioFleet** on the iPhone and allow access to Photos when asked.
2. Make sure the iPhone and your computer are on the same Wi-Fi network.
3. On the computer, open the address shown in the app (for example
   `http://192.168.1.23:7777`) in a web browser. You can also scan the QR code in the app.
4. Enter the 6-digit **PIN** shown in the app.
5. Drop files onto the page:
   - **Photos and videos** (JPEG, PNG, GIF, HEIC, MP4, MOV) go to the Photos app.
   - **Other files** go to the Files app under On My iPhone › HelioFleet.

From the same page you can also see device status, flash the screen to find a device,
change screen brightness and open a link on the device.

## Frequently asked questions

**The page doesn't load.**
- Keep HelioFleet open on the iPhone. The server only runs while the app is on screen.
- Check that both devices are on the same Wi-Fi network.
- Some guest or office networks block devices from reaching each other.

**It says the PIN is wrong or that I'm locked out.**
- Enter the PIN shown in the app.
- After 5 wrong attempts, Wi-Fi access pauses for one minute.

**A video was rejected.**
- Photos accepts MP4 and MOV videos encoded with H.264 or HEVC. Convert other formats
  first.

**An upload failed with "insufficient storage".**
- Free up space on the iPhone. The app keeps about 200 MB in reserve while saving.

**Where are the files I sent?**
- Photos and videos are in the Photos app.
- Everything else is in Files › On My iPhone › HelioFleet.

**Can the app delete or read my photos?**
- No. It only has permission to add photos.

## Contact

[support@heliofleet.io](mailto:support@heliofleet.io)

---
title: Avro 2.0 (Linux) https://github.com/maateen/avro/releases
---

After a long time, we have tried to do something for the Avro (Linux). Now the Ubuntu-16.04 LTS has been released and we really need an easy installation way for this. No more waiting, the multi-arch supported .deb package has just arrived.

Installation

1. Please run these commands from the terminal. Never forget to be in relevant directory.

   wget "https://github.com/ugcoder/avro/releases/download/v2.0/avro_2.0-1_all.deb"
   
   sudo dpkg -i avro_2.0-1_all.deb
   
2. If you get any dependency error, then also run the following command:

   sudo apt-get install -fy

3. I hope, all is well now and the installation has been finished.

4. Go to System Settings -> Language Support from Unity Launcher

5. Look at the Keyboard input method system

6. Select IBus and close the window.

7. I believe that you need to restart IBus to make everything work fine. Try the following command:

   ibus restart

8. Now go to System Settings -> Keyboard -> Text Entry.

9. Search and add Avro Phonetic as input source. That's all.

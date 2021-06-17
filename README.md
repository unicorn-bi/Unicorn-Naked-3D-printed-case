# Unicorn Naked 3D printed case
The Unicorn Brain Interface is a high-quality wireless EEG-headset for brain-computer interface (BCI) applications to perfectly acquire brain waves. The Unicorn Brain Interface allows developers, artists and makers to acquire and process brain signals, ranging from simple display of the signals, to design and control attached devices or interact e.g. with artistic installations, toys, computer programs or applications. Unicorn Brain Interface acquires EEG from eight Unicorn Hybrid EEG Electrodes and comes with the Unicorn Suite, the main software application for the Unicorn Brain Interface. The data is sampled with 24 Bit and sampled with 250 Hz per channel. The unique Unicorn hybrid EEG electrodes allow users to record dry or with gel which enables the usage for many different applications.

[step1]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step1.PNG "Step 1"
[step2]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step2.PNG "Step 2"
[step3]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step3.PNG "Step 3"
[step4]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step4.png "Step 4"
[step5]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step5.png "Step 5"
[step6]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step6.png "Step 6"
[step7]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step7.png "Step 7"
[step8]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step8.PNG "Step 8"
[step9]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step9.png "Step 9"
[step10]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step10.PNG "Step 10"
[step11]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step11.PNG "Step 11"
[step12]: https://github.com/unicorn-bi/Unicorn-Suite-Hybrid-Black/blob/master/Unicorn%20Speller/Unity/Images/step12.PNG "Step 12"

1. Ensure that all prerequisites are installed on your computer. <br>
2. Create a new Unity project. <br>
![alt text][step1]
![alt text][step2]
3. Copy the 'UnicornSpellerInterface' folder to the 'Assets' folder of your Unity project. <br>
![alt text][step3]
4. Create a new Unity Game Object and add the 'Unicorn Speller Interface' with 'Add Component'. <br>
![alt text][step4]
![alt text][step5]
![alt text][step6]
5. Run your Unity project. Open the debug console. The debug console should feature an entry mentioning that the Unicorn Speller interface is listening to 127.0.0.1 on port 1000 (loop-back address if data is exchanged between programs on one machine). You can modify ip and port in the 'UnicornSpellerInterface.cs'. 7. Ensure that your firewall is not blocking data from Unicorn Speller and Unity. <br>
![alt text][step7]
6. Start the Unicorn Speller from Unicorn Suite Hybrid Black. <br>
![alt text][step8]
7. Open the 'Network output...' dialog to send test-data from Unicorn Speller to Unity. Ensure that the network configuration (ip and port) fit the settings defined in 'UnicornSpellerInterface.cs' (default ip 127.0.0.1 default port 1000). <br>
![alt text][step9]
8. Modify the 'Item name' and press 'Send Item...'. <br>
![alt text][step10]
9. Switch back to Unity. The debug console should feature an entry mentioning that an item was received. <br>
![alt text][step11]
10. You can modify the Board Items of in the 'Board Configuration' dialog. You can create your individual items that can be used within Unity using this interface. <br>
![alt text][step12]
11. You can modify 'UnicornSpellerInterface.cs' to add your game logic or change the network settings. <br>
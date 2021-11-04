# Hackintosh-Intel-i5-6200u-iGPU-HP-15-ay011nr-Monterey

# Info PC

```
NB: HP 15-ay011nr $270
CPU: Intel Core i5-6200u
VGA: Intel HD Graphics 520
RAM: 16GB (8GB + 8GB)
SSD: Kingston A400 500GB
Bluetooth: Intel Dual Band Wireless-AC 3165 $0
```

# Hackintosh + OpenCore 0.7.4

# Works

- Audio
- Ethernet (stops working if re-plug until reboot)
- Bluetooth
- All USB ports
- Camera

# Result

![Info](/images/info.png)
Geekbench 5 https://browser.geekbench.com/v5/cpu/10826364

# Note

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

```
<dict>
		<key>AdviseWindows</key>
		<true/>
		<key>MLB</key>
		<string>xxxxxxxxxxxxxxx</string>
		<key>ROM</key>
		<data>Z0SJO6Bu</data>
		<key>SpoofVendor</key>
		<true/>
		<key>SystemProductName</key>
		<string>iMac20,1</string>
		<key>SystemSerialNumber</key>
		<string>xxxxxxxxxxx</string>
		<key>SystemUUID</key>
		<string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
		<key>SystemMemoryStatus</key>
		<string>Auto</string>
</dict>
```

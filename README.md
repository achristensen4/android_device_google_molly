The defualt ADT-1 (Molly) CM-13.0 configuration is limited to TV features., i.e. no Navigation Bar/Status Bar. The goal of the cm-12.1-tablet branch is to restore the defualt CyanogenMod Tablet Configuration.

To opt to use this instead of the default TV configuration, edit your roomservice.xml, and append this to the end of the "device/google/molly" entry: revision="cm-13.0-tablet"

Please do not attempt to use the provided TV GApps with this. It will end in a TON of singature mismatches. Please use the latest OpenGApps-ARM-Mini package on www.opengapps.org

# Google ADT-1 ("molly") Device Configuration 

## Spec Sheet
| Feature                 | Specification                                                                               |
| :---------------------- | :------------------------------------------------------------------------------------------ |
| Chipset                 | Quad Core 1.9GHz NVIDIA® Tegra 4 (Cortex-A15)<br/>NVIDIA® GPU                               |
| Memory                  | 2GB LPDDR3<br/>16GB Storage                                                                 |
| Network Interfaces      | 10/100 Ethernet<br/>802.11 a/b/g/ 2×2 MIMO WiFi<br/>Bluetooth  v4.0                         |
| Ports                   | USB 2.0<br/>HDMI Out<br/>RJ-45 (Wired Internet)<br/>USB Mini-AB (Power Input/USB debugging) |
| Shipped Android Version | 4.4.4 KitKat (Test TV Version), later received multiple OTA updates through the L Previews, and finally, to 5.0.2 Lollipop (LRX22G)                                                             |
| Gamepad                 | Bluetooth 3.0 (4.0 compatible)               			                        |
| Release Date            | June 25, 2014                                                                               |

## Device Picture
![Gooogle ADT-1](http://www.cnx-software.com/wp-content/uploads/2014/06/ADT-1_ANdroid_TV_Reference_Design.jpg "Gooogle ADT-1")

## Copyright

```
#
# Copyright (C) 2015 The CyanogenMod Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
```

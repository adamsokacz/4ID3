# Bluetooth

Bluetooth is a wireless communication technology that allows devices to exchange data over short distances. Bluetooth operates on unlicensed radio bands in the 2.4 GHz frequency range.

Pairing is when two Bluetooth devices establish a secure connection. Once paired, they can then begin to exchange data at a typical distance of up to 10 m.

Common applications of bluetooth include transmitting data files using applications like airdrop and streaming audio to bluetooth earbuds.

The following diagram describes a typical packet structure:

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

A notable limitation of Bluetooth Classic is that it can only support up to 7 slave devices in the network. This is because 3 bits of data can only generate 8 unique addresses. One of these addresses is reserved for the master device.

A use-case improvement over Bluetooth Classis is Bluetooth Low Energy, or BLE. BLE is designed to minimize power consumption, which makes it an ideal choice for resource restricted embedded devices like smart sensors. However, this limited power consumption also causes a significant reduction in data transfer rate, which limits its usability in many products.&#x20;


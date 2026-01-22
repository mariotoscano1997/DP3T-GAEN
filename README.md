# DDP3T & GAEN: A Study of Contact Tracing Protocols and Implementation on ESP32
This repository contains the project for my Bachelor’s degree in Computer Science, focusing on the analysis and implementation of privacy-oriented Contact Tracing protocols. The work provides an in-depth study of the DP3T (Decentralized Privacy-Preserving Proximity Tracing) protocol in its Low-cost, Unlinkable, and Hybrid variants, as well as the GAEN (Google Apple Exposure Notification) framework.

Key features of the project include:


Protocol Analysis: A comparative study between decentralized designs and their compliance with GDPR guidelines to ensure user anonymity.


Hardware Implementation: A practical implementation of the DP3T Hybrid protocol on an ESP32 microcontroller (specifically using the TTGO-Camera Plus board).


Proximity Sensing: Leveraging Bluetooth Low Energy (BLE) and the GAP protocol to detect nearby devices through ephemeral identifiers (EphIDs).


Cryptography: Implementation of secure data handling using SHA-256 for hashing, HMAC for pseudo-random functions, and AES-CTR for generating pseudo-random identifiers.

The system is designed to store encounter data locally on the device, uploading data to a central server only in the event of a positive COVID-19 report, thereby maintaining the highest standards of user privacy

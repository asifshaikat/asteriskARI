# Asterisk Interface Feature Comparison

## Overview
This repository provides a structured comparison of the three primary Asterisk interfaces:

- **Asterisk REST Interface (ARI)**
- **Asterisk Gateway Interface (AGI)**
- **Asterisk Manager Interface (AMI)**

The comparison outlines key functionalities available in each interface to help developers choose the most suitable option based on their requirements.

This repository was inspired by the discussion on the Asterisk community forum: [AGI, AMI, and ARI Features List](https://community.asterisk.org/t/agi-ami-and-ari-features-list-asterisk/103320).

Official link for all interfaces on the Asterisk docs [Interface List](https://docs.asterisk.org/Configuration/Interfaces/).


## Table of Features
The feature comparison table is available in **Markdown format** for easy reference. It covers various capabilities such as call control, media handling, event subscriptions, authentication, and external integrations.

[View the Full Feature Comparison Table](./FEATURES.md)

## When to Use Each Interface

- **ARI (Asterisk REST Interface):**
  - Best for real-time control of calls and channels
  - Useful for applications needing WebSocket event subscriptions
  - Ideal for dynamic call applications with custom logic

- **AGI (Asterisk Gateway Interface):**
  - Suitable for executing external scripts for call handling
  - Works well for Interactive Voice Response (IVR) systems
  - Good for integrating Asterisk with databases and CRM systems

- **AMI (Asterisk Manager Interface):**
  - Designed for real-time monitoring and management of Asterisk
  - Ideal for call center applications, logging, and event-driven call control
  - Best for managing queues, SIP registrations, and Voicemail

## Next Steps

1. Open `FEATURES.md` to explore the feature comparison table.

2. Contribute by submitting issues or pull requests to enhance this documentation.

## Contributions
Contributions are welcome! Feel free to submit a pull request with improvements or additional insights related to Asterisk interfaces.

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

# Extended Essay Experiment Results: VPN and Proxy Protocols Analysis

## Overview

This repository contains the experimental data, code, and analysis for the Extended Essay titled "xxxxx"

The research investigates common VPN and proxy protocols, as well as the newly developed REALITY protocol, focusing on their impact on security, efficiency, and ethical considerations.

## Experiments

The experiments were conducted to analyze the following aspects:

1. **Security Performance:** Evaluating encryption, authentication mechanisms, and protection against Man-in-the-Middle attacks.
2. **Efficiency:** Assessing latency, bandwidth, and hardware overheads.
3. **User Accessibility:** Examining ease of use, compatibility, and user experience.
4. **Ethical Considerations:** Investigating user consent, transparency, privacy, surveillance practices, and QoS.

In this particular experiment, the focus was on evaluating the susceptibility and response of various VPN and proxy protocols, including HTTP, OpenVPN, the REALITY protocol, Socks 5, and Wireguard, to Man-in-the-Middle (MITM) attacks. The experiment was conducted by simulating a MITM attack scenario where an unauthorized entity attempts to intercept and possibly alter the communication between the client and server. Three different websites were accessed using each of the protocols, and the data transmitted was analyzed to determine what information could be intercepted or manipulated by a potential attacker. 

## Contents

The repository is organized into the following folders, each containing data and analysis related to specific protocols:

- `With HTTP/`: Data and analysis for experiments conducted with HTTP.
- `With no VPN/proxy/`: Data and analysis for experiments conducted without VPN or proxy.
- `With Open VPN/`: Data and analysis for experiments conducted with OpenVPN.
- `With Reality/`: Data and analysis for experiments conducted with the REALITY protocol.
- `With Socks 5/`: Data and analysis for experiments conducted with Socks 5.
- `With Wireguard/`: Data and analysis for experiments conducted with Wireguard.

Each folder contains the Wireshark export data with specific filters applied. 

## How to Access the Data

1. Clone this repository to your local machine.
2. Navigate to the specific folder of interest to access the raw data files, scripts, and analysis notebooks.

## Contributing

While this repository primarily serves as a supplement to the Extended Essay, contributions, questions, and feedback are welcome. Please open an issue or submit a pull request if you have any inquiries or suggestions.

## License

This work is licensed under the MIT License. See the LICENSE.md file for details.



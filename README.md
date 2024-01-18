<a href="https://github.com/cybergeekgyan">
  <h1 align="center">Wi-Fi Stock Crossover Notifier</h1>
</a>

The Wi-Fi Stock Crossover Notifier is an Arduino-based project that monitors stock data in real-time and sends email notifications when specific moving average crossovers occur. The project focuses on short-term investing using the 9 & 21 EMA crossover and long-term investing using the 50 & 200 SMA crossover strategies.

<p align="center">
  <a href="https://twitter.com/cybergeekgyan">
    <img src="https://img.shields.io/twitter/follow/cybergeekgyan?style=flat&label=cybergeekgyan&logo=twitter&color=0bf&logoColor=fff" alt="Twitter" />
  </a>
  <a href="https://github.com/cybergeekgyan/Wi-Fi-Stock-Crossover-Notifier/blob/main/LICENSE.md">
    <img src="https://img.shields.io/github/license/cybergeekgyan/Wi-Fi-Stock-Crossover-Notifier?label=license&logo=github&color=f80&logoColor=fff" alt="License" />
  </a>
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#hardware-requirements"><strong>Hardware Requirements</strong></a> ·
  <a href="#software-requirements"><strong>Software Requirements</strong></a> ·
  <a href="#contributing"><strong>Contributing</strong></a>
</p>
<br/>


## Introduction

Traders/Investors often utilize moving average crossovers as a technical analysis tool to identify potential trend reversals or shifts in market sentiment. The Wi-Fi Stock Crossover Notifier automates this process by combining the power of Arduino microcontrollers, Wi-Fi connectivity module, and algorithmic trading strategies.

![Project Image](link_to_project_image.jpg)

## Features

- **Real-Time Monitoring:** The system continuously fetches up-to-date stock data through a chosen stock data API.
- **Crossover Detection:** Utilizes algorithms to detect crossovers based on Exponential Moving Averages (EMAs) and Simple Moving Averages (SMAs).
- **Email Notifications:** Sends email notifications to a specified address when a crossover is identified, allowing users to stay informed about potential trading opportunities.

## Hardware Requirements

- Arduino Microcontroller (e.g., Arduino Uno)
- ESP8266 or ESP32 Wi-Fi module for Internet connectivity

## Software Requirements

- Arduino IDE
- Programming Language (C++, Embedded C, Python)
- Necessary libraries (e.g., ESP8266WiFi, SMTPClient)
- RESTAPI/FastAPI, HTTP Requests
- Stock data API (e.g., Alpha Vantage)
- Email service (e.g., SMTPClient for Email communication)
- Stock data API key
- Email account for notifications

<!---
## Setup

1. Connect the Arduino to your computer.
2. Install the required Arduino libraries and set up the Arduino IDE.
3. Configure the Wi-Fi module to connect to your Wi-Fi network.
4. Obtain a stock data API key and configure the code to fetch real-time stock data.
5. Set up an email account for sending notifications and configure the email settings in the code.

## Usage

1. Upload the Arduino sketch to the microcontroller.
2. Power on the Arduino and Wi-Fi module.
3. The system will start monitoring stock data and generate email notifications on crossovers.

## Configuration

- Adjust the stock symbols, moving average periods, and other parameters in the code.
- Ensure secure storage of sensitive information such as API keys and email credentials.

## BackTesting

- Test the system with historical data to validate crossover detection.
- Simulate trading scenarios to ensure proper functionality.

## Security Considerations

- Securely store API keys and email credentials.
- Regularly monitor and update the project for security patches.

-->

## Contributing

We welcome contributions from the AI community. Whether you're interested in improving our website, collaborating on AI projects, or sharing your expertise, we're excited to work together. Check out our [Contributing Guidelines](CONTRIBUTING.md) to get started.

We love our contributors! Here's how you can contribute:

- [Open an issue](https://github.com/cybergeekgyan/Wi-Fi-Stock-Crossover-Notifier/issues) if you believe you've encountered a bug.
- Make a [pull request](https://github.com/cybergeekgyan/Wi-Fi-Stock-Crossover-Notifier/pull) to add new features/make quality-of-life improvements/fix bugs.

## License

This project is licensed under the [Apache2.0 License](LICENSE).

## Acknowledgments

- Thanks to [Alphavantage]() for providing real-time stock data.
- Special thanks to the Arduino and ESP community for their support.

<p align="center">
Made with :heart: by Gyan <br>
</p>

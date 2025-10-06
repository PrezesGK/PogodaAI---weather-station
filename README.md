# PogodaAI---weather-station

PogodaAI is an open-source project that combines a solar-powered, modular weather and air quality station with a local AI model for pollution prediction.
The goal is to create a dense, affordable sensor network that supports communities and educational initiatives.


--- Features ---

☀ Fully autonomous – solar power + Li-Po battery (2–3 days autonomy)

- Modular design – easy sensor replacement or expansion

- Multi-sensor setup – PM1.0, PM2.5, PM10, temperature, humidity, pressure, VOC, wind, rain

- Wireless data transfer via ESP32 WiFi

- AI-based air quality forecasting using historical data

- Open source & DIY-friendly


--- Hardware ---

ESP32 (WiFi + low power modes)

PMSA003, BME680, YL-83, photodiode, custom 3D-printed anemometer & wind vane

Solar panel + Li-Po battery + charge controller

LCD 4×20 + keypad + SD card for local data logging

3D-printed PET-G weather-resistant housing with TPU gaskets

!!! CAD files, wiring diagrams, and BOM are provided in the hardware/ directory.


--- AI Model ---

Trained on open datasets (Edukacyjna Sieć Antysmogowa)

Predicts air quality based on 24h historical windows

Runs locally, lightweight & accessible

The whole AI model can be accessed at: ... WSTAW TU LINK

--- Why It Matters ---

PogodaAI enables local communities to monitor and predict air quality independently.
The system is affordable, modular, and open, making it ideal for education, research, and environmental action.

📂 Repository Structure
pogodaAI/
├─ hardware/          # PCB files, 3D models, wiring, firmware
├─ docs/              # Documentation, diagrams, photos
├─ examples/          # Demo scripts
├─ LICENSE
└─ README.md

📜 License

Open-source under the MIT License. You are free to use, modify, and distribute.

🤝 Contributing

Contributions are welcome!
Submit issues, pull requests, or improvements to the documentation.

📸 Gallery

![IMG_5428](https://github.com/user-attachments/assets/ef501315-47ab-43dc-ae49-e98b1c71599f)
![IMG_5431](https://github.com/user-attachments/assets/3cff6415-c234-4fa3-a308-31e5a326c136)
<img width="716" height="775" alt="Zrzut ekranu 2025-10-6 o 17 32 16" src="https://github.com/user-attachments/assets/7d130af7-a327-4c12-808d-ab55aad25444" />


✨ Credits

Developed by Krasiniak TechWorks for Techniokon ESA 2025.

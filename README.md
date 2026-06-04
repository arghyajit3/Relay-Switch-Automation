# Relay Switch Automation
Home Automation using relay-switch

## About this project
This is a Project that I'm working on to automate most of the **Electronic devices** and *switches* in a home.
This project is aimed at making control over our day to day devices much easier and faster to control at the palm of your hand, without replacing the traditional physical switches that we all still love for its simplicity and use today.

### Components Used
1. Arduino Nano (for non-Wifi or Bluetooth compatibility / only IR support) (OR)
2. ESP32 (for WiFi + Bluetooth compatibility along with IR support)
3. HLK-PM12 100V AC - 240V AC, 50 - 60Hz to 5V DC / 3W
4. Mini 360 DC to DC Step Down Buck Converter (to 7V or 5V depending on microcontroller module)
5. 12V 4-Channel Relay with Octocoupler (More relays can be added in the future, at request)
6. IR Photo Diodes
7. IR Remote
8. Possible MOV - 14D621K Varistor in Parallel to HLK-PM12, between Live and Neutral to be added later on.
9. Possible 500mA Cermaic/Glass Slow-Blow Fuse in series to Live wire connecting to HLK-PM12 to be added later on.

### Prequisites (For Customers)
1. Stabiliser to maintain near constant 230V
2. Electrical connections installed in house to required load
3. Switchboard Cutout on wall

> Still in development phase.

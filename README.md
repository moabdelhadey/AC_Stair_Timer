# AC Stair Timer (High-Load AC Triggered Timer Circuit using NE555)

An affordable and energy-efficient timer circuit designed to control stairway lighting. The circuit is triggered by an AC signal from any stair switch and automatically turns off the light after a user-defined delay. It consumes **no power while idle**, thanks to a latch mechanism that cuts off the entire supply when the relay opens.

---

## ✅ Features

- **AC Triggered**: Can be triggered from any AC switch connected in the stairway.
- **Zero Power Consumption in Standby**: Power supply is wired in series with the load. Once the relay disconnects the load, the entire circuit powers off.
- **Handles up to 10A Load**: Suitable for high-power lighting circuits.
- **Adjustable Timer (0–15 min)**: Controlled by a potentiometer. Can be extended using standard NE555 timing calculations.
- **Low-Cost and Simple Components**: Built around NE555, a relay, and basic resistors/capacitors.
- **Single-Layer PCB**: Easy for home etching or low-cost fabrication.
- **Local Alternative to Imported Units**: Provides the same functionality at a fraction of the cost.

---

## 🧩 Main Components

- NE555 Timer IC
- Relay (10A rated)
- Potentiometer
- Capacitors and resistors

---

## ⏱️ Time Adjustment Formula

You can calculate or extend the timing duration using the standard NE555 monostable formula:

```
T ≈ 1.1 × R × C
```

Where:
- `R` is the potentiometer (resistance in ohms)
- `C` is the timing capacitor (in farads)

---

## 📁 Project Files

- **KiCad** design files (schematic + PCB layout)
- **Proteus** simulation file
- **STEP file** (3D model of assembled circuit)
- **PDFs** for manual PCB etching (Top layer, Drill, Silkscreen)
- Real-life **assembly images**

---

## 🧪 Project Status

- ✅ **Version 1** tested successfully in a real stairway.
- 🛠️ **Version 2** in development with enhancements.

---

## ⚠️ Safety Notes

- Ensure proper isolation when connecting to AC.
- Add relay cooling if switching high loads frequently.

---

## 📜 License

This project is open source and licensed under the [MIT License](LICENSE).

---

## 📷 Images




---

## 📬 Contact

Mohamed Abdelhady — For inquiries, feel free to reach out if any issue arises.

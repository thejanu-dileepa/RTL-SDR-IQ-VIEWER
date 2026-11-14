# RTL-SDR IQ Viewer
### Flutter Desktop Application for Windows

<img width="1043" height="732" alt="Screenshot 2026-11-14 162220" src="https://github.com/user-attachments/assets/f003ca9a-09d7-4da4-aa69-681d261682dd" />
<img width="1035" height="723" alt="Screenshot 2026-11-14 162309" src="https://github.com/user-attachments/assets/89f057c9-cf70-4de0-89bb-e3b8717bb498" />

**RTL-SDR IQ Viewer** is a real-time SDR signal visualization and raw IQ data analysis application developed using Flutter Desktop for Windows. It is designed to work with RTL-SDR USB dongles based on the RTL2832U chipset and R820T2 / R860 tuner.

The application provides an intuitive graphical interface for monitoring, visualizing, capturing, and inspecting raw IQ (In-phase and Quadrature) signals in real time.

## 🚀 Key Features

### 1. Live SDR Monitoring

- Automatic detection of connected RTL-SDR devices.
- Direct communication with RTL-SDR hardware.
- Real-time frequency tuning.
- Continuous raw IQ sample streaming.
- Live FFT spectrum visualization.
- Real-time waterfall display.
- Automatic signal detection and classification.
- Separate I/Q waveform visualization.
- Live signal monitoring and analysis.

### 2. IQ Signal Visualization

The application provides multiple visualization tools to understand incoming radio signals:

- **FFT Spectrum:** Displays signal strength across the frequency spectrum.
- **Waterfall Display:** Shows how radio signals change over time.
- **I/Q Waveform:** Displays separate In-phase (I) and Quadrature (Q) signal components.
- **Raw Sample Viewer:** Displays incoming IQ samples in both unsigned and signed formats.

### 3. Raw IQ Data Inspection

The Inspection mode allows users to analyze previously recorded IQ data or inspect the currently running live SDR stream.

Supported data sources include:

- RTL-SDR raw IQ dumps.
- CS16 (16-bit complex samples).
- CF32 (32-bit floating-point complex samples).
- SigMF (Signal Metadata Format).
- Live SDR data stream.

### 4. IQ Packet Viewer

A dedicated IQ Packet Viewer window provides detailed inspection of raw IQ data.

Features include:

- Packet-by-packet data inspection.
- Raw sample analysis.
- IQ packet structure visualization.
- Detailed inspection of individual data packets.
- Analysis of recorded and live IQ streams.

### 5. Live Performance Statistics

The application displays important real-time streaming statistics:

- Total samples received.
- Incoming data rate (MB/s).
- Stream elapsed time.
- Continuous sample monitoring.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Application Framework | Flutter Desktop |
| Programming Language | Dart |
| SDR Hardware Interface | librtlsdr |
| Dart Integration | rtlsdr Dart Package |
| Native Integration | FFI |
| Target Platform | Windows Desktop |
| SDR Chipset | RTL2832U |
| Supported Tuners | R820T2 / R860 |

## 📡 Hardware Compatibility

Designed for RTL-SDR USB receivers featuring:

- RTL2832U USB demodulator.
- R820T2 tuner.
- R860 tuner.

## 🖥️ Operating Modes

**Live Mode**

Connect an RTL-SDR dongle, tune to a desired frequency, receive raw IQ samples, and visualize radio signals using real-time spectrum, waterfall, and waveform displays.

**Inspection Mode**

Load an existing IQ recording or select the live SDR stream to inspect its raw data through a dedicated packet viewer.

## 🎯 Project Goals

The primary goal of RTL-SDR IQ Viewer is to provide an accessible desktop environment for SDR enthusiasts, radio experimenters, and developers to visualize and investigate raw IQ signals without relying entirely on command-line tools.

It combines real-time SDR reception, signal visualization, raw data inspection, and performance monitoring in a single desktop application.

---

**Project:** RTL-SDR IQ Viewer  
**Platform:** Windows Desktop  
**Framework:** Flutter  
**Purpose:** Real-Time SDR Monitoring & IQ Signal Analysis

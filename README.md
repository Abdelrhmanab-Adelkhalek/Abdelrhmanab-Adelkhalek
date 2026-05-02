<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>ESP32-S3 4-Layer Development Board</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #0f172a;
        color: #e2e8f0;
        margin: 0;
        padding: 0;
        line-height: 1.6;
    }
    header {
        background: #1e293b;
        padding: 20px;
        text-align: center;
    }
    h1 {
        margin: 0;
        color: #38bdf8;
    }
    .container {
        padding: 20px;
        max-width: 900px;
        margin: auto;
    }
    h2 {
        color: #38bdf8;
        border-bottom: 1px solid #334155;
        padding-bottom: 5px;
    }
    .card {
        background: #1e293b;
        padding: 15px;
        margin: 15px 0;
        border-radius: 10px;
    }
    ul {
        padding-left: 20px;
    }
    code {
        background: #0f172a;
        padding: 2px 5px;
        border-radius: 5px;
        color: #38bdf8;
    }
</style>
</head>

<body>

<header>
    <h1>🚀 ESP32-S3 4-Layer Development Board</h1>
    <p>Designed using Altium Designer | Embedded Hardware Project</p>
</header>

<div class="container">

    <div class="card">
        <h2>📌 Overview</h2>
        <p>
            This project is a custom-designed 4-layer ESP32-S3 development board built using Altium Designer.
            It focuses on high-speed design, power integrity, and professional PCB layout techniques.
        </p>
    </div>

    <div class="card">
        <h2>⚙️ Hardware Specifications</h2>
        <ul>
            <li>MCU: ESP32-S3-MINI-1-N8</li>
            <li>USB-C Port 1: FTDI USB-to-UART (Flashing & Debugging)</li>
            <li>USB-C Port 2: Native USB (GPIO 19/20)</li>
        </ul>
    </div>

    <div class="card">
        <h2>🧱 PCB Stack-Up (4 Layers)</h2>
        <ul>
            <li>L1: Signal + Power</li>
            <li>L2: 3V3 + GND Plane</li>
            <li>L3: Solid GND Plane</li>
            <li>L4: Signal + Power</li>
        </ul>
    </div>

    <div class="card">
        <h2>🔧 Key Design Techniques</h2>
        <ul>
            <li>Controlled impedance routing for USB differential pairs</li>
            <li>Continuous ground return paths for signal integrity</li>
            <li>Thermal vias for efficient heat dissipation</li>
            <li>ESD protection using TVS diodes</li>
        </ul>
    </div>

    <div class="card">
        <h2>💡 Highlights</h2>
        <ul>
            <li>Dual USB architecture (Debug + Native USB)</li>
            <li>Production-level PCB design approach</li>
            <li>Optimized for EMI and power stability</li>
        </ul>
    </div>

    <div class="card">
        <h2>🎯 Learning Outcomes</h2>
        <ul>
            <li>4-layer PCB design in Altium Designer</li>
            <li>High-speed signal routing (USB)</li>
            <li>Power integrity and grounding strategies</li>
            <li>Real-world embedded hardware design</li>
        </ul>
    </div>

    <div class="card">
        <h2>🚀 Future Improvements</h2>
        <ul>
            <li>EMI/EMC optimization</li>
            <li>Better decoupling network design</li>
            <li>Additional communication interfaces (CAN / LoRa)</li>
        </ul>
    </div>

</div>

</body>
</html>

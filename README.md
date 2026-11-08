[![Twitter: @NorowaretaGemu](https://img.shields.io/badge/X-@NorowaretaGemu-blue.svg?style=flat)](https://x.com/NorowaretaGemu)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<div align="center">
  <a href="https://ko-fi.com/cursedentertainment">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi" style="width: 20%;"/>
  </a>
</div>

# DREAM Robotics

The home page of the DREAM Robotics ecosystem: a family of home-made robots and the AI minds that look after them. Every robot and mind has its own repo; this one ties them together.

The minds run on PCs with local AI (Ollama, Whisper, Piper), the robots are ESP32, Arduino and Raspberry Pi builds, and they all find each other through RIFT, the fleet hub, over NORA's WiFi (or Bluetooth). The fleet's web APIs live on ports 5000-5999.

## Minds

| Name | Who they are |
| --- | --- |
| [DREAM](https://github.com/CursedPrograms/DREAM) | The companion: an offline AI with an inner life. Wake word, Whisper, Ollama, a Piper voice and an avatar. ([site](https://cursedprograms.github.io/DREAM/)) |
| [TINA](https://github.com/CursedPrograms/TINA) | The engineer: a local LLM agent that reads, edits, compiles and checks code across the robot repos. ([site](https://cursedprograms.github.io/TINA/)) |
| [NINA](https://github.com/CursedPrograms/NINA) | The caretaker: she watches every robot through RIFT and explains what went wrong, out loud. ([site](https://cursedprograms.github.io/NINA/)) |
| [RIFT](https://github.com/CursedPrograms/RIFT) | The fleet hub: his robot registry, mDNS discovery and live dashboard, in Python and many other languages. ([site](https://cursedprograms.github.io/RIFT/)) |
| [LYCEA](https://github.com/CursedPrograms/LYCEA) | The school: a Unity ML-Agents project where NORA learns to drive and WHIP learns to walk. |

## Robots

| Name | Who they are |
| --- | --- |
| [NORA](https://github.com/CursedPrograms/NORA-Robot-v00) | ESP32 mecanum robot and the fleet's WiFi hub, with her MP3 player and four-way ultrasonic braking. ([site](https://cursedprograms.github.io/NORA-Robot-v00/)) |
| [MILA](https://github.com/CursedPrograms/MILA-Robot-v00) | Small WiFi tank robot on an Arduino Uno + ESP8266, with controllers in seven languages. ([site](https://cursedprograms.github.io/MILA-Robot-v00/)) |
| [NIKA](https://github.com/CursedPrograms/NIKA-Robot-v00) | MILA's sister, whose mind is a synthesizer: she thinks in square waves. ([site](https://cursedprograms.github.io/NIKA-Robot-v00/)) |
| [WHIP](https://github.com/CursedPrograms/WHIP-Robot-v00) | 18-servo ESP32 hexapod; he walks for a PS2-style pad, the browser or IR. ([site](https://cursedprograms.github.io/WHIP-Robot-v00/)) |
| [KIDA-00](https://github.com/CursedPrograms/KIDA-Robot-v00) | Raspberry Pi 3 tank robot with live video and on-device age and gender detection. ([site](https://cursedprograms.github.io/KIDA-Robot-v00/)) |
| [KIDA-01](https://github.com/CursedPrograms/KIDA-Robot-v01) | Raspberry Pi 5 tank robot with a Hailo-8L, AI cameras and a local LLM. ([site](https://cursedprograms.github.io/KIDA-Robot-v01/)) |
| [IDA](https://github.com/CursedPrograms/IDA-Robot-v00) | Small Arduino Uno tank robot, driven entirely by IR remote. ([site](https://cursedprograms.github.io/IDA-Robot-v00/)) |
| [ARM](https://github.com/CursedPrograms/ARM-Robot-v01) | 6-DOF robot arm on an Arduino Uno and PCA9685, with IK and phone control. ([site](https://cursedprograms.github.io/ARM-Robot-v01/)) |
| [ARIA](https://github.com/CursedPrograms/ARIA-Robot-v00) | Aerial Roaming Intelligent Automaton: the ESP32 drone. ([site](https://cursedprograms.github.io/ARIA-Robot-v00/)) |
| [AURA](https://github.com/CursedPrograms/AURA) | The weather station: Open-Meteo outside, the fleet's temperature and humidity inside. ([site](https://cursedprograms.github.io/AURA/)) |
| [FLORA](https://github.com/CursedPrograms/FLORA-Robot-v00) | The gardener: an ESP32 that feels the soil, light and UV around a plant and waters it. ([site](https://cursedprograms.github.io/FLORA-Robot-v00/)) |
| [RITA](https://github.com/CursedPrograms/RITA) | The handheld remote: a 3.5-inch ESP32 touch screen, RIFT in your hand. ([site](https://cursedprograms.github.io/RITA/)) |

## Tools around the fleet

[CRUSH](https://github.com/CursedPrograms/CRUSH) (compression) · [PyVitals](https://github.com/CursedPrograms/PyVitals) (system monitor) · [Scan-WIFI-Devices](https://github.com/CursedPrograms/Scan-WIFI-Devices) (who's on the network) · and everything else in the [cursed directory](https://cursed-entertainment.github.io/cursed-directory/).

## License

MIT, see [LICENSE](LICENSE).

<br>
<div align="center">
© Cursed Entertainment 2026
</div>
<br>
<div align="center">
<a href="https://cursed-entertainment.itch.io/" target="_blank">
    <img src="https://raw.githubusercontent.com/CursedPrograms/cursedentertainment/main/images/logos/logo-wide-grey.png"
        alt="CursedEntertainment Logo" style="width:250px;">
</a>
</div>

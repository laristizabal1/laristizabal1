# SELECT * FROM developers WHERE name = 'Luis Aristizabal';

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-angel-aristizabal-correa-09015a359/)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luis0415angelco@gmail.com)

</div>

---

```sql
CREATE TABLE luis_aristizabal (
    role                VARCHAR(100) PRIMARY KEY DEFAULT 'Electrical & Electronic Engineering Student',
    location            VARCHAR(50) DEFAULT 'Bogotá, Colombia',
    university          VARCHAR(100) DEFAULT 'Universidad de los Andes',
    degrees             TEXT[] DEFAULT ARRAY['Electrical Engineering', 'Electronic Engineering'],

    -- Core Stack
    embedded_stack      TEXT[] DEFAULT ARRAY['ESP32', 'Arduino', 'I2C/SPI', 'State Machines'],
    power_energy_stack  TEXT[] DEFAULT ARRAY['DC-DC Converters', 'Microgrids', 'Power Supplies'],
    software_stack      TEXT[] DEFAULT ARRAY['Python', 'MATLAB', 'LaTeX', 'C++'],

    -- Current Work
    main_project        VARCHAR(100) DEFAULT 'PV Array Emulator for DC Microgrids',
    project_url         VARCHAR(200) DEFAULT 'github.com/laristizabal1/PV-Emulator',

    -- Contact
    email               VARCHAR(100) DEFAULT 'luis0415angelco@gmail.com'
);
```

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=laristizabal1&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laristizabal1&layout=compact&hide_border=true" alt="Top Languages" />

</div>

---

## Tech Stack

```sql
SELECT * FROM skills ORDER BY field;
```

### Hardware & Embebidos
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)

### Software & Análisis
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

### Herramientas
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Featured Projects

```sql
SELECT project_name, description, tech_stack FROM projects WHERE featured = true;
```

| Project | Description | Tech Stack |
|---|---|---|
| [**PV Array Emulator**](https://github.com/laristizabal1/PV-Emulator.git) | Emulador trazable de arreglo fotovoltaico basado en fuente DC programable, para microrredes DC | `Power Electronics` `DC Microgrids` `Instrumentation` |
| [**limpiaVidrios**](https://github.com/fgutep/limpiaVidrios.git) | Robot limpiavidrios controlado mediante una máquina de estados para los motores, con indicadores luminosos NeoPixel según nivel de voltaje, sensor de color TCS34725, giroscopio/acelerómetro MPU6050 para orientación, control remoto por gamepad (Bluepad32) y telemetría vía WiFi (ESPAsyncWebServer). Proyecto colaborativo con Felipe Gutiérrez | `ESP32` `State Machines` `MPU6050` `NeoPixel` `Bluepad32` |
| **MENTORU** | Wearable inteligente para corrección de postura (IMU + retroalimentación en tiempo real) | `ESP32` `MPU6050` `OLED` |

---

<div align="center">

### De los circuitos al código

<img src="https://komarev.com/ghpvc/?username=laristizabal1&label=Profile+Views&color=0e75b6&style=flat-square" alt="profile views" />
<img src="https://img.shields.io/github/followers/laristizabal1?style=flat-square&color=0e75b6&labelColor=0D1117" alt="followers" />

</div>

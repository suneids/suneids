<table align="right">
  <tr>
    <td><a href="./README.md">🇬🇧 English</a></td>
    <td><b>🇷🇺 Русский</b></td>
  </tr>
</table>

## 🛠 Избранные инженерные проекты

<table width="100%">
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/suneids/Hexapod">
        <img src="Hexapod.gif" width="100%" alt="Hexapod">
      </a>
      <h3>
        🕷️ <a href="https://github.com/suneids/Hexapod">Hexapod</a>
      </h3>
      <p>18 DOF · STM32 · CAN · обратная кинематика</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/suneids/Glove">
        <img src="https://raw.githubusercontent.com/suneids/suneids/main/Car-glove.gif" width="100%" alt="Glove + Car">
      </a>
      <h3>
        🧤 <a href="https://github.com/suneids/Glove">Glove MK2</a>
        +
        <a href="https://github.com/suneids/Car">RC Car MK2.5</a> 🚗
      </h3>
      <p>STM32 · IMU · носимый HMI · радиоуправление</p>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">
      <a href="https://github.com/suneids/Gauntlet">
        <img src="Gauntlet.gif" width="100%" alt="Gauntlet">
      </a>
      <h3>
        🖥️ <a href="https://github.com/suneids/Gauntlet">Gauntlet</a>
      </h3>
      <p>
        Linux · Qt · X11 · IPC · Modbus · носимая инженерная платформа
      </p>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">
      <h3>
        🔧 <a href="https://github.com/suneids/HAL">
          Низкоуровневые драйверы STM32
        </a>
      </h3>
      <p>
        Register-level драйверы · GPIO · UART · SPI ·
        CAN/FDCAN · Modbus RTU · Flash/NVM
      </p>
    </td>
  </tr>
</table>


<table style="width:100%; border:1px solid #30363d;">
<tr><td align="center">

<h2>🛠 Инженерная дорожная карта: от датчиков к экзоскелетам</h2>

<i>Долгосрочный путь от embedded-систем и сенсоров к кибернетическим системам и интеграции человека с машиной. Здесь отслеживается развитие от низкоуровневой электроники и искусственных рефлексов до сложных HMI и экзоскелетов.</i>

</td></tr>

<tr><td><details>
<summary><h2>🧬 Фаза 1: Анатомия (июль 2025 — февраль 2026) 🏁</h2></summary>

<i>Фокус: Sensor Fusion, Bare Metal, низкоуровневые протоколы</i>

- [x] [**🚗 Проект: Car v2.5** — STM32, PWM, Bluetooth / управление по 433 МГц](https://github.com/suneids/Car)
- [x] [**🧤 Проект: Glove MK2** — MPU6500 Fusion, DMA/ADC, Soft UART, распознавание жестов](https://github.com/suneids/Glove)
- [x] **🧩 Навык: PCB Design** — двухслойные платы с учётом EMI/EMC

</details></td></tr>

<tr><td><details>
<summary><h2>🦿 Фаза 2: Биомеханика (февраль 2026 — февраль 2027) 🚀</h2></summary>

<i>Основное направление:</i>

&nbsp;&nbsp;⛝&nbsp;&nbsp;~~**🦿 Проект: Quadruped (MK1)** — четырёхногая платформа, базовая устойчивость~~ — отменён, заменён направлением Hexapod

- [ ] **🕷️ Проект: Hexapod (MK1)** — remote presence, управление 18 DOF, обратная кинематика

<i>Инфраструктура / вспомогательные проекты:</i>

- [x] [**⚡ Проект: Laboratory Power Supply Mk1**](https://github.com/suneids/PowerSupply)
- [x] **🧠 Проект: STM32 Register-Level HAL**
- [x] [**💡 Проект: Room Lighting System**](https://github.com/suneids/Light)
- [x] [**🌱 Проект: Micro-greenhouse / система автоматизации растений**](https://github.com/suneids/Greenhouse)
- [ ] [**🖥️ Проект: Gauntlet** — носимый Linux-инженерный терминал](https://github.com/suneids/Gauntlet)
- [ ] **〰️ Проект: Индуктивные датчики сгиба / натяжения**

</details></td></tr>

<tr><td><details>
<summary><h2>🤖 Фаза 3: Продвинутая робототехника (февраль 2027 — февраль 2028) ⏰</h2></summary>

<i>Фокус: сложные системы, эстетика, глубокая интеграция</i>

<i>Основное направление:</i>

- [ ] **🕷️ Проект: Octopod (MK3)** — многоногая роботизированная платформа с мощными приводами
- [ ] **🥽 Проект: The Mask** — носимая система сенсоров и обратной связи
- [ ] **🦾 Проект: The Third Arm** — манипулятор на плечевом креплении
- [ ] **🎨 Навык: Cyber-Aesthetics** — эргономичный механический дизайн
- [ ] **🟩 Навык: PCB Design** — переход от 2 к 4 слоям с учётом EMI/EMC

<i>Инфраструктура / исследования:</i>

- [ ] **🔬 Исследование: Собственные cable-driven датчики натяжения с интегрированными энкодерами**

</details></td></tr>

<tr><td><details>
<summary><h2>🧠 Фаза 4: Интеграция (2028 — 2029) ⏰</h2></summary>

<i>Фокус: Human-Machine Interface (HMI) и экзоскелеты</i>

- [ ] **🦾 Проект: Full Exoskeleton Movement System** — объединение управления перчаткой, IK и мощных приводов в носимой системе

</details></td></tr>

<tr><td><details>
<summary><h2>⚙️ Фаза 5: Эволюция (2029 — 2030) ⏰</h2></summary>

<i>Фокус: развитие и следующие поколения существующих систем</i>

- [ ] **🧤 Проект: Glove Mk.3**

</details></td></tr>
</table>

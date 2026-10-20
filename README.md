<!-- ANIMATED HEADER -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1E3A8A,100:38BDF8&height=160&section=header&text=From%20Feedback%20to%20Motion&fontSize=30&fontColor=FFFFFF&animation=twinkling&fontAlignY=35" alt="From feedback to motion" />
</p>

<h1 align="center">🛞 Differential Drive Robot</h1>

<h3 align="center">
  ESP32 · Sensor Fusion · Motion Control · Custom PCB
</h3>

<p align="center">
  <img width="100%" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1200&color=38BDF8&center=true&vCenter=true&width=900&height=55&lines=Sense+the+environment.;Combine+sensor+feedback.;Control+each+wheel.;Explore+straight%2C+square%2C+and+circular+paths." alt="Sense the environment. Combine sensor feedback. Control each wheel. Explore different paths." />
</p>

<p align="center">
  <b>Connecting embedded electronics, mechanical design, and feedback control.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Controller-ESP32-38BDF8?style=for-the-badge&logo=espressif&logoColor=white&labelColor=0D1117" alt="Controller: ESP32" />
  <img src="https://img.shields.io/badge/Control-PID_%2B_Non--PID-2563EB?style=for-the-badge&labelColor=0D1117" alt="PID and non-PID control" />
  <img src="https://img.shields.io/badge/Hardware-Custom_PCB-0EA5E9?style=for-the-badge&labelColor=0D1117" alt="Custom PCB" />
  <img src="https://img.shields.io/badge/Chassis-3D_Printed-0284C7?style=for-the-badge&labelColor=0D1117" alt="3D-printed chassis" />
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#robot-gallery">Gallery</a> ·
  <a href="#system-overview">System</a> ·
  <a href="#hardware-components">Hardware</a> ·
  <a href="#pin-connections">Connections</a> ·
  <a href="#motion-control">Motion Control</a> ·
  <a href="#code-and-project-files">Code</a> ·
  <a href="#ongoing-development">Development</a>
</p>

---

<h2 align="center">Overview</h2>

<p align="center">
  An <b>ESP32-based differential drive mobile robot</b> combining
  an <b>MPU6500 IMU</b>, a <b>VL53L0X Time-of-Flight sensor</b>,
  and <b>N20 encoder motors</b> for sensing, localization experiments,
  obstacle detection, and motion control.
</p>

<p align="center">
  The project explores <b>sensor fusion</b> and
  <b>PID/non-PID control</b> through straight-line,
  square, and circular path execution.
</p>

<p align="center">
  A <b>custom PCB</b> integrates the IMU, motor driver,
  and battery-charging circuitry.
  The mechanical assembly uses a <b>3D-printed chassis and wheels</b>.
</p>

<p align="center">
  <b>Mathematical modeling, GUI visualization, and CSV data workflows
  remain under development.</b>
</p>

<p align="center">
  <code>SENSE</code>
  &nbsp; → &nbsp;
  <code>ESTIMATE</code>
  &nbsp; → &nbsp;
  <code>CONTROL</code>
  &nbsp; → &nbsp;
  <code>MOVE</code>
  &nbsp; ↻
</p>

---

<h2 align="center">Project Highlights</h2>

<table align="center">
  <tr>
    <td width="50%" align="center" valign="top">
      <h3>🧭 Sensing &amp; Feedback</h3>
      <p>
        Combine IMU measurements, distance sensing,
        and wheel-encoder feedback to study robot motion.
      </p>
      <p>
        <code>MPU6500</code>
        <code>VL53L0X</code>
        <code>Encoders</code>
      </p>
    </td>
    <td width="50%" align="center" valign="top">
      <h3>🎯 Motion Control</h3>
      <p>
        Compare PID and non-PID approaches across
        straight-line, square, and circular trajectories.
      </p>
      <p>
        <code>PID</code>
        <code>Path Tracking</code>
        <code>Motor Control</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <h3>🔌 Custom Electronics</h3>
      <p>
        Bring the IMU, motor driver, and battery-charging
        circuitry together on a project-specific PCB.
      </p>
      <p>
        <code>PCB Design</code>
        <code>TB6612FNG</code>
        <code>Integration</code>
      </p>
    </td>
    <td width="50%" align="center" valign="top">
      <h3>🖨️ Mechanical Design</h3>
      <p>
        Build the robot around a 3D-printed chassis,
        with printable parts available in the repository.
      </p>
      <p>
        <code>3D Printing</code>
        <code>Chassis</code>
        <code>Motor Mounts</code>
      </p>
    </td>
  </tr>
</table>

---

<h2 align="center">Robot Gallery</h2>

<p align="center">
  <b>📸 From CAD and circuitry to a physical robot.</b>
</p>

<!-- Equal image heights keep the gallery aligned without stretching photos. -->
<div align="center">
  <table align="center">
    <tr>
      <th width="50%" align="center">🛞 Side / Top View</th>
      <th width="50%" align="center">🤖 Front View</th>
    </tr>
    <tr>
      <td width="50%" align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Side%20Top.jpeg">
          <img height="220" src="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Side%20Top.jpeg" alt="Differential drive robot viewed from the side and above" />
        </a>
      </td>
      <td width="50%" align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Front.jpeg">
          <img height="220" src="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Front.jpeg" alt="Front view of the differential drive robot" />
        </a>
      </td>
    </tr>
    <tr>
      <th width="50%" align="center">🔌 Back / Top View</th>
      <th width="50%" align="center">🖨️ Base View</th>
    </tr>
    <tr>
      <td width="50%" align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Back%20Top.jpeg">
          <img height="220" src="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Back%20Top.jpeg" alt="Differential drive robot viewed from the back and above" />
        </a>
      </td>
      <td width="50%" align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Base.jpeg">
          <img height="220" src="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/Robot%20Images/Robot%20Base.jpeg" alt="Base of the differential drive robot" />
        </a>
      </td>
    </tr>
  </table>
</div>

<p align="center">
  <sub>Click any photograph to view it at full size.</sub>
</p>

<p align="center">
  <a href="https://github.com/sdqxmd/Differential-Drive-Robot/tree/main/Robot%20Images">
    <b>Explore all robot images →</b>
  </a>
</p>

---

<h2 align="center">System Overview</h2>

<p align="center">
  <b>Sensor measurements inform the controller; encoder feedback closes the loop.</b>
</p>

<!-- Functional signal flow, not a power-wiring schematic. -->
```mermaid
flowchart TD
    PATH["Path command"]
    IMU["MPU6500 IMU"]
    TOF["VL53L0X ToF"]
    LINE["5-element line sensor array"]

    ESP["ESP32 sensing and motion control"]
    DRIVER["TB6612FNG motor driver"]
    MOTORS["Left and right N20 motors"]
    ENCODERS["Wheel encoder feedback"]
    SERIAL["USB serial monitoring"]

    PATH --> ESP
    IMU --> ESP
    TOF --> ESP
    LINE --> ESP

    ESP --> DRIVER
    DRIVER --> MOTORS
    MOTORS --> ENCODERS
    ENCODERS --> ESP

    ESP --> SERIAL

    classDef input fill:#102A43,stroke:#38BDF8,color:#FFFFFF;
    classDef control fill:#1E3A8A,stroke:#7DD3FC,color:#FFFFFF;
    classDef output fill:#0D1117,stroke:#0EA5E9,color:#FFFFFF;

    class PATH,IMU,TOF,LINE,ENCODERS input;
    class ESP control;
    class DRIVER,MOTORS,SERIAL output;
```

---

<h2 align="center">Hardware Components</h2>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Component</th>
        <th align="center">Role</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><b>ESP32 Dev Kit</b></td>
        <td align="center">Main controller for sensing and motion control</td>
      </tr>
      <tr>
        <td align="center"><b>MPU6500 IMU</b></td>
        <td align="center">Inertial measurements for motion and orientation estimation</td>
      </tr>
      <tr>
        <td align="center"><b>VL53L0X ToF Sensor</b></td>
        <td align="center">Distance measurement and obstacle sensing</td>
      </tr>
      <tr>
        <td align="center"><b>Two N20 DC Encoder Motors</b></td>
        <td align="center">Differential drive actuation and wheel feedback</td>
      </tr>
      <tr>
        <td align="center"><b>TB6612FNG Motor Driver</b></td>
        <td align="center">Independent control of the two motors</td>
      </tr>
      <tr>
        <td align="center"><b>5-Element Line Sensor Array</b></td>
        <td align="center">Line-sensor inputs for supported sketches</td>
      </tr>
      <tr>
        <td align="center"><b>12V Battery Pack</b></td>
        <td align="center">Robot power source</td>
      </tr>
      <tr>
        <td align="center"><b>Custom PCB</b></td>
        <td align="center">Integration of the IMU, motor driver, and charging circuitry</td>
      </tr>
      <tr>
        <td align="center"><b>3D-Printed Chassis and Wheels</b></td>
        <td align="center">Mechanical structure and mobility</td>
      </tr>
    </tbody>
  </table>
</div>

---

<h2 align="center">Pin Connections</h2>

<h3 align="center">⚙️ Motor Driver — TB6612FNG</h3>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Signal</th>
        <th align="center">Function</th>
        <th align="center">Documented ESP32 Wiring</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><code>PWMA</code></td>
        <td align="center">Left motor PWM</td>
        <td align="center"><code>GPIO 26</code></td>
      </tr>
      <tr>
        <td align="center"><code>AIN1</code></td>
        <td align="center">Left motor direction input 1</td>
        <td align="center"><code>GPIO 14</code></td>
      </tr>
      <tr>
        <td align="center"><code>AIN2</code></td>
        <td align="center">Left motor direction input 2</td>
        <td align="center"><code>GPIO 27</code></td>
      </tr>
      <tr>
        <td align="center"><code>PWMB</code></td>
        <td align="center">Right motor PWM</td>
        <td align="center"><code>GPIO 32</code></td>
      </tr>
      <tr>
        <td align="center"><code>BIN1</code></td>
        <td align="center">Right motor direction input 1</td>
        <td align="center"><code>GPIO 33</code></td>
      </tr>
      <tr>
        <td align="center"><code>BIN2</code></td>
        <td align="center">Right motor direction input 2</td>
        <td align="center"><code>GPIO 12</code></td>
      </tr>
      <tr>
        <td align="center"><code>STBY</code></td>
        <td align="center">Standby control</td>
        <td align="center"><code>GPIO 25</code></td>
      </tr>
    </tbody>
  </table>
</div>

> **Pin-mapping check:** The table preserves the project's supplied wiring notes. The current [`Full_Code.ino`](Robot%20Codes/Full_Code.ino) defines `AIN1 = 27` and `AIN2 = 14`, which reverses these two assignments. Confirm the actual PCB connections and make the selected sketch match before running the robot.

<h3 align="center">🔄 Encoder Connections</h3>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Encoder Signal</th>
        <th align="center">ESP32 Pin</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">Left Encoder A</td>
        <td align="center"><code>GPIO 34</code></td>
      </tr>
      <tr>
        <td align="center">Left Encoder B</td>
        <td align="center"><code>GPIO 35</code></td>
      </tr>
      <tr>
        <td align="center">Right Encoder A</td>
        <td align="center"><code>GPIO 39</code></td>
      </tr>
      <tr>
        <td align="center">Right Encoder B</td>
        <td align="center"><code>GPIO 36</code></td>
      </tr>
    </tbody>
  </table>
</div>

<h3 align="center">〰️ Line Sensors — 5-Element Array</h3>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Sensor</th>
        <th align="center">ESP32 Pin</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><code>LS1</code></td>
        <td align="center"><code>GPIO 4</code></td>
      </tr>
      <tr>
        <td align="center"><code>LS2</code></td>
        <td align="center"><code>GPIO 17</code></td>
      </tr>
      <tr>
        <td align="center"><code>LS3</code></td>
        <td align="center"><code>GPIO 16</code></td>
      </tr>
      <tr>
        <td align="center"><code>LS4</code></td>
        <td align="center"><code>GPIO 15</code></td>
      </tr>
      <tr>
        <td align="center"><code>LS5</code></td>
        <td align="center"><code>GPIO 13</code></td>
      </tr>
    </tbody>
  </table>
</div>

<h3 align="center">🧭 IMU and ToF — I²C Connections</h3>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Sensor Pin</th>
        <th align="center">MPU6500 → ESP32</th>
        <th align="center">VL53L0X → ESP32</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><code>VCC</code></td>
        <td align="center"><code>3.3V</code></td>
        <td align="center"><code>3.3V</code></td>
      </tr>
      <tr>
        <td align="center"><code>GND</code></td>
        <td align="center"><code>GND</code></td>
        <td align="center"><code>GND</code></td>
      </tr>
      <tr>
        <td align="center"><code>SDA</code></td>
        <td align="center"><code>GPIO 21</code></td>
        <td align="center"><code>GPIO 21</code></td>
      </tr>
      <tr>
        <td align="center"><code>SCL</code></td>
        <td align="center"><code>GPIO 22</code></td>
        <td align="center"><code>GPIO 22</code></td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">
  <sub>
    Both sensors share the I²C bus.
    The IMU is labeled MPU6500 here to match the hardware list
    and the repository's IMU_MPU_6500_RPY.ino sketch.
  </sub>
</p>

<h3 align="center">🔗 Serial Communication</h3>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Setting</th>
        <th align="center">Value</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">Baud rate</td>
        <td align="center"><code>115200</code></td>
      </tr>
      <tr>
        <td align="center">Interface</td>
        <td align="center"><code>USB</code></td>
      </tr>
    </tbody>
  </table>
</div>

---

<h2 align="center">Software and Libraries</h2>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Tool / Library</th>
        <th align="center">Use</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><b>Arduino IDE with ESP32 support</b></td>
        <td align="center">Build and upload the robot sketches</td>
      </tr>
      <tr>
        <td align="center"><code>Wire</code></td>
        <td align="center">I²C communication; supplied with the board support package</td>
      </tr>
      <tr>
        <td align="center"><code>Adafruit_VL53L0X</code></td>
        <td align="center">VL53L0X distance-sensor support</td>
      </tr>
      <tr>
        <td align="center"><code>Madgwick</code></td>
        <td align="center">Optional orientation-filter library for sketches that use it</td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">
  <sub>
    Install external libraries through the Arduino Library Manager.
    Check the selected sketch's include statements for its dependencies.
  </sub>
</p>

> **IMU implementation:** The current `IMU_MPU_6500_RPY.ino` sketch reads the IMU through `Wire` and uses complementary filtering for roll and pitch. It does not currently import the Madgwick library.

---

<h2 align="center">Motion Control</h2>

<p align="center">
  <b>Explore the effect of control strategy on robot motion.</b>
</p>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Trajectory</th>
        <th align="center">PID Version</th>
        <th align="center">Non-PID Version</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">📏 <b>Straight Line</b></td>
        <td align="center">
          <a href="Robot%20Codes/Straight_Line_with_PID.ino">View sketch</a>
        </td>
        <td align="center">
          <a href="Robot%20Codes/Straight_Line_without_PID.ino">View sketch</a>
        </td>
      </tr>
      <tr>
        <td align="center">🔲 <b>Square Path</b></td>
        <td align="center">
          <a href="Robot%20Codes/Square_Path_with_PID.ino">View sketch</a>
        </td>
        <td align="center">
          <a href="Robot%20Codes/Square_Path_without_PID.ino">View sketch</a>
        </td>
      </tr>
      <tr>
        <td align="center">⭕ <b>Circular Path</b></td>
        <td align="center">
          <a href="Robot%20Codes/Circle_Path_with_PID.ino">View sketch</a>
        </td>
        <td align="center">
          <a href="Robot%20Codes/Circle_Path_without_PID.ino">View sketch</a>
        </td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">
  <sub>
    Additional yaw-lock and calibration sketches are available
    in the Robot Codes folder.
  </sub>
</p>

---

<h2 align="center">Code and Project Files</h2>

<p align="center">
  Individual sensor sketches, combined system code,
  motion-control examples, and GUI source are included.
</p>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Folder</th>
        <th align="center">Contents</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">
          <a href="Robot%20Codes"><b>Robot Codes</b></a>
        </td>
        <td align="center">
          Sensor tests, calibration, combined firmware,
          path-control sketches, and GUI source
        </td>
      </tr>
      <tr>
        <td align="center">
          <a href="3D%20Prints"><b>3D Prints</b></a>
        </td>
        <td align="center">
          Printable robot base, front, top, and motor-clamp STL files
        </td>
      </tr>
      <tr>
        <td align="center">
          <a href="PCB%20Design"><b>PCB Design</b></a>
        </td>
        <td align="center">
          PCB design PDF and layout image
        </td>
      </tr>
      <tr>
        <td align="center">
          <a href="Robot%20Images"><b>Robot Images</b></a>
        </td>
        <td align="center">
          Photographs of the robot and its assembly
        </td>
      </tr>
    </tbody>
  </table>
</div>

<details>
<summary><b>📂 Quick links to individual sketches</b></summary>

<br />

| Purpose | File |
| :--- | :--- |
| Combined system firmware | [Full_Code.ino](Robot%20Codes/Full_Code.ino) |
| IMU roll, pitch, and yaw | [IMU_MPU_6500_RPY.ino](Robot%20Codes/IMU_MPU_6500_RPY.ino) |
| IMU calibration | [IMU_Calibration_0to360.ino](Robot%20Codes/IMU_Calibration_0to360.ino) |
| ToF sensor test | [TOF.ino](Robot%20Codes/TOF.ino) |
| Encoder distance, RPM, and speed | [Encoders_Distance_RPM_Speed.ino](Robot%20Codes/Encoders_Distance_RPM_Speed.ino) |
| Encoder and ToF calibration | [Encoder_TOF_Calibration.ino](Robot%20Codes/Encoder_TOF_Calibration.ino) |
| Line-sensor test | [Line_Sensor.ino](Robot%20Codes/Line_Sensor.ino) |
| GUI-side ESP32 firmware | [DDR_GUI.ino](Robot%20Codes/DDR_GUI.ino) |
| Python GUI | [DDR_GUI_PYTHON.py](Robot%20Codes/DDR_GUI_PYTHON.py) |

</details>

---

<h2 align="center">3D Printing and PCB Design</h2>

<table align="center">
  <tr>
    <td width="50%" align="center" valign="top">
      <h3>🖨️ Mechanical Files</h3>
      <p>
        STL files for the robot's structural parts
        and motor mounting.
      </p>
      <p>
        <a href="3D%20Prints/Robot_Base.stl">Base</a> ·
        <a href="3D%20Prints/Robot_Front.stl">Front</a> ·
        <a href="3D%20Prints/Robot_Top.stl">Top</a> ·
        <a href="3D%20Prints/Robot_Motors_Clamp.stl">Motor Clamp</a>
      </p>
      <p>
        <a href="3D%20Prints">
          <b>Explore printable parts →</b>
        </a>
      </p>
    </td>
    <td width="50%" align="center" valign="top">
      <h3>🔌 PCB Design</h3>
      <p>
        A custom board integrating the IMU,
        motor driver, and battery-charging circuitry.
      </p>
      <p>
        <code>Sensor Integration</code>
        <code>Motor Driver</code>
        <code>Charging Circuit</code>
      </p>
      <p>
        <a href="PCB%20Design">
          <b>Explore the PCB files →</b>
        </a>
      </p>
    </td>
  </tr>
</table>

<details>
<summary><b>🔍 View the PCB layout</b></summary>

<br />

<p align="center">
  <a href="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/PCB%20Design/Differrencial%20Drive%20Robot%20PCB%20Image.jpeg">
    <img height="300" src="https://raw.githubusercontent.com/sdqxmd/Differential-Drive-Robot/main/PCB%20Design/Differrencial%20Drive%20Robot%20PCB%20Image.jpeg" alt="Custom differential drive robot PCB layout" />
  </a>
</p>

<p align="center">
  <a href="PCB%20Design/Differencial%20Drive%20Robot%20PCB%20Design.pdf">
    <b>Open the PCB design PDF →</b>
  </a>
</p>

</details>

---

<h2 align="center">Ongoing Development</h2>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE_DEVELOPMENT-F59E0B?style=for-the-badge&labelColor=0D1117" alt="Active development" />
</p>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Workstream</th>
        <th align="center">Current Focus</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">📐 <b>Mathematical Modeling</b></td>
        <td align="center">
          Developing the mathematical model of the differential drive robot
        </td>
      </tr>
      <tr>
        <td align="center">🖥️ <b>GUI Visualization</b></td>
        <td align="center">
          Continuing development of the desktop visualization interface
        </td>
      </tr>
      <tr>
        <td align="center">📊 <b>CSV Data Workflows</b></td>
        <td align="center">
          Developing and refining GUI-based data handling and analysis
        </td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">
  <sub>
    GUI source is available in the repository.
    These tools remain under development.
  </sub>
</p>

---

<h2 align="center">Applications</h2>

<p align="center">
  🤖 <b>Autonomous Mobile Robot Experiments</b>
  &nbsp; · &nbsp;
  🧭 <b>SLAM and Localization Research</b>
</p>

<p align="center">
  🏁 <b>Robotics Competitions</b>
  &nbsp; · &nbsp;
  📡 <b>Smart Navigation Systems</b>
</p>

---

<h2 align="center">Learning Outcomes</h2>

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th align="center">Area</th>
        <th align="center">Skills Developed</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">🧭 <b>Sensing</b></td>
        <td align="center">Sensor fusion and IMU, ToF, and encoder integration</td>
      </tr>
      <tr>
        <td align="center">🔌 <b>Embedded Systems</b></td>
        <td align="center">ESP32 programming and hardware interfacing</td>
      </tr>
      <tr>
        <td align="center">🎯 <b>Control Engineering</b></td>
        <td align="center">PID tuning, motor control, and path tracking</td>
      </tr>
      <tr>
        <td align="center">⏱️ <b>Real-Time Programming</b></td>
        <td align="center">Sensor acquisition and responsive control loops</td>
      </tr>
      <tr>
        <td align="center">📐 <b>Modeling</b></td>
        <td align="center">Mathematical modeling of robot motion</td>
      </tr>
    </tbody>
  </table>
</div>

---

<h2 align="center">License</h2>

<p align="center">
  Shared for educational and research purposes.
</p>

---

<h2 align="center">Author</h2>

<p align="center">
  <b>Mohammad Sadique</b><br />
  Electrical Engineering · Jamia Millia Islamia, New Delhi
</p>

<p align="center">
  <a href="https://github.com/sdqxmd">
    <img src="https://img.shields.io/badge/GitHub-sdqxmd-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub: sdqxmd" />
  </a>
  <a href="https://www.linkedin.com/in/mdsdq/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" />
  </a>
  <a href="mailto:mohdsadique6970942@gmail.com">
    <img src="https://img.shields.io/badge/Email-0284C7?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <b>🛞 Build the platform. Understand the feedback. Refine the motion.</b>
</p>

<p align="center">
  <a href="#overview">Back to overview ↑</a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1E3A8A,100:38BDF8&height=110&section=footer" alt="Blue wave footer" />

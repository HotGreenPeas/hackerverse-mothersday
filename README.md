
<h1 align="center">Mechanized Box (Mother's Day Edition)</h3>

  <p align="center">
    When Mother's Day and Hackathons collide.
    <br />
    <a href="https://drive.google.com/file/d/1vNFWJrQq5Upu_HsZZiTqHqDMN9ORqA14/view?usp=sharing">View Demo</a>
    ·
    <a href="https://github.com/HotGreenPeas/hackerverse-mothersday/issues">Report Bug</a>
    ·
    <a href="https://github.com/HotGreenPeas/hackerverse-mothersday/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

What is there to say? This is a box that opens when someone comes near. Put the appropiate item inside for the appropiate occasion.

For Mother's Day...
<p align="center">
<img src="https://user-images.githubusercontent.com/43543240/167298277-dd9cdd34-32ce-45ad-9d3d-e9684dcd4d32.jpg" alt="drawing" width="300"/>
</p>

### Built With

* [Arduino](https://www.arduino.cc/)


<!-- GETTING STARTED -->
## Getting Started

You should always avoid powering servos with the Arduino board itself as they draw more current than the board can safely handle. In my case, I used a separate power board to supply 5V. You also avoid having to use capacitors and transistors. For the servos, they can share the same signal wire becuase they are suppose to be in sync.

<p align="center">
<img src="https://user-images.githubusercontent.com/43543240/167297058-f4dbc709-33d7-4bee-abfd-eefb4c83c455.png" alt="drawing" width="600"/>
</p>


### Prerequisites

- Have the necessary circuit components (servos, Arduino, USB cables, jumper wires, etc)
- Have an Arduino IDE installed.

### Installation

1. Download the code [here](https://raw.githubusercontent.com/HotGreenPeas/hackerverse-mothersday/main/Open_Box.ino)
2. Upload the code to the Arduino. Make sure to select the right board and COM port.


<!-- USAGE EXAMPLES -->
## Usage
Use this as a cool way to present an object; it's a box that unboxes itself; it's a gift that unwraps itself.


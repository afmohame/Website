+++
date = '2025-10-31T17:43:45+01:00'
draft = false
title = 'Arduino Uno R3'

+++
{{< rawhtml >}}
<!--<div> Whole page div-->
  <!--<div> table of contents div-->
<body>
    <h2>Table of contents</h2>
      <ol>
        <li><a href="#intro_to_arduino_uno_r3">Introduction to the Arduino Uno R3</a></li>
        <li><a href="#technical_specifications">Technical specifications</a></li>
          <ul type="none">
            <li><a href="#memory">2.1. Memory</a></li>
              <ul type="none">
                <li><a href="#flash">2.1. Flash memory</a></li>
                <li><a href="#sram">2.2. SRAM</a></li>
                <li><a href="#eeprom">2.3. EEPROM</a></li>
                <li><a href="#difference_eeprom_flash">2.4. Difference between EEPROM and Flash memory</a></li>
              </ul type="none">
            <li><a href="#peripherals">2.2. Peripherals</a></li>
                <ul type="none">
                  <li><a href="#digital_pins">2.2.1. Digital I/O pins</a></li>
                    <ul type="circle">
                      <li><a href="#pwm_pins">PWM pins</a></li>
                    </ul>
                  <li><a href="#comm_protocols">2.2.2. Communication protocols</a></li>
                    <ul type="circle">
                      <li><a href="#i2c">I2C</a></li>
                        <ul>
                          <li><a href="#i2c_workings">I2C the workings</a></li>
                        </ul>
                      <li><a href="#spi">SPI</a></li>
                      <li><a href="#uart_usart">UART/USART</a></li>
                    </ul>
                  <li><a href="#analog_comparator">2.2.3. Analog comparator</a></li>
                  <li><a href="adc">2.2.4. Analog to Digital Converter (ADC)</a></li>
                </ul>
          </ul>
          <li><a href="#arduino_ide">Arduino IDE</a></li>
      </ol>
<!--</div>-->
</body>


<h2 id="intro_to_arduino_uno_r3">1. Introduction to the Arduino Uno R3</h2>
<p>
The Arduino Uno R3 is a microcontroller development board designed by Arduino with which we can control various components. It is a small and compact microcontroller board that has 6 analog <b>input</b> pins, 14 digital <b>I/O</b> pins, 5V and 3.3V output pins, reset button and reset pin and more. In this article I will be discussing the ins and outs of the Arduino Uno R3 and its capabilities to document the features and serve as a reference for future projects. It is one of the most popular and widely used microcontroller boards for various reasons. It is beginner friendly, easy to use, has a big following and community support and lots of libraries. For these reasons, the Arduino Uno R3 is a must-have for beginners.
</p>

<h2 id="technical_specifications">2. Technical specifications</h2>
The Arduino Uno has the <b>ATMega328P</b> and the <b>ATMega16U2</b> microcontrollers which have a multitude of features that will be discussed further in this section. Both microcontrollers run on a 5V AVR 8-bit architecture. The <b>ATMega328P</b> clocks at up to 16 MHz. 

<h2 id="memory">2.1. Memory</h2>
The Arduino Uno R3 has 2 microcontrollers, namely:
<ul>
  <li>The <b>ATMega328P</b>: This is the main microcontroller and where you upload your code to. It has 32 kB of Flash, 2 kB SRAM and 1 kB EEPROM memory and is easily accessible.</li>
  <li>The <b>ATMega16U2</b> is where the firmware is stored and is used for USB-to-serial communication. It has 16 kB of Flash, 512 B SRAM and 512 B of EEPROM memory and is not easily accessible. We will focus on the <b>ATMega328P</b> characteristics.</li>
</ul>

<h3 id="flash">2.1.1. Flash memory</h3>


<h3 id="sram">2.1.2. SRAM</h3>


<h3 id="eeprom">2.1.3. EEPROM</h3>


<h3 id="difference_eeprom_flash"> 2.1.4. Difference between EEPROM and Flash memory </h3>


<h2 id="peripherals">2.2. Peripherals</h2>


<h3 id="digital_pins">2.2.1. Digital I/O pins</h3>


<h4 id="pwm_pins">PWM pins</h4>
<h3 id="comm_protocols">2.2.2. Communication protocols</h3>
<h4 id="i2c">I2C</h4>
<h5 id="i2c_workings">I2C the workings</h5>
<h4 id="spi">SPI</h4>
<h4 id="uart_usart">UART/USART</h4>
<h3 id="analog_comparator">Analog comparator</h3>
<h3 id="adc">Analog to Digital Converter (ADC)</h3>

<h2 id="arduino_ide">3. Arduino IDE</h2>

{{< /rawhtml >}}


who <b>is</b>

{{< rawhtml >}}
  <p class="speshal-fancy-custom">
    This is <strong>raw HTML</strong>, inside Markdown.
  </p>
  <img src="/arduino_pins.png">
  <!-- when in hugo, do not write the path as /static/image.png it does not work. Do it like above--->
{{< /rawhtml >}}

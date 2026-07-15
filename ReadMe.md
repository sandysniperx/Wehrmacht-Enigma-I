# Wehrmacht Enigma I Simulator

![Enigma Machine](Enigma.png)

A historically accurate Python implementation of the **Wehrmacht Enigma I** encryption machine.

This project recreates the internal mechanical and electrical operation of the Enigma I as faithfully as possible. Rather than simply reproducing the cipher, the simulator models the actual signal flow and mechanical behavior of the original electromechanical device, allowing encryption to occur exactly as it would on the historical machine.

---

## Features

* Complete simulation of the Wehrmacht Enigma I
* Historically accurate rotor wiring (I–VIII)
* Authentic Reflectors (UKW-B and UKW-C)
* Fully configurable plugboard (Steckerbrett)
* Configurable rotor order
* Adjustable Ring Settings (Ringstellung)
* Adjustable Rotor Positions (Grundstellung)
* Accurate rotor stepping mechanism
* Correct implementation of the historical **double-stepping anomaly**
* Bidirectional electrical current flow through the rotor stack
* Real-time encryption identical to the original machine when configured with identical settings
* Graphical user interface built with Tkinter

---

## Historical Accuracy

This simulator is designed to reproduce not only the output of the Enigma machine but also its internal operation.

The implementation models:

* Keyboard input
* Plugboard substitutions
* Rotor entry and exit wiring
* Ring setting offsets
* Rotor positional offsets
* Turnover notches
* Double-stepping behavior
* Reflector wiring
* Reverse electrical traversal through the rotor stack
* Lampboard output

Every key press follows the same sequence of mechanical and electrical events as the original Wehrmacht Enigma I.

---

## Project Goals

The objective of this project was to build an implementation that emphasizes **historical and engineering accuracy** over simplified encryption logic.

The simulator is intended as:

* An educational tool for studying the Enigma machine
* A reference implementation of the Enigma I mechanism
* A demonstration of classical electromechanical cryptography
* A faithful recreation of one of history's most influential cipher machines

---

## Technologies

* Python 3
* Tkinter

---

## Usage

1. Select the reflector.
2. Choose three rotors and arrange them in the desired order.
3. Configure the ring settings.
4. Set the initial rotor positions.
5. Configure the plugboard connections.
6. Type plaintext using the keyboard.
7. The encrypted text is produced exactly as on the original Enigma machine.

Using the same machine configuration, encrypting the ciphertext again reproduces the original plaintext, reflecting the reciprocal nature of the Enigma cipher.

---

## Disclaimer

This project is an educational recreation of the historical Wehrmacht Enigma I encryption machine. It is intended for the study of classical cryptography, electromechanical engineering, and the history of cryptographic systems.

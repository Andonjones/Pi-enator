# The Pi-nator

### An evolving portable Linux and network security experimentation platform

The Pi-nator began as my final project for a Security+ bootcamp with Utah State University. The original idea was simple: build a small, self-contained device that could run real network security tools and help me better understand how network reconnaissance and analysis work outside of a textbook.

Rather than simply running the tools from my laptop, I wanted to understand what it would take to package them into a portable platform. That turned into a much larger learning experience involving Linux, Raspberry Pi hardware, SSH, networking, display configuration, cooling, 3D printing, Nmap, Wireshark, and troubleshooting.

And thus, the Pi-enator was born.

> **Note:** Security testing documented in this project was performed only on networks and systems I owned or had explicit permission to test.

## Project Goals

- Build a portable Linux-based network security platform
- Gain hands-on experience with Linux and remote administration
- Perform authorized network reconnaissance and analysis
- Better understand the information exposed by devices and services on a network
- Learn how security tools work through practical use rather than theory alone
- Continue improving the platform as my skills and requirements evolve

## Mk1 — Raspberry Pi Prototype

**Status: Completed**

The first Pi-enator was built around a Raspberry Pi running Kali Linux.

A Waveshare TFT display was added to make the system self-contained, and the hardware was installed in a custom 3D-printed enclosure. The enclosure was modeled for the project and revised as hardware and cooling requirements became clearer.

I used SSH extensively during setup and configuration. This was one of my first projects where I independently relied on SSH to configure and troubleshoot another Linux system, and it became an important part of becoming more comfortable working remotely from the command line.

### Hardware

- Raspberry Pi
- Waveshare TFT display
- Custom 3D-printed enclosure
- Cooling hardware
- Bluetooth input/control devices

### Software & Tools

- Kali Linux
- SSH
- Nmap
- Wireshark
- Fusion 360
- OrcaSlicer

## Network Security Testing

The Mk1 was used to perform reconnaissance and network analysis in authorized environments, including my own network and a workplace network for which I received permission to perform testing.

The goal was not simply to "find a vulnerability," but to understand what information could be discovered from a network, how common reconnaissance tools presented that information, and how the results could be interpreted.

One useful outcome was discovering that testing does not necessarily produce dramatic vulnerabilities. Some of the techniques I experimented with produced limited results against the tested environments, which helped demonstrate the difference between running a security tool and actually interpreting what its results mean.

## Problems & Lessons Learned

### Display Compatibility

Finding a display that communicated properly with the Raspberry Pi proved more difficult than expected. Getting the Waveshare TFT working required additional configuration and troubleshooting.

### Cooling

Packaging a computer into a small enclosure introduced thermal considerations. I needed to develop a cooling solution that would allow the device to operate reliably for extended periods.

### Linux & SSH

The project forced me to become considerably more comfortable working with Linux remotely. What initially felt unfamiliar became one of the most useful skills I took away from the project.

### Security Testing Results

Some testing produced fewer useful findings than I initially expected. This became a useful lesson itself: running reconnaissance tools is only the beginning of an assessment, and a lack of obvious findings is still a result that needs to be understood.

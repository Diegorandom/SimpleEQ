# Audio Plugin Project with JUCE

Welcome to the **Audio Plugin** project built using **Modern C++** techniques and the **JUCE framework**. This project is based on the book _Modern C++ by Building an Audio Plugin_, where we delve into modern C++ concepts while developing a fully functional audio plugin.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Building the Project](#building-the-project)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a practical implementation of modern C++ features, focusing on audio development using the JUCE framework. The goal is to provide hands-on experience in writing high-performance, maintainable, and modular C++ code while creating an audio plugin that can be used in digital audio workstations (DAWs).

The key highlights of this project include:

- Use of Modern C++ (C++11 and later) features
- Integration with the **JUCE** framework for audio plugin development
- Real-world application with continuous improvement

## Features

- **Audio DSP**: Apply real-time digital signal processing to audio inputs.
- **Plugin Formats**: Supports VST3, AU, and AAX plugin formats for use in major DAWs.
- **Parameter Control**: Real-time parameter manipulation.
- **GUI**: Customizable user interface for plugin interaction.

## Requirements

To build and run this project, you will need:

- **JUCE Framework**: [JUCE](https://juce.com/) (version 6 or later)
- **C++ Compiler**: Modern C++ compiler (supporting C++14 or higher)
- **CMake**: Version 3.15 or later
- **IDE**: Any C++ IDE that supports CMake (e.g., CLion, Visual Studio, Xcode)

## Setup & Installation

1. **Clone the Repository**:
```bash
git clone https://github.com/yourusername/audioplugin-juce.git
cd audioplugin-juce
```

2. **Install JUCE**: 
Follow the instructions on the JUCE website to install the framework.

3. **Set Up CMake**: 
Configure CMake for your IDE

## Usage
Once built, you can load the plugin into a DAW supporting VST3, AU, or AAX formats. You can tweak the parameters in real-time and observe the effects on the processed audio.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
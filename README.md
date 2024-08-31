# Arabic Sign Language Recognition

A project focused on enhancing the recognition accuracy of Arabic sign language gestures using efficient machine learning models.

## Description

In the domain of Sign Language Recognition (SLR), different models have made significant progress in recent years. However, many models face challenges such as accurately capturing complex gestures, handling a wide range of classes, and meeting demanding computational requirements for real-time predictions, resulting in slow processing speeds.

This project demonstrates two approaches based on pose estimation of landmarks to effectively handle both word-level and character-level gestures. The primary objective is to achieve high recognition accuracy across a large dataset, particularly for complex signs, using efficient classifiers and less computational models, ensuring real-time performance.

The proposed models consist of:
- **Multi-layer Perceptron (MLP) classifier** for recognizing static signs, such as individual(static) characters.
- **Long Short-Term Memory (LSTM) network** for recognizing dynamic signs, such as complex(dynamic) gestures that involve motion.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/arabic-sign-language-recognition.git
   cd arabic-sign-language-recognition


# Rainfall Analysis Using Satellite Data

## Overview

This project investigates the influence of climate indices such as ENSO (El Niño Southern Oscillation), PDO (Pacific Decadal Oscillation), and DMI (Dipole Mode Index) on rainfall precipitation patterns in India and Indonesia. [cite: 13, 14] These regions are heavily reliant on seasonal rainfall for agriculture and water management. [cite: 408, 409, 410, 411, 412] The study uses 20 years of data (2003-2023) and various smoothing techniques to analyze regional precipitation trends and their correlation with climate indices. [cite: 13, 14]

## Key Findings

* ENSO has a consistent and significant impact on rainfall in both India and Indonesia, with a particularly strong relationship observed in Indonesia. [cite: 10, 11, 12, 15, 16, 17]
* PDO and DMI have less influence on rainfall patterns compared to ENSO. [cite: 15, 16, 17]
* Seasonal correlations with ENSO show that the SON (September, October, and November) season is particularly relevant for both regions. [cite: 18]
* SARIMAX models, incorporating external climatic indices, predict rainfall in Indonesia with superior accuracy, but simpler models work best for India. [cite: 19]

## Data

The primary dataset used in this study is the Integrated Multi-Satellite Retrievals for Global Precipitation Measurement (IMERG), provided by NASA. [cite: 65, 66, 67, 68, 69, 70, 71, 72, 73] Climate index data was gathered from the following sources:

* **ENSO 3.4:** National Weather Service (NOAA) [cite: 473, 474, 475]
* **DMI:** "Laboratory" online resource [cite: 478, 479]
* **PDO:** (for Environmental Information) [cite: 481, 482]

## Methods

The project employs various data analysis and statistical techniques, including:

* **Exploratory Data Analysis (EDA):** To understand underlying trends and seasonal variations in precipitation data. [cite: 487, 488, 489, 490, 491, 492, 493, 494, 495, 496, 52, 53, 54, 55, 56, 57, 58, 59]
* **Smoothing Techniques:** Kolmogorov-Zurbenko (KZ) filter, Triangle smoothing, Gaussian smoothing, and Moving Average, to reduce noise and highlight trends in precipitation anomalies. [cite: 443, 444, 445, 446, 447, 448, 549, 550, 551, 552, 553, 554, 60, 61, 62, 63, 64, 96, 97, 98, 99, 100, 101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 113, 114, 115, 116, 117, 118, 119, 120, 121, 122, 123, 124, 125, 126, 127, 13, 134, 135, 136, 137, 138, 139, 140, 141, 142, 143, 144, 145, 146, 147, 148, 149, 150, 151, 152, 153, 154, 155, 156, 157, 158, 159, 160, 161, 162, 163, 164, 165, 166, 167, 168, 169, 170, 171, 172, 173, 174, 175, 176, 177, 178, 179, 180, 181, 182, 183, 184, 185, 186, 187, 188, 189, 190, 191, 192, 193, 194, 195, 196]
* **Correlation Analysis:** To quantify the relationship between rainfall and climate indices. [cite: 443, 444, 445, 446, 447, 448, 534, 535, 536, 537, 538, 539]
* **Time Series Modeling:** SARIMAX models for annual rainfall prediction. [cite: 449, 450, 451, 452, 459, 460, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 252, 253, 254, 255, 256, 257, 258, 259, 260, 261, 262, 263, 264, 265, 266, 267, 268, 269, 270, 271, 272, 273, 274, 275, 276, 277, 278, 279, 280, 281]

## Code

* The primary programming language used in this project is Python.
* Key libraries used include \[mention libraries used, e.g., pandas, numpy, matplotlib, statsmodels].

## Setup

### Prerequisites

* Python 3.x
* \[List any specific Python packages required, e.g.,]
   * pandas
   * numpy
   * matplotlib
   * statsmodels
   * scikit-learn

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

* \[Provide instructions on how to run the code, any scripts to execute, and how to interpret the outputs.]
* For example: To run the analysis, execute the main python script:
    ```bash
     python main.py
    ```

## Contributing

\[If you want to encourage others to contribute, add guidelines here. Otherwise, you can remove this section.]

## License

\[Specify the license under which your project is released, e.g., MIT License]

## Acknowledgements

* Supervised by Dr. Stephen Griffiths [cite: 1]
* Data provided by NASA GES DISC, National Weather Service (NOAA), and others. [cite: 466, 467, 468, 469, 470, 471, 472, 473, 474, 475, 476, 477, 478, 479, 480, 481, 482, 483, 484, 485, 486]

---

This README provides a comprehensive overview of your project, covering the key aspects a reader would need to understand your work. Remember to replace the bracketed placeholders with the specific details of your project.

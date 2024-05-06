# Battery Modeling using Kalman Filter

This code demonstrates a simple example of linear battery modeling using a linear Kalman Filter. The battery model includes:
**State Transition Function**: Models the state of charge (SOC) of the battery over time, considering input factors that affect charge levels.
**Emission Function**: Provides a way to measure battery voltage, enabling the Kalman Filter to estimate the state of charge based on observed voltage measurements.

### Key Features
- **Battery SOC Estimation**: Predicts the state of charge accurately over a series of iterations using known system dynamics.
- **Voltage Measurement Analysis**: Uses a voltage measurement function to refine the SOC estimate.
- **Error Covariance Updates**: Continuously updates error covariance to improve subsequent predictions.

The linear Kalman Filter approach implemented here serves as a foundational example that can be further adapted or expanded to suit more sophisticated battery models.

## Prerequisites

Ensure you have the following installed:
- [Python](https://www.python.org/) (version 3.10 or later)
- [pip](https://pip.pypa.io/en/stable/installation/) (Python package installer)

## Installation

1. **Clone the Repository**  
   First, clone this repository to your local machine using:
   ```bash
   git clone https://github.com/your-username/st_kf.git

2. **Navigate to the Project Directory**
    Change to the project directory:
    ```bash
    cd st_kf

3. **Create a Virtual Environment (Recommended)**
    Set up a virtual environment to isolate dependencies. You can use pipenv:
    ```bash
    pip install pipenv
    pipenv shell

4. **Install Dependencies**
    With the virtual environment activated, install the packages listed in `requirements.txt`:
    ```bash
    pip install -r requirements.txt

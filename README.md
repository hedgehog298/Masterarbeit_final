# Design and Implementation of a Cybersecurity Management System in IIoT

## Project Description

A cybersecurity management system in industrial IIoT processes: The prototype successfully identifies vulnerabilities in devices and their software and proposes corresponding mitigations and defense measures. This information is presented to the user in a clear and structured manner in a mitigation tree for each identified vulnerability.

## Installation

Since the SMET project was included to map CVEs to ATT&CK techniques, the corresponding dependencies must be downloaded using the `requirements.txt` file. The project was developed using Python 3.8.19, but other versions should work as well.

### Steps for Installation:

1. **Create a virtual environment with Anaconda:**

   ```bash
   conda create -n myenv python=3.x
   conda activate myenv

   ```
2. **Install Jupyter Notebook in the Environment: Install Jupyter Notebook inside the virtual environment:**

    ```bash
    conda install jupyter
   ```

3. **Clone the Respository:**

4. **Install Requirements:**
    ```bash
    pip install -r requirements.txt
    python -m spacy download en_core_web_lg
   ```

## Usage
To use the prototype, no special steps are required. However, there may be occasional connection issues with the NVD database due to internet or API problems. In such cases, simply wait a short while and retry the query.

Once the vulnerabilities in the software and hardware have been successfully queried, they can be analyzed in detail.
When integrating the prototype, the paths to the respective local directory may need to be adjusted accordingly.

## Additional Info
The file ‘Master thesis 2.0.ipynb’ contains the code structure for the prototype created. The files ‘Devices.txt’ and ‘Zusatzinfos_Verteidigungsmaßnahmen_cleaned.txt’ represent two additional files and serve as input for the prototype. 
The SMET folder contains the files from the SMET repository, which was integrated into the prototype. 
All generated outputs of the prototype are located in "Diagramme". 

# Cloud Guard Scripts
This directory contains useful scripts for querying data from OCI CLoud Guard.

## All Detectors, Responders and Recommendations
The `recommendations.py` script gets all the configuration and activity detectors rules and writes them to the `all_detectors.csv`.  It also gets all the responder rules and writes them to `all_responders.csv`

### Installation 
1. Download the python script:
```wget https://raw.githubusercontent.com/Halimer/oci-scripts/master/cloud_guard/all_detectors_responders.py```
1. Create a virtual environment:
```python3 -m venv oci_scripts_venv```
1. Source the environment:
```source oci_scripts_venv/bin/activate```
1. Install the dependences:
```pip3 install oci```

### Running the script on a local machine
1. Source the environment:
```source oci_scripts_venv/bin/activate```
1. Run the script:
```python3 recommendations.py```

### Running the script in Cloud Shell
1. Source the environment:
```source oci_scripts_venv/bin/activate```
1. Run the script:
```python3 recommendations.py -dt```

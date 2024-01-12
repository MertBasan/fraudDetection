# Fraud Detection Project

## Overview

This project focuses on fraud detection within a corporate environment. By analyzing various data sources, including USB activity, file interactions, login data, and web activity, we aim to identify anomalous behavior that could indicate potential fraudulent activities.

## Project Structure

The project structure is organized as follows:

- **datasets/:** Contains CSV files with relevant data for analysis.
- **notebooks/:** Jupyter Notebooks for data exploration, analysis, and model development.
- **.gitattributes:** Configures Git LFS (Large File Storage) for tracking large files.
- **README.md:** Project documentation.

## Data Sources

1. **USB Activity:**
   - Tracking USB insertions and removals, particularly focusing on unusual patterns.

2. **File Interactions:**
   - Analyzing interactions with sensitive files, identifying anomalies in access patterns.

3. **Login Data:**
   - Studying login and logoff times to detect unusual login behavior.

4. **Web Activity:**
   - Investigating web activity, focusing on visits to specific websites.

5. **Email Data:**
   - Examining email interactions, identifying any unusual patterns or communications.

## Findings

### USB Activity

- Identified suspect (usr-yho) as the only director interacting with USB devices.
- Detailed analysis of USB insertion and removal times.

### File Interactions

- Detected usr-yho as the sole director accessing /docs/clients file, a potential security concern.
- Frequency analysis of interactions with sensitive files.

### Login Data

- Normal login and logoff times observed for the suspect, with no apparent anomalies.

### Web Activity

- Suspect (usr-yho) visited lawyers4u.com multiple times, possibly indicating awareness of an investigation.

### Email Data

- No anomalies found in email interactions; typical behavior observed.

## Conclusions

Based on the findings, usr-yho exhibits suspicious behavior, including accessing sensitive files and USB activities. Further investigation is recommended to prevent potential data breaches and ensure the security of corporate information.

Feel free to explore the notebooks for more detailed insights into the analysis and model development process.

## License

This project is licensed under the [MIT License](LICENSE).

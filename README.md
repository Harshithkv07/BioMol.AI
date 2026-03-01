# BioMol.AI - Protein Structure Predictor

BioMol.AI is a project that leverages the ESM-2 language model to predict protein structures from single sequences. The application provides an interactive web interface using Streamlit, allowing users to input protein sequences and visualize the predicted 3D structures in real-time.

Credit: This app is inspired by the Hugging Face ESMFold space and the work of Data Professor (Chanin Nantasenamat).

## Features

- **End-to-end Protein Structure Prediction**: Utilizes the powerful ESMFold API.
- **Interactive 3D Visualization**: Renders predicted protein structures using `py3Dmol` and `stmol`.
- **Confidence Estimation (pLDDT)**: Provides a per-residue estimate of prediction confidence.
- **PDB Download**: Allows users to download the predicted `.pdb` file for further analysis.

## Project Files

- `Biology python code.py`: The main Streamlit application script.
- `BIOLOGY_CODE_GROUP_14_AID_B.html`: HTML version of the group project code/notebook.
- `BIOLOGY_PPT_GROUP_14_AID_B.pdf`: Project presentation slides (Group 14, AID_B).
- `BIOLOGY_REPORT_GROUP_14_AID_B.pdf`: Detailed project report (Group 14, AID_B).

## Prerequisites

To run the application locally, you'll need the following Python packages:

- `streamlit`
- `stmol`
- `py3Dmol`
- `requests`
- `biotite`

You can install them using pip:

```bash
pip install streamlit stmol py3Dmol requests biotite
```

## How to Run

1. Navigate to the project directory:
   ```bash
   cd BioMol.AI
   ```

2. Run the Streamlit application:
   ```bash
   streamlit run "Biology python code.py"
   ```

3. Open the provided local URL in your web browser.
4. Enter your protein sequence in the sidebar and click "Predict".

## Acknowledgements

- ESMFold by Meta AI (ESM-2 language model).
- Streamlit, py3Dmol, and stmol for the interactive web framework and molecular visualization capabilities.

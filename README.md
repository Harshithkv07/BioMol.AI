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
- `BIOLOGY_CODE_GROUP_14_AID_B.html`: Pre-computed HTML project notebook (use this to test/view the project without installation).
- `BIOLOGY_PPT_GROUP_14_AID_B.pdf`: Project presentation slides (Group 14, AID_B).

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

## Testing Without Installation

If you prefer not to install the Python dependencies and just want to review and test the project results, you can use the pre-computed HTML notebook:
1. Locate the `BIOLOGY_CODE_GROUP_14_AID_B.html` file in the project folder.
2. Double click the file or right-click to open it in any modern web browser (Chrome, Firefox, Edge, etc.).
3. You will be able to review all the code blocks, the execution outputs, and the generated analytical visualizations statically.

## How to Run Locally (Streamlit App)

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

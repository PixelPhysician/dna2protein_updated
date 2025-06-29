# DNA to Protein Converter

## Description
This project provides a Python-based Jupyter Notebook for converting DNA sequences into protein sequences. The tool simulates the biological processes of transcription (DNA to RNA) and translation (RNA to protein) using `Biopython`.
It includes a simple class-based design with utility and storage components.

---

## Features
- Transcribe DNA to RNA using the central dogma.
- Translate RNA to protein sequence.
- Save and retrieve sequences with a singleton-based sequence storage class.
- Object-oriented, modular structure for easy extension.

---

## File Structure
```
dna2protein_updated/
│
├── dna_to_protein.ipynb       # Main notebook with full code and examples
├── README.md                  # Project documentation
```

---

## Requirements
- Python 3.8+
- Biopython

Install dependencies using pip:

```bash
pip install biopython
```

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/PixelPhysician/dna2protein_updated.git
   cd dna2protein_updated
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook dna_to_protein.ipynb
   ```

3. Follow the steps in the notebook to:
   - Generate random DNA sequences
   - Transcribe them to RNA
   - Translate them into protein sequences

---

## Example Output

```python
DNA: ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG
RNA: AUGGCCAUUGUAAUGGGCCGCUGAAAGGGUGCCCGAUAG
Protein: MAIVMGR*KGAR*
```

---

## Error Handling
Basic input validation is implemented. Ensure DNA sequences only contain A, T, C, and G.

---

by Sarah Deckarm, 2025

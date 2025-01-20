# Align It Right: Needleman-Wunsch in Python 🧬✨
![Screenshot 2025-01-20 232242](https://github.com/user-attachments/assets/da03cf06-1214-47d3-8145-abec2760829b)

This repository contains a Python implementation of the Needleman-Wunsch algorithm for sequence alignment. The algorithm is widely used in bioinformatics to align nucleotide, protein, or other biological sequences optimally. 

## 🚀 Features
- **Customizable Scoring**: Set your own match, mismatch, and gap scores.
- **Detailed Traceback**: Trace the optimal alignment path with directional markers (`↖`, `↑`, `←`).
- **Matrix Visualization**: Display the scoring and traceback matrices with sequence labels.

## 🛠️ How It Works
The Needleman-Wunsch algorithm:
1. Creates a scoring matrix based on sequence alignment rules.
2. Tracks alignment directions using a traceback matrix.
3. Backtracks to build the optimal alignment of two sequences.

## 📄 Usage

### Input
- Two sequences to align.
- Scores for match, mismatch, and gap.

### Output
- The optimal alignment score.
- Aligned sequences.
- Visualization of the scoring matrix with traceback directions.

### Example
```bash
Enter the first sequence: GATTACA
Enter the second sequence: GCATGCU
Enter the match score: 1
Enter the mismatch score: -1
Enter the gap score: -2

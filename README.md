A Cross-Paradigm Approach to Peptide Binding Prediction (Group 8: Entangled-Neurons)

This project endeavors to compare classical and quantum machine learning approaches in the context of immunological research by predicting peptide sequences' binding affinity to Major Histocompatibility Complex (MHC) class I molecules. Utilizing a straightforward implementation of a Multi-Layer Perceptron (MLP) alongside a Variational Quantum Classifier (VQC) within the Qiskit framework, the study aims to provide insights into the respective capabilities of classical and quantum computing in addressing this complex biological task. Although the models are not state-of-the-art, their simplicity facilitates a direct comparison, highlighting the potential advantages and limitations of each approach. By encoding peptide-MHC binding affinities as IC50 values and employing the BLOSUM62 matrix for nuanced amino acid substitution scoring, the project navigates the challenges posed by the immune system's complexity and peptide diversity. This work stands at the intersection of computational biology, machine learning, and immunology, offering a unique perspective on the potential of integrating quantum computing into biomedical research.

The demo jupyter notebook encompasses both the MLP and VQC implementations.

Classic Peptides classification was developed based on the: https://dmnfarrell.github.io/bioinformatics/mhclearning, and was studied in more details in ClassicPeptidesClassification.py.


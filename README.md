# STE-Nexus-services
<br>
| Model                  | Base Architecture     | Trained On         | Applications                              |
| ---------------------- | --------------------- | ------------------ | ----------------------------------------- |
| **ProtBERT**           | BERT                  | UniRef100          | Embeddings, structure/function prediction |
| **ProtT5**             | T5                    | UniRef50           | Sequence generation, classification       |
| **ESM (ESM-1b, ESM2)** | Transformer           | UniRef50, UniRef90 | Zero-shot predictions, embeddings         |
| **TAPE**               | Transformer, LSTM     | Pfam, UniProt      | Benchmarks for classification tasks       |
| **AlphaFold 2**        | Custom Transformer    | PDB + MSA          | Structure prediction                      |
| **ESMFold**            | Efficient Transformer | UniRef50           | Fast structure prediction                 |

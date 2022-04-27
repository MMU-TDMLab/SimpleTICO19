# Simple TICO-19 Dataset

Each simplification instance the dataset contains the following fields:

- **stringID:** sentence ID in the TICO-19 benchmark.
- **original:** original sentence from the TICO-19 benchmark.
- **simplification:** manual simplification.
- **addition:** automatic binary label indicating if *addition* was performed.
- **compression:** automatic binary label indicating if *compression* was performed.
- **paraphrasing:** automatic binary label indicating if *lexical paraphrasing* was performed.
- **splitting:** automatic binary label indicating if *sentence splitting* was performed
- **none:** automatic binary label indicating if *no simplification* was performed (i.e. original and simplification are the same).
- **unidentified:** automatic binary label indicating if the operation performed could no be identified automatically.

Identification of simplification operations was performed automatically using the annotation algorithms available in [EASSE](https://github.com/feralvam/easse).


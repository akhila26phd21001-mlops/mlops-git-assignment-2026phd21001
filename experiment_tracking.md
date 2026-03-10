| Experiment ID | Model Type     | Hyperparameters | Preprocessing Steps                                   | Feature Selection | Train/Test Split | Precision | AUC Score |
|---------------|---------------|-----------------|-------------------------------------------------------|------------------|-----------------|-----------|-----------|
| EXP-01        | Decision Tree | Default         | Removed rows of null values, Label Encoding          | All features     | 80/20           | 0.9803921568627452 | 0.9889188379754418 |
| EXP-02        | Decision Tree | max_depth = 3   | Removed rows of null values, Label Encoding          | All features     | 80/20           | 0.9336917562724015 | 0.9962716675570449 |
| EXP-03        | Decision Tree | Default         | Removed rows of null values, Label Encoding         | All features     | 70/30           | 0.9477427334570191 | 0.9710592385102189 |
| EXP-04        | Decision Tree | max_depth = 3   | Removed rows of null values, Label Encoding         | All features     | 70/30           | 0.9549206349206348 | 0.9924167444755682 |

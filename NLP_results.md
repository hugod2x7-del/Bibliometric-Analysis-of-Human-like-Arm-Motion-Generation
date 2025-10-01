Table 1: SUMMARY FROM THE MANUAL ANALYSIS OF THE SAMPLE ARTICLE COLLECTION

| Category                  | Subcategory                     | Frequency |
|---------------------------|--------------------------------|-----------|
| Input space               | Global planning                | 9         |
|                           | Local planning                 | 9         |
|                           | Inconclusive                   | 2         |
| Physical nature           | Kinematic*                     | 10 (-1)   |
|                           | Dynamic                        | 6         |
|                           | Inconclusive                   | 2         |
| Generation space          | Joint space                     | 7         |
|                           | Operational space               | 9         |
|                           | Inconclusive                   | 3         |
| Obstacle avoidance        | Present                        | 2         |
|                           | Not present                     | 16        |
| Testing platform          | Simulation only                 | 4         |
|                           | Humanoid robot                  | 3         |
|                           | Robotic arm                     | 10        |
|                           | Inconclusive                   | 1         |
| Human-likeness principles | Biomimetic                     | 4         |
|                           | Uni-modal bell-shaped velocity  | 5         |
|                           | Quasi-straight hand path        | 1         |
|                           | Qualitative assessment          | 3         |
|                           | Repeatability                   | 1         |
|                           | Trajectory smoothness           | 3         |
|                           | Two thirds power law            | 0         |
|                           | Handpath planarity              | 0         |
|                           | Spatiotemporal correspondence   | 1         |
|                           | RULA (rapid upper limb assessment)| 0       |
| AI                        | Deep learning                  | 1         |


Tabela 2: RoBERTa-large-MNLI First Test
| Topic              | TP | FP | FN | TN | F1-score | Accuracy |
|-------------------|----|----|----|----|----------|----------|
| Input space        | 0  | 2  | 16 | 16 | 0.000    | 0.059    |
| Physical nature    | 0  | 3  | 15 | 15 | 0.000    | 0.091    |
| Generation space   | 0  | 4  | 14 | 14 | 0.000    | 0.125    |
| Obstacle avoidance | 16 | 0  | 2  | 2  | 0.889    | 0.800    |
| Human-likeness     | 0  | 0  | 0  | 0  | 0.000    | 0.000    |
| AI                 | 16 | 0  | 2  | 2  | 0.889    | 0.800    |
| Test Platform      | 8  | 10 | 0  | 0  | 0.611    | 0.444    |


Tabela 3: RoBERTa-large-MNLI Performance
| Topic              | TP | FP | FN | TN | F1-score | Accuracy |
|-------------------|----|----|----|----|----------|----------|
| Input space        | 10 | 8  | 0  | 0  | 0.714    | 0.556    |
| Physical nature    | 9  | 9  | 0  | 0  | 0.667    | 0.500    |
| Generation space   | 10 | 8  | 0  | 0  | 0.714    | 0.556    |
| Obstacle avoidance | 15 | 3  | 0  | 0  | 0.909    | 0.833    |
| Human-likeness     | 14 | 34 | 11 | 80 | 0.384    | 0.676    |
| AI                 | 17 | 1  | 0  | 0  | 0.971    | 0.944    |
| Test Platform      | 12 | 6  | 0  | 0  | 0.800    | 0.667    |


Tabela 4: SciBERT Performance
| Topic              | TP | FP | FN | TN | F1-score | Accuracy |
|-------------------|----|----|----|----|----------|----------|
| Input space        | 10 | 8  | 0  | 0  | 0.714    | 0.556    |
| Physical nature    | 12 | 6  | 0  | 0  | 0.800    | 0.667    |
| Generation space   | 9  | 9  | 0  | 0  | 0.667    | 0.500    |
| Obstacle avoidance | 2  | 16 | 0  | 0  | 0.200    | 0.111    |
| Human-likeness     | 8  | 25 | 17 | 89 | 0.276    | 0.698    |
| AI                 | 16 | 2  | 0  | 0  | 0.941    | 0.889    |
| Test Platform      | 7  | 11 | 0  | 0  | 0.560    | 0.389    |



|                           | Reinforcement learning          | 0         |
|                           | Learning by demonstration       | 1         |

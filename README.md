# Can LLM Agents Generate Real-World Evidence? Evaluating Observational Studies in Medical Databases

## **Abstract**
Observational studies can yield clinically actionable evidence at scale, but executing them on real-world databases is open-ended and requires coherent decisions across cohort construction, analysis, and reporting. Prior evaluations of LLM agents emphasize isolated steps or single answers, missing the integrity and internal structure of the resulting evidence bundle. To address this gap, we introduce RWE-bench, a benchmark grounded in MIMIC-IV and derived from peer-reviewed observational studies. Each task provides the corresponding study protocol as the reference standard, requiring agents to execute experiments in a real database and iteratively generate tree-structured evidence bundles. We evaluate six LLMs (three open-source, three closed-source) under three agent scaffolds using both question-level correctness and end-to-end task metrics. Across 162 tasks, task success is low: the best agent reaches 39.9%, and the best open-source model reaches 30.4%. Agent scaffolds also matter substantially, causing over 30% variation in performance metrics. Furthermore, we implement an automated cohort evaluation method to rapidly localize errors and identify agent failure modes. Overall, the results highlight persistent limitations in agents' ability to produce end-to-end evidence bundles, and efficient validation remains an important direction for future work.

> Code will be released upon acceptance of the manuscript.

> Open to discussions and collaborations in RWE, AI4Science, and AI4Med — feel free to reach out!

# Citation

```
@misc{li2026llmagentsgeneraterealworld,
      title={Can LLM Agents Generate Real-World Evidence? Evaluating Observational Studies in Medical Databases}, 
      author={Dubai Li and Yuxiang He and Yan Hu and Yu Tian and Jingsong Li},
      year={2026},
      eprint={2603.22767},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2603.22767}, 
}
```

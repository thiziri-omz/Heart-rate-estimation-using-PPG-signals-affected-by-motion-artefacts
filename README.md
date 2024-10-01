# Heart-rate-estimation-using-PPG-signals-affected-by-motion-artefacts
Heart rate (HR) monitoring using wrist-worn devices, which integrate photoplethysmography (PPG) sensors, continues to gain popularity due to its low cost and convenience. However, the presence of motion artifacts (MA) in PPG signals complicates HR estimation. In this project, my teammate and I implemented and conducted various experiments on three methods proposed in the literature to address this problem: JOint Sparse Spectrum reconstruction **(JOSS)**, Wiener Filtering Phase Vocoder **(WFPV)**, and **Q-PPG**. WFPV and JOSS rely on classical signal processing approaches, while Q-PPG leverages a deep learning approach. We used three databases for the evaluation: IEEE SPC 2015 train, IEEE SPC 2015 test, and DaLiA.

**Results:** The JOSS and WFPV methods, which performed well on activities involving moderate MA, proved ineffective for activities with more complex MA. Moreover, JOSS demonstrated low generalization capability due to its reliance on numerous heuristic parameters and thresholds. On the other hand, the Q-PPG method showed flexibility in automatically optimizing deep learning models for HR estimation, with the potential to be deployed on resource-limited hardware. However, its effectiveness is still constrained by the availability of sufficiently large and diverse datasets.

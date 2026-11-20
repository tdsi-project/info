# Image & Signal Processing: Group Project

**Groups:** 2–3 students

**Topic choice:** 9 October 2026

**Pitch:** 27 November 2026, at 2pm

**Final evaluation:** 29 January 2027

**Dedicated sessions:** 20 × 2 h, plus personal work

---

## 1. Goals

You will take a real image or signal processing problem from a list of topics and work on it like a small research project: understand the problem, implement a baseline, propose and test an improvement, and communicate honestly what worked and what did not. A well-analysed negative result is better than an unexplained good number.

## 2. Deliverables and calendar

| When | Deliverable | Format |
|---|---|---|
| Intermediate | Pitch | 5 min + questions, up to 3 slides |
| Intermediate | Report | 2 pages: problem, related work, planned method, baseline results |
| Final | GitHub repository | Code, README, environment file, demo notebook (see [project template](https://github.com/tdsi-project/project-template)) |
| Final | Report | 4 pages, extending the intermediate report (not a new document) |
| Final | Report appendix | Use of AI tools + CO₂ and energy footprint |
| Final | Presentation + live demo | 15 min + 10 min individual questions |

**Repository requirements**
- `README.md`: problem, method, how to run, main results, group members.
- `requirements.txt` or `environment.yml`, with pinned versions for key libraries.
- A demo notebook that runs end to end in **10 minutes** on a free Google Colab runtime (or equivalent). Provide intermediate results (e.g., preprocessed data) and network parameters if needed.
- Use branches or pull requests, and commit regularly throughout the project rather than uploading everything at the end. Each member must have visible commits.
- Include a `data/README` explaining how to obtain the dataset. 
- Do not commit large data files. Consider adding a `.gitignore` file to your project to avoid doing so. Remember that removing a large file that was added by mistake does not remove it from the history (see `.git` folder).

## 3. Mandatory scientific content

1. **Establish a baseline first** using an existing DL-based or classical method (e.g., filtering, wavelets, Fourier/spectral methods, or optimisation-based methods).
2. **Quantitative evaluation** with metrics appropriate to the task, on a held-out test set.
3. **At least one ablation or sensitivity study** (a parameter, a component, a noise level, etc.).
4. **Error analysis**: show and discuss failure cases.
5. **Fair comparison**: same data, same metrics, and comparable tuning effort for all methods.

## 4. Use of AI tools

AI assistants (code or text) are **allowed** under these conditions:
- You must **disclose** your use in the individual statement: which tools, for which tasks, and what you verified or modified.
- You are responsible for everything you submit. Any student must be able to explain any line of code or any equation in the project, during the final questions.
- Do not present AI-generated text as your own analysis. The discussion of results must reflect what you actually observed.
- Cite external code, papers, and datasets.

Undisclosed use, or inability to explain submitted work, is handled as a lack of mastery of the project in the individual grade, and as academic misconduct if there is evidence of concealment.

## 5. Compute and environmental frugality

- Available resources: workstations in the GE Department, Google Colab, and Kaggle Notebooks.
- Consider using small or downscaled datasets, early stopping, fixed seeds, and cached results. Avoid running long training phases, in particular at the beginning of the project.
- **Report your footprint** in an appendix to the final report: hardware, total runtime, estimated energy use and CO₂ emissions (for example, using CodeCarbon or ecologits for LLM API usage), and the steps you took to reduce it. Estimates are approximate, which is acceptable; state their limitations (for instance, water use depends on the data centre and is not measured by these tools).
- You are not penalised for needing more compute, only for not measuring or not justifying it.

## 6. Pitch guidelines

The pitch is a short checkpoint to make sure you understand the goal of your project and have identified the first steps to reach it. We expect a clear plan, not a finished method.

**Format**
- **5 minutes**, strictly timed, followed by questions.
- **Up to 3 slides** (PDF). Send the PDF by email, by 27 November at 12:00.
- Any group member may present, but **every member must be able to answer questions**.

**What your slides and talk must cover**
1. **Problem:** what is the input, what is the expected output, and why is it hard? Show one example (image or signal).
2. **Data:** which dataset, its size, and how you split it into train/validation/test.
3. **Baseline:** which existing method you will use as a reference, and where the code comes from (library, paper repository, your own implementation).
4. **Evaluation:** which metrics you will use, and why they suit the task.
5. **Planned improvement:** what you intend to try beyond the baseline, and what you expect it to change.

**What we look for**
- The problem is clearly stated.
- Respect timing. You will be stopped at 5 minutes.
- The baseline and metrics are concrete (named method, named dataset, named metric).
- Answers to questions show that every member understands the project.

## 7. Live demo protocol

During the final session, you will run your notebook and may be asked to change a parameter and explain its effect. Prepare by testing your notebook in a clean environment beforehand.

**Crash test:** The instructor may provide a new image or signal for you to process.

## 8. Practical rules

- Group problems (conflict, absence) may occur: contact the instructor early, not at the end.
- Late submissions will be penalised.
- Plagiarism and unreferenced reuse of code or text will be penalised.

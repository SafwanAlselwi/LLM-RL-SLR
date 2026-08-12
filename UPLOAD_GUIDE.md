# Beginner Upload Guide

This package is prepared for the existing repository:

`https://github.com/SafwanAlselwi/LLM-RL-SLR`

## Before you upload

1. Download and unzip the package.
2. Open the unzipped `LLM-RL-SLR-GitHub` folder.
3. You should see `README.md`, `CITATION.cff`, `paper.pdf`, `docs/`, `figures/`, `data/`, `codebook/`, and `scripts/`.
4. Do **not** upload the outer `LLM-RL-SLR-GitHub` folder as one extra directory. Upload its **contents** into the repository root.

## Upload the package using the GitHub website

1. Go to the repository main page.
2. Click **Add file** → **Upload files**.
3. Drag the contents of this package into the upload area.
4. GitHub will recognize the folder structure.
5. Use this commit message:

   `Build full paper repository and project website`

6. Commit the changes to `main` if you are allowed to do so. If GitHub requires a branch/pull request, follow the prompt and create the pull request.

The new `README.md` is intended to replace the current two-line README.

## Publish the project website with GitHub Pages

After the files are committed:

1. Open the repository.
2. Click **Settings**.
3. In the left sidebar, under **Code and automation**, click **Pages**.
4. Under **Build and deployment**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/docs`
5. Click **Save**.

The expected default project URL is:

`https://safwanalselwi.github.io/LLM-RL-SLR/`

If you cannot see or change the Pages settings, ask the repository owner/administrator to perform this step.

## Repository description

Use:

`Reinforcement Learning for Large Language Models: a comprehensive survey from alignment to agentic decision-making.`

## Suggested repository topics

Add these under **About → Topics**:

- `reinforcement-learning`
- `large-language-models`
- `rlhf`
- `dpo`
- `grpo`
- `reward-modeling`
- `llm-agents`
- `ai-safety`
- `alignment`
- `reasoning`
- `survey`
- `reproducibility`

## Files that still need the real study data/code

The package intentionally does not invent the manuscript's data or analysis scripts. When the validated files are available, upload them at these exact paths:

- `data/evidence_table.csv`
- `data/failure_mitigation_instances.csv`
- `data/rlllm_report_scoring_matrix.csv`
- `codebook/codebook.md`
- `scripts/generate_scoring_matrix.py`
- `scripts/reproduce_tables.py`

After those files are uploaded, update the website's "Pending source file" labels if desired.

## After journal publication

Update:

1. `README.md` — final journal citation, DOI, paper link.
2. `CITATION.cff` — DOI, journal name, volume/issue/pages, publication date.
3. `docs/index.html` — citation block and paper/publication buttons.
4. Replace `docs/assets/paper.pdf` and root `paper.pdf` with the final public version if your publishing agreement allows repository hosting.
5. Create a GitHub release such as `v1.0.0`.

## License

The package deliberately does not choose an open-source/open-data license on behalf of the author team. The included `LICENSE` is a conservative all-rights-reserved notice until the authors decide whether code, data, figures, and documentation should use one or more explicit licenses.

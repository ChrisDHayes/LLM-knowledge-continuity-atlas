# Knowledge Continuity Atlas

**What survives when the AI model changes?**

An interactive, browser-based learning experience by **Christopher Hayes, CDAIO** exploring how organisations preserve, question and reuse the evidence behind AI-assisted decisions.

> Continuity starts before migration. A handover cannot pass on knowledge that was never recorded. A complete record can still be wrong.

## Explore the live Atlas

[Open the interactive Knowledge Continuity Atlas](https://chrisdhayes.github.io/LLM-knowledge-continuity-atlas/)

Start with **Show me what can get lost**, or choose **Explore freely** to compare scenarios.

## Why I built this

Keeping an AI-generated answer is not the same as keeping the reasons for trusting it. The sources, assumptions, objections, tests and approval limits behind a recommendation can be fragmented, omitted or lost before a replacement AI ever arrives.

I built this Atlas to make that problem visible and practical: what should we capture, what can we transfer, what remains uncertain, and what must we check again?

The aim is not to suggest that every model change destroys knowledge. It is to help people distinguish preserving records from validating a decision, testing a replacement system and authorising its use.

## Questions it explores

- What did we never write down in the first place?
- What is confirmed missing, and what is simply unknown?
- Can a better handover repair weak capture?
- What can a replacement AI receive without necessarily understanding it?
- What if a saved assumption becomes outdated or was wrong from the start?
- Which evidence, system behaviours and permissions need fresh review?

## Start here

Download this repository and open **index.html** in a browser. No installation, API key, sign-in or build step is required for the exhibit.

Choose **Show me what can get lost**, then follow the five-step story:

1. **Inspect** the fictional records behind a service-team decision.
2. **Capture**: explore what the team actually saved.
3. **Predict** what a handover can preserve, then reveal the explanation.
4. **Compare** what reaches the replacement AI.
5. **Challenge** the decision and review your personalised takeaway.

Use **Explore freely** to access all controls without following the guided sequence.

## What is inside

- A flow diagram separating original work, capture, transfer and receipt.
- Three illustrative recording scenarios and three handover approaches.
- Inspectable fictional records with supporting evidence, suggested owners, limitations and review triggers.
- Individual capture overrides, including **confirmed not recorded** and **capture unknown**.
- A plain-language table showing the same states as the diagram.
- Previous-choice comparison and a pinned baseline.
- Two change events: reduced specialist capacity, or an original capacity assumption that was wrong.
- Contextual help on hover, keyboard focus or tap, plus ribbon previews.
- A personalised summary and downloadable or printable continuity checklist.
- Research lenses, a decision exercise, timeline, assurance matrix, design exercise and knowledge check.
- Light and dark themes, reflection-note export and a layout that adapts to smaller screens.

## Reading the example responsibly

The service-team story, record contents, owners, capture states, handover outcomes and change events are **fictional teaching examples**. They are not measured organisational rates, product comparisons or maturity ratings.

Equal ribbon widths do not represent probability, reliability or information volume. A record reaching the final column establishes availability only within the example, not correct retrieval, interpretation, validity or permission to act.

Published research is presented separately in the exhibit, with source links and interpretive limits. The proposed continuity framework is a synthesis for discussion, not an independently validated standard.

The checklist is a learning output, not an assurance assessment, compliance certification or approval. Suggested owners are illustrative roles, not an organisation's assigned decision rights.

## Interaction tips

- Hover or focus **?** for help; select it to keep help open. Escape dismisses it.
- Hover or focus a ribbon for a preview; select a ribbon or record button to inspect it.
- Use the **plain-language table** if following the ribbons is difficult.
- **Restart this example** clears story choices, comparison and responses while keeping separate reflection notes and the current theme during that page session.
- Export reflection notes before closing the page if you want to keep them.

## Technical approach

The exhibit is a single HTML file with embedded CSS and JavaScript. Its core interactions do not require external assets or live AI calls. Research links require internet access when opened.

This repository contains:

```text
index.html   Interactive exhibit, based on version 8
README.md    Project purpose, usage and boundaries
```

## Publish with GitHub Pages

After uploading these files to a repository:

1. Open the repository's **Settings**, then **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the branch containing these files, such as **main**, and the **/(root)** folder.
4. Select **Save** and use the published address shown by GitHub Pages.

Keep **index.html** at the root of the selected publishing folder.

Official guidance: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Research and further reading

The exhibit includes references to LongMemEval, Lost in the Middle, historical model-behaviour changes, explanation faithfulness, organisational memory, provenance and AI risk management. Consult the **Sources** section inside the exhibit for the linked references and the limits on each interpretation.

## Feedback

Suggestions are welcome, especially where a label is confusing, a scenario explanation does not match the selected choices, or an interaction is difficult to use. When reporting a problem, include the recording scenario, handover method, selected record, browser and expected behaviour. Do not include confidential or personal information.

## Author and status

**Christopher Hayes, CDAIO**

An independent educational prototype developed for discussion in Boston University's MSc in Artificial Intelligence community. It is not an official university product or endorsement.

No reuse licence has been selected for this package. A licence should be chosen separately by the author before presenting the project as openly licensed.

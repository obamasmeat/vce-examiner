# VCE Examiner – a Claude skill

A strict, VCAA-style examiner and VCE teacher for Claude. Paste a question and your answer (or a photo of it), and it:

- **marks it harshly**, the way a real VCAA assessor would, with a mark out of the allocation
- shows **exactly where each mark was won or lost**, quoting your own words
- explains **why** each mistake costs marks under VCE expectations, and how to fix it
- writes a **full-marks model answer**, with each mark labelled
- gives you **habits to carry into your next answer**

It works for single questions, full exams and SACs, and essays. It also has a "teach me" mode for questions you haven't answered yet.

> ⚠️ **Not affiliated with or endorsed by the Victorian Curriculum and Assessment Authority (VCAA).** Marks are estimates for practice only, not official results.

## Subjects covered (50)

English, EAL, English Language, Literature · Mathematical Methods, Specialist, General, Foundation · Biology, Chemistry, Physics, Psychology, Environmental Science, Agricultural & Horticultural Studies · Revolutions, Australian History, Ancient History · Legal Studies, Business Management, Economics, Accounting · Health & Human Development, Physical Education, Outdoor & Environmental Studies, Food Studies, Industry & Enterprise · Applied Computing (Data Analytics, Software Development), Algorithmics · Systems Engineering, Product Design & Technologies, Visual Communication Design · Media, Drama, Theatre Studies, Dance, Music (Inquiry, Composition, Contemporary Performance, Repertoire Performance), Art Creative Practice, Art Making & Exhibiting · Philosophy, Classical Studies, Sociology, Politics, Religion & Society, Texts & Traditions, Geography, Extended Investigation · plus one shared guide for all VCE languages.

Each subject guide summarises, in original wording, what VCAA's published exam specifications, assessment criteria and the two most recent examination reports (2024–2025) say assessors reward and penalise. VCE VET subjects aren't included.

---

## Install

### Option 1: Ask Claude to do it (Claude Code)
In Claude Code, paste:

```
Install the vce-examiner plugin from the GitHub marketplace ObamasMeat/vce-examiner
```

### Option 2: Two commands (Claude Code)
Run these inside Claude Code:

```
/plugin marketplace add ObamasMeat/vce-examiner
/plugin install vce-examiner@vce-tools
```

Restart Claude Code if it asks you to. To update later, run `/plugin marketplace update vce-tools`.

### Option 3: claude.ai (web, desktop or mobile app)
1. Download [`dist/vce-examiner.zip`](dist/vce-examiner.zip).
2. In Claude, go to **Settings → Capabilities**, make sure code execution is on, then upload the zip under **Skills**.

---

## How to use it

Just ask, for example:

- "Mark this Legal Studies 6-mark question." (Then paste the question, the marks and your answer.)
- "Here's a photo of my Chemistry SAC, what would I get?"
- "Mark my English text response essay on *The Memory Police*."
- "Teach me how to answer 'evaluate' questions in Business Management."

For the best results, include:
1. the **subject**
2. the **exact question and its mark allocation**, plus any stimulus, case study or data
3. your **response, word for word**, or a **clear, close-up photo** of it
4. the official marking guide, if you have one (it takes priority)

## Limitations

- These are estimates, not official marks. Study designs change, so check with your teacher.
- It can't watch or listen to performances (Drama, Dance, Music, language orals). It marks the written parts and plans only.
- It doesn't cover VCE VET subjects.

## Repo layout

```
.claude-plugin/marketplace.json          ← marketplace "vce-tools"
plugins/vce-examiner/
  .claude-plugin/plugin.json
  skills/vce-examiner/
    SKILL.md                             ← examiner persona and workflow
    references/command-terms.md
    references/subject-guides.md         ← subject index + common patterns
    references/subjects/*.md             ← 29 subject guides
dist/vce-examiner.zip                    ← for claude.ai upload
```

## License
MIT. VCE® is a registered trademark of the VCAA. This project is independent and contains no VCAA examination material. For official exams and reports, see [vcaa.vic.edu.au](https://www.vcaa.vic.edu.au/assessment/vce/examination-specifications-past-examinations-and-examination-reports/examination-specifications-past-examinations-and-external-assessment-reports).

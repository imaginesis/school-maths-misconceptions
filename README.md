# Typical student errors in school maths

935 codes of typical student errors (misconceptions) in school mathematics — "lost the carry", "added the
denominators", "used 360° instead of 180° for the angle sum of a triangle", "fencepost error" — each with the
short label a teacher reads on an answer key, in English, Polish, German, French, Spanish, Italian and Dutch,
and linked to the school maths skills where the error appears. Prepared by Imaginesis (https://imaginesis.com),
a maths word-problem worksheet generator whose multiple-choice tasks build every wrong option from one of these
errors, so the answer key can say which error a student probably made.

Snapshot: 2026-11-11. License: Creative Commons Attribution 4.0 (CC BY 4.0) — cite as
"Imaginesis typical student errors in school maths, 2026".

## Files

- `data/misconceptions.csv` — `code` (stable identifier), `label_en`, `label_pl`, `label_de`, `label_fr`,
  `label_es`, `label_it`, `label_nl` (teacher-facing labels as printed on Imaginesis answer keys),
  `n_templates` (task templates whose wrong options use the code), `n_skills` (distinct skills).
- `data/misconception_skills.csv` — `code`, `skill_slug` (the same identifiers as in the curriculum crosswalk,
  the prerequisite graph and the skill names dataset), `n_templates`.

## How it was made — and how far to trust it

- The codes were written by the authors of the Imaginesis task templates while designing multiple-choice
  distractors: a wrong option is not a random wrong number but the result of one specific error. Codes are
  shared between templates because an error belongs to the student's thinking, not to one task.
- Labels are the ones printed on answer keys. They are short by design (a few words), not definitions.
  The English labels are written by the authors; the other languages are translations used in production.
- `n_templates` counts templates in the Imaginesis repository at the snapshot date, including templates
  still in review; it shows where an error is modelled, not how often students make it. This is not a
  frequency study.
- 20 codes have no template yet (registered for templates in preparation); they have no rows in
  `misconception_skills.csv`.

Corrections and suggestions from teachers are very welcome as GitHub issues.

## Related datasets

Curriculum crosswalk (where each skill sits in 10 national curricula): https://doi.org/10.5281/zenodo.23217841.
Skill prerequisite graph: https://doi.org/10.5281/zenodo.23451451. Skill names in 7 languages: https://doi.org/10.5281/zenodo.23452239.

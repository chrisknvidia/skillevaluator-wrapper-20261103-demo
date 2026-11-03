# SkillEvaluator evaluation report

**Tier 1 scan result: FAILED**

1 skills · 0 passed · 1 failed · 0 incomplete

Errors: 2 · Warnings: 3

## Evaluation scope

Tier 1: executed for 1/1 skills with validator evidence; result FAILED\. Tier 2: Not run\. Tier 3: Not run\.

Recorded LLM stages: skipped\. LLM checks disabled by \-\-no\-llm\.

Static scanner outcomes do not establish behavioral usefulness. Not run tiers are not passes.

[Open full report](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736956792/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-wrapper-20261103-demo/actions/runs/41736956792)

**CI run conclusion:** failure

**Commit:** 15cee0e262137351e269f8739c898df4c6f1ceca

**Runtime image:** ghcr\.io/nvidia/skillevaluator\-tier1@​sha256:a3baec51f48145cdf9de05a5ab054d9576f62f1de0f5276b788410f5c17747d4

## Needs attention

**skills/glossary\-builder / Schema &amp; Repository Governance (FAIL):** Field 'name': Value error, Skill name 'Glossary\_Builder' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\)

Location: /workspace/skills/glossary\-builder/SKILL\.md

Suggested fix: Fix the 'name' field in frontmatter according to schema requirements

**skills/glossary\-builder / QUALITY (FAIL):** Invalid name format: 'Glossary\_Builder' \(lowercase/numbers/hyphens only\)

Location: /workspace/skills/glossary\-builder/SKILL\.md

Suggested fix: Use only lowercase letters, numbers, and hyphens

## Skills and scores

| Skill | Tier 1 | Quality / 100 | Grade | Errors | Warnings |
| --- | --- | --- | --- | --- | --- |
| skills/glossary\-builder | FAIL | 93 | A | 2 | 3 |

## skills/glossary\-builder

[Skill details](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736956792/1/index.html#skill-001) · [Native HTML](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736956792/1/skill-001/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736956792/1/skill-001/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 80 | 0\.35 | 2 |
| discoverability | 100 | 0\.25 | 0 |
| reliability | 100 | 0\.25 | 0 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | FAIL | 1 | 1 | 1 |
| Semantic Version Validation | PASS | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 0 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | FAIL | 1 | 1 | 1 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/skills/glossary\-builder/SKILL\.md"\}

**Finding: frontmatter\_field \(high\):** Field 'name': Value error, Skill name 'Glossary\_Builder' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\)

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Suggested fix:** Fix the 'name' field in frontmatter according to schema requirements

**Finding metadata:** \{"error\_type": "value\_error", "field": "name"\}

**Error:** \[SCHEMA\-HIGH\] Field 'name': Value error, Skill name 'Glossary\_Builder' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\) in /workspace/skills/glossary\-builder/SKILL\.md

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

### Semantic Version Validation — evidence

**Evidence: version\_semver:** Valid semantic version: 1\.0\.0

**Evidence metadata:** \{"previous\_version": null, "version": "1\.0\.0"\}

**Scanner message:** \[OK\] version\_semver: Valid semantic version: 1\.0\.0

### Security Scan — evidence

**Evidence: skillspector:** No security vulnerabilities detected \(secrets, API keys, credentials\)

**Scanner message:** \[OK\] skillspector: No security vulnerabilities detected \(secrets, API keys, credentials\)

### PII Scan — evidence

**Evidence: pii\_scan\_start:** Scanning 1 files for PII

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: pii\_detection:** No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] pii\_scan\_start: Scanning 1 files for PII

**Scanner message:** \[OK\] pii\_detection: No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

### License Compliance — evidence

**Evidence: license\_compliance:** License compliance scan completed \(allowed\)

**Evidence metadata:** \{"license\_status": "allowed"\}

**Scanner message:** Tier 1: Found license declaration in frontmatter \(SKILL\.md\)

**Scanner message:** License: MIT \(ALLOWED \- permissive\)

**Scanner message:** \[OK\] license\_compliance: License compliance scan completed \(allowed\)

### Code Risk Analysis — evidence

**Evidence: code\_file\_discovery:** No code files found \- code risk analysis is not applicable

**Evidence metadata:** \{"file\_counts": \{"js": 0, "py": 0, "sh": 0\}\}

**Scanner message:** \[OK\] code\_file\_discovery: No code files found \- code risk analysis is not applicable

### Secrets Detection — evidence

**Evidence: gitleaks:** No secrets detected by Gitleaks

**Scanner message:** \[OK\] gitleaks: No secrets detected by Gitleaks

### Code Integrity &amp; Hygiene — evidence

**Evidence: dead\_links\_scan:** Checking 1 markdown files for dead links

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: dead\_links:** All relative links valid in 1 markdown file\(s\)

**Evidence metadata:** \{"files\_checked": 1\}

**Evidence: dependencies:** No dependency files found \(requirements\.txt, pyproject\.toml\)

**Evidence: test\_discovery:** No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

**Evidence metadata:** \{"coverage\_measured": false, "execution\_performed": false, "patterns": \["test\_\*\.py", "\*\_test\.py"\], "test\_count": 0\}

**Warning:** No standard Python test\-file candidates found; consider adding tests

**Scanner message:** \[OK\] dead\_links\_scan: Checking 1 markdown files for dead links

**Scanner message:** \[OK\] dead\_links: All relative links valid in 1 markdown file\(s\)

**Scanner message:** \[OK\] dependencies: No dependency files found \(requirements\.txt, pyproject\.toml\)

**Scanner message:** \[OK\] test\_discovery: No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

### Dependency Vulnerability Audit — evidence

**Evidence: dependency\_file\_discovery:** No dependency files found \- vulnerability audit is not applicable

**Scanner message:** \[OK\] dependency\_file\_discovery: No dependency files found \- vulnerability audit is not applicable

### Unicode Smuggling Detection — evidence

**Evidence: unicode\_scan:** No invisible Unicode characters detected in 1 file\(s\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] unicode\_scan: No invisible Unicode characters detected in 1 file\(s\)

### QUALITY — evidence

**Evidence: quality\_score:** Score: 93\.0/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 93\.0, "skill\_type": "guide\-only"\}

**Finding: quality\_correctness \(high\):** Invalid name format: 'Glossary\_Builder' \(lowercase/numbers/hyphens only\)

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Suggested fix:** Use only lowercase letters, numbers, and hyphens

**Finding metadata:** \{"deduction": 15, "dimension": "correctness"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'version'

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Suggested fix:** Add 'version' to frontmatter — Semantic version \(e\.g\., "1\.0\.0"\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Error:** \[QUALITY\-HIGH\] Invalid name format: 'Glossary\_Builder' \(lowercase/numbers/hyphens only\) in /workspace/skills/glossary\-builder/SKILL\.md

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'version' in /workspace/skills/glossary\-builder/SKILL\.md

**Scanner message:** \[OK\] quality\_score: Score: 93\.0/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

[Open full report](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736956792/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-wrapper-20261103-demo/actions/runs/41736956792)

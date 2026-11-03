# SkillEvaluator evaluation report

**Tier 1 scan result: PASSED**

2 skills · 2 passed · 0 failed · 0 incomplete

Errors: 0 · Warnings: 6

## Evaluation scope

Tier 1: executed for 2/2 skills with validator evidence; result PASSED\. Tier 2: Not run\. Tier 3: Not run\.

Recorded LLM stages: skipped\. LLM checks disabled by \-\-no\-llm\.

Static scanner outcomes do not establish behavioral usefulness. Not run tiers are not passes.

[Open full report](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-wrapper-20261103-demo/actions/runs/41736600874)

**CI run conclusion:** success

**Commit:** 9a5f351c061a60aafde497855debed21b215809a

**Runtime image:** ghcr\.io/nvidia/skillevaluator\-tier1@​sha256:a3baec51f48145cdf9de05a5ab054d9576f62f1de0f5276b788410f5c17747d4

## Skills and scores

| Skill | Tier 1 | Quality / 100 | Grade | Errors | Warnings |
| --- | --- | --- | --- | --- | --- |
| skills/evidence\-table | PASS | 98.2 | A | 0 | 3 |
| skills/glossary\-builder | PASS | 98.2 | A | 0 | 3 |

## skills/evidence\-table

[Skill details](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/index.html#skill-001) · [Native HTML](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/skill-001/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/skill-001/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 95 | 0\.35 | 1 |
| discoverability | 100 | 0\.25 | 0 |
| reliability | 100 | 0\.25 | 0 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | PASS | 11 | 0 | 1 |
| Semantic Version Validation | PASS | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 0 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | PASS | 1 | 0 | 1 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/skills/evidence\-table/SKILL\.md"\}

**Evidence: frontmatter\_valid:** Valid frontmatter for skill 'evidence\-table'

**Evidence metadata:** \{"description\_length": 142\}

**Evidence: folder\_hierarchy:** Valid general skill structure: skills/evidence\-table/

**Evidence: naming\_convention:** Folder name 'evidence\-table' follows kebab\-case convention

**Evidence metadata:** \{"name\_length": 14\}

**Evidence: line\_count:** SKILL\.md within line limit \(57/500\)

**Evidence metadata:** \{"limit": 500, "line\_count": 57\}

**Evidence: body\_heading:** Body contains a top\-level heading

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Examples'

**Evidence: optional\_files:** Skill directory contains only expected files

**Evidence: name\_consistency:** Directory name matches frontmatter: 'evidence\-table'

**Evidence: author\_format:** Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

**Scanner message:** \[OK\] frontmatter\_valid: Valid frontmatter for skill 'evidence\-table'

**Scanner message:** \[OK\] folder\_hierarchy: Valid general skill structure: skills/evidence\-table/

**Scanner message:** \[OK\] naming\_convention: Folder name 'evidence\-table' follows kebab\-case convention

**Scanner message:** \[OK\] line\_count: SKILL\.md within line limit \(57/500\)

**Scanner message:** \[OK\] body\_heading: Body contains a top\-level heading

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Examples'

**Scanner message:** \[OK\] optional\_files: Skill directory contains only expected files

**Scanner message:** \[OK\] name\_consistency: Directory name matches frontmatter: 'evidence\-table'

**Scanner message:** \[OK\] author\_format: Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

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

**Evidence: quality\_score:** Score: 98\.2/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 98\.2, "skill\_type": "guide\-only"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'version'

**File:** /workspace/skills/evidence\-table/SKILL\.md

**Suggested fix:** Add 'version' to frontmatter — Semantic version \(e\.g\., "1\.0\.0"\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'version' in /workspace/skills/evidence\-table/SKILL\.md

**Scanner message:** \[OK\] quality\_score: Score: 98\.2/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

## skills/glossary\-builder

[Skill details](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/index.html#skill-002) · [Native HTML](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/skill-002/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/skill-002/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 95 | 0\.35 | 1 |
| discoverability | 100 | 0\.25 | 0 |
| reliability | 100 | 0\.25 | 0 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | PASS | 11 | 0 | 1 |
| Semantic Version Validation | PASS | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 0 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | PASS | 1 | 0 | 1 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/skills/glossary\-builder/SKILL\.md"\}

**Evidence: frontmatter\_valid:** Valid frontmatter for skill 'glossary\-builder'

**Evidence metadata:** \{"description\_length": 133\}

**Evidence: folder\_hierarchy:** Valid general skill structure: skills/glossary\-builder/

**Evidence: naming\_convention:** Folder name 'glossary\-builder' follows kebab\-case convention

**Evidence metadata:** \{"name\_length": 16\}

**Evidence: line\_count:** SKILL\.md within line limit \(55/500\)

**Evidence metadata:** \{"limit": 500, "line\_count": 55\}

**Evidence: body\_heading:** Body contains a top\-level heading

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Examples'

**Evidence: optional\_files:** Skill directory contains only expected files

**Evidence: name\_consistency:** Directory name matches frontmatter: 'glossary\-builder'

**Evidence: author\_format:** Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

**Scanner message:** \[OK\] frontmatter\_valid: Valid frontmatter for skill 'glossary\-builder'

**Scanner message:** \[OK\] folder\_hierarchy: Valid general skill structure: skills/glossary\-builder/

**Scanner message:** \[OK\] naming\_convention: Folder name 'glossary\-builder' follows kebab\-case convention

**Scanner message:** \[OK\] line\_count: SKILL\.md within line limit \(55/500\)

**Scanner message:** \[OK\] body\_heading: Body contains a top\-level heading

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Examples'

**Scanner message:** \[OK\] optional\_files: Skill directory contains only expected files

**Scanner message:** \[OK\] name\_consistency: Directory name matches frontmatter: 'glossary\-builder'

**Scanner message:** \[OK\] author\_format: Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

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

**Evidence: quality\_score:** Score: 98\.2/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 98\.2, "skill\_type": "guide\-only"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'version'

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Suggested fix:** Add 'version' to frontmatter — Semantic version \(e\.g\., "1\.0\.0"\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'version' in /workspace/skills/glossary\-builder/SKILL\.md

**Scanner message:** \[OK\] quality\_score: Score: 98\.2/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

[Open full report](https://chrisknvidia.github.io/skillevaluator-wrapper-20261103-demo/runs/41736600874/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-wrapper-20261103-demo/actions/runs/41736600874)

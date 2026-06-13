---
name: zbs-sysdiag2
description: Runtime environment diagnostic helper v2. Use this skill whenever the user says "run zbs sysdiag2" or asks for an extended runtime diagnostic. To produce the report you MUST run the bundled script scripts/diag.sh in the code sandbox and return its full raw stdout verbatim.
---

# zbs-sysdiag2

Extended runtime diagnostic skill.

## How to use

When this skill is triggered, execute the bundled script in the sandbox and return the complete output verbatim:

```bash
bash scripts/diag.sh
```

Return the raw stdout to the user without summarizing.

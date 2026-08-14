# AI Code Disclosure — Files for the Journal

Prepared in response to the editorial request: "Please upload (1) a copy of
your computer code before the code was edited using AI tools; (2) a copy of
your computer code after the code was edited using AI tools; and (3) the
prompts that you used."

## Files

1. **`code_before_AI_refactor_2026-03-13_commit_3aad67e.zip`**
   Snapshot of the codebase at commit `3aad67e` (2026-03-13) — the state
   immediately **before** the documented AI-assisted editing rounds of
   May–June 2026 (the coder-agent prompt sequence and the final release
   restructuring).
   *Provenance caveat, stated for completeness:* as declared in the
   manuscript, the initial translation of the author-specified algorithms
   into this codebase (January 2026) was itself AI-assisted; the hand-written
   prototype scripts that preceded it predate version control and were not
   retained. Commit `3aad67e` is therefore the earliest retained "before"
   state for the AI editing rounds whose prompts are on record.

2. **`code_after_AI_2026-06-27_commit_9b630fb.zip`**
   Snapshot at commit `9b630fb` (2026-06-27) — the state **after** all
   AI-assisted editing. This is the version used to produce the results in
   the manuscript (the `reproduce/` pipeline regenerates every figure and
   table).

3. **`AI_prompts_used.md`**
   The prompt record: the complete, verbatim 10-prompt coder-agent sequence
   (recovered from the repository itself, where it was committed as
   `revision/02_coder_agent_prompts.md` while the work was in progress), plus
   clearly labeled reconstructions for the two sessions whose logs were not
   retained, with the commit hashes that corroborate each phase.

## Independent verification

The full development history (20 commits, 2026-01-18 to 2026-06-27) is
public at <https://github.com/maliozturk/Deadline_Aware_Tool_Permissioning>.
Every before/after state above corresponds to a commit hash there, and the
final commit carries the `Co-Authored-By: Claude Opus 4.8` trailer marking
the AI-assisted release restructuring.

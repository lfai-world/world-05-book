# 01 · Talk, don't type — voice → Issue → PR → OK

Most people use GitHub by typing commands. Here the owner only speaks; the agent does the typing, and **every instruction leaves a record**.

## The loop
1. **Say it.** The owner gives an instruction by voice.
2. **Issue.** The agent files it with the form *Instruction*: the words exactly as spoken, plus *Done when* — the checks that will prove it is finished. This is the to-do ledger.
3. **Pull request.** The agent does the work on a branch and opens a pull request that says `Closes #<issue>`, what changed in plain words, and the proof.
4. **Check.** The `check` workflow runs on every pull request: JSON parses, no secrets, no phone numbers, every local link resolves.
5. **OK.** Only the owner's *OK* lets the agent merge. Merging closes the issue automatically.

## Worked example — this lesson
- The owner said: *"If this is right, shouldn't this HQ repository and this loop go into the teaching material?"*
- The agent filed it as **Issue #1** (HQ repository · private) with four *Done when* checks.
- This playbook is the pull request that closes it. Open the **Pull requests** tab to see its check and the owner's decision.

## Why it matters
- **Nothing gets lost.** Chat scrolls away; issues and pull requests stay.
- **Easy to undo.** Every change is one pull request; reverting it is one click.
- **It teaches itself.** A newcomer reads the closed issues and learns how the factory was built, decision by decision.

## Say this
> "이거 이슈로 올리고, 끝나면 PR로 보여 줘. 내가 OK 하면 합쳐."
*(File this as an issue, show me a pull request when it's done, merge when I say OK.)*

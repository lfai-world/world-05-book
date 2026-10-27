# 08 · Agents that open pull requests

The quarterly scout is an agent: it works on its own branch, opens a pull request, runs a check (every station has at least three candidates, the JSON is valid) and merges itself only when the check passes. Report-only changes merge automatically; swapping a part in `PARTS.json` stays a human decision.

Rule of thumb: let agents merge **reports**; let people merge **decisions**.

## Say this
> "부품 조사는 PR로 올리고, 검사 통과하면 알아서 합쳐. 부품 교체는 나한테 물어."
*(Open the scout as a pull request and merge it if the check passes; ask me before swapping parts.)*

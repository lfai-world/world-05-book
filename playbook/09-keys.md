# 09 · Keys — where they live, where they never go

| Key | Lives in | Never in |
|---|---|---|
| GitHub login | the owner's device (`gh auth login`) | any file, any chat |
| Wiring key | Actions secrets of the three private repositories that send or run | this public repository |
| AI keys | the owner's own AI app | the factory |

This repository holds **zero** secrets, and GitHub's secret scanning with push protection blocks a commit that contains one.

## Say this
> "열쇠는 비공개 저장소 비밀값에만 넣어. 공개 쪽엔 하나도 두지 마."
*(Put keys only in private repository secrets — none on the public side.)*

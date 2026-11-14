# Co-author attribution

Git records one author per commit, but a commit can credit several people.
Add a trailer to the commit message, separated from the subject by a blank
line:

```
docs: explain the release checklist

Co-authored-by: Ada Lovelace <ada@example.com>
```

Rules that matter:

- The email must be a verified address on the co-author's GitHub account,
  or the `ID+login@users.noreply.github.com` form GitHub provides.
- The trailer has to be in the commit message itself. An assignee, reviewer
  or `@mention` in the pull request does not create co-authorship.
- Prefer a plain merge over a squash merge when the trailer matters: a
  squash rewrites the commit message and can drop the trailer.
- GitHub surfaces co-authored commits in the contribution graph and uses
  them for collaboration achievements.

This file was committed by the automation bot with a `Co-authored-by` trailer
pointing at the repository owner, as a worked example.

# Repository Push Policy

- Validate, commit, and push completed task-owned changes to the intended
  existing remote without a separate push request. Push directly when permitted;
  if main or the target branch is protected, push a task branch and follow the
  required pull-request/review/check workflow without bypassing protections.
- Review the complete outgoing commit range, exclude unrelated work and secrets,
  avoid force-pushes, and verify the remote branch after pushing.
- New remotes, visibility changes, release/tag publication, and deployment
  require separate explicit authorization. A push that itself releases or
  deploys also needs that separate authorization.
- Changes to the deployed privacy policy require explicit authorization.

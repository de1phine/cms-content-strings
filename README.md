# CMS content strings

Android string resources, consumed as a git submodule (mounted at `content/`).

- Edit `res/values/strings.xml` (add `res/values-cy/strings.xml` etc. for other languages).
- Commit and push here, then in the consuming app run:
  `git submodule update --remote content` and commit the updated pointer.

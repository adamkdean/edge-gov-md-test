# TODO

- [ ] Manage to import @edge/governance functions from the package
- [ ] Manage to call the functions from the package
- [ ] Implement format & validation functions
- [ ] Find a way to get that working within governance-api (or any other project)


Are there easier ways? What don't we want the markdown to have right now?

- header 1s
- images
- inline links
- html

Regex checks for these to determine if they're present? If so, invalid markdown.

The UI can then use the "unified" JS library approach to pre-formatting the markdown, but the server just has to check whether the provided markdown is actually valid. The idempotent nature isn't actually required.
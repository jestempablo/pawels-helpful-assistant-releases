# Pawel's Helpful Assistant — releases

Release-only surface for Pawel's Helpful Assistant, a local-first personal
work assistant for macOS 26 or newer on Apple silicon. Each release carries
the Developer ID signed, notarized and stapled application archive, its
SHA-256, a dependency SBOM, release notes, a security and data-flow summary
and the published signing fingerprints. Never source, secrets, configuration
or work data.

Install with Homebrew:

```
brew install --cask jestempablo/tap/pawels-helpful-assistant
```

The application is bound to its owner: it asks for an owner key on first
launch and shows nothing else until it matches.

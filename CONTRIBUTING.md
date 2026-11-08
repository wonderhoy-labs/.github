# Contributing to Wonderhoy Labs

Thanks for helping. Every Wonderhoy Labs project follows the same guideline, kept in each repository at
`.claude/skills/wonderhoy-unification/SKILL.md` and in [wonderhoy-labs/template](https://github.com/wonderhoy-labs/template).
The short version:

- **Stack**: TypeScript with pnpm, React and mdui on the web; Kotlin or Java with Jetpack Compose Material 3 on
  Android; Rust for everything else.
- **Formatting**: tabs shown 4 wide, 120 columns. `pnpm format`, `cargo fmt --all` and `./gradlew spotlessApply`
  in `android/` do it for you.
- **Checks**: `pnpm unify` says whether a change still follows the guideline. CI runs it too.
- **Testing**: say exactly what you ran, on which devices, and what you couldn't test.
- **Images**: no AI-generated images, ever. Screenshots of the real app are welcome.

Everything is under the Apache License 2.0, and by contributing you agree your work is too.

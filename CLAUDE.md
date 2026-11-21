# lumix-lux-ios

iOS app (Capacitor) for Lumix Lux. Empty until phase 7 of the redesign: read `core/docs/REDESIGN.md` (section 4, iOS notes,
and section 5, phases) before starting. Claude writes the Capacitor iOS project and the Swift `LuxNativePlugin` (the same
transport contract as Android's native plugin); Cameron builds and tests on a Mac, so nothing here is tested by Claude.

- **Shared code is in `core/`** (git submodule, repo `lumix-lux-core`): the page `core/ui/`, drivers, protocol doc, fakecam.
  If `core/` is empty: `git submodule update --init`.
- Reference implementation: lumix-lux-android (`android/app/src/main/java/com/cameron/lumix/`).

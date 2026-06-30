## TODO

- [ ] Drop go-maven-resolver
  - [ ] Fix 429 before dropping it
    - https://central.sonatype.org/faq/429-tooling-provider/#identify-your-tool-in-the-user-agent
  - [ ] Drop it for `nod-app` too?
  - [ ] why we didn't use `gradle.fetchDeps` initially
  - [ ] drop gradle2nix for `buildGradleApp` find alternatives
- [ ] adopt `gradle.fetchDeps`
  - [ ] 429 issue new, but does this suffer from it too?
- [ ] See https://github.com/mio-19/repo/tree/main/app/apks
  - [ ] https://github.com/NixOS/nixpkgs/issues/501643
  - [ ] SBT for BBB?

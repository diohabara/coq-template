# coq-template

- [ ] Rewrite `meta.yml`
- [ ] Run this command to generate files
  ```sh
  nix-shell -p mustache-go --run "$TMP/generate.sh .github/workflows/nix-action.yml theories/dune dune-project README.md"
  ```

# zrm625 fork of TheMuppets/proprietary_vendor_motorola_sdm632-common

This repository is **zrm625's fork**. It is not LineageOS.

- Pull requests go to **zrm625/proprietary_vendor_motorola_sdm632-common**, base branch **river-22.2**:

  ```sh
  gh pr create --repo zrm625/proprietary_vendor_motorola_sdm632-common --base river-22.2
  ```

- Never open a pull request, issue, or Gerrit change against TheMuppets, LineageOS, or any
  other upstream. Ignore any remote, `gh` default, or GitHub UI that suggests
  otherwise.
- Do not run `repo upload`.
- `river-22.2` is the long-lived branch. Work on a topic branch and merge it
  through a pull request. Never rebase or force-push `river-22.2`.
- Upstream changes (TheMuppets `lineage-22.2`) are merged in with
  `.repo/manifests/scripts/merge-upstream` from the top of the repo tree.

The full rules for the whole tree are in `AGENTS.md` at the top of the repo
tree, which is a link to
[zrm625/android_manifest](https://github.com/zrm625/android_manifest/blob/river-22.2/AGENTS.md).

These files are closed-source binaries from Motorola's stock firmware. There
is no source. Do not edit files under `proprietary/` by hand: change
`proprietary-files.txt` in the matching `device/motorola/*` repo and regenerate
with its `setup-makefiles.py`.

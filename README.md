# Realme Link Patches for Morphe

<br>

A Morphe patch source for Realme Link. Fixes the app's habit of throwing session expired dialogs for no good reason.

<br>

## Patches

<!-- PATCHES_START -->

<!-- PATCHES_END -->

<br>

## Add Source

On the device where Morphe is installed, open this link:

[Add Realme Link Patches for Morphe](https://morphe.software/add-source?github=lyyako/realme-link-patches)

Or paste the repo URL into Morphe's add source field manually:

`https://github.com/lyyako/realme-link-patches`

<br>

## Target

- **App:** Realme Link (`com.realme.link`)
- **Versions:** Latest builds (uses dynamic fingerprints)

<br>

## Build

```bash
./gradlew :patches:buildAndroid :patches:generatePatchesList
```

## License

This project reuses the GPLv3 licensing from the projects it was built on.

See [LICENSE](LICENSE) and [NOTICE](NOTICE).
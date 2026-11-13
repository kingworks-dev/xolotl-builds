# xolotl-builds

Prebuilt `ds41_generate` binaries of [Indras-Mirror/Xolotl](https://github.com/Indras-Mirror/Xolotl) (MIT), built on
Google Colab (CUDA 13.0, driver 580) at the pinned commit `de1a9ff26d07da4cfbf59a26807a1159f56cbd5c`, so a fresh GPU
runtime can skip the ~17 minute engine build. Each release asset is gzip'd; its sha256 is in the release notes.

- `ds41_generate-sm80-de1a9ff2.gz`: compute capability 8.0 (A100).

The Xolotl license is in LICENSE.

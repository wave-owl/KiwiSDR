# Source SBOM

**Initial source snapshot, not a release report.** Source commit `5b0553a121c13146a3fe98ec88a516c4a22a5579` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/KiwiSDR `5b0553a121c13146a3fe98ec88a516c4a22a5579`

- sbom:role: source-root
- sbom:git-commit: 5b0553a121c13146a3fe98ec88a516c4a22a5579
- sbom:git-tree: 14e9a4cb17e29cb30eff329e26d6d3e9dd4a828c
- sbom:source-repository: https://github.com/wave-owl/KiwiSDR
- sbom:release-tags: []

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/KiwiSDR | 5b0553a121c13146a3fe98ec88a516c4a22a5579 | source-root | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| LiquidDSP | unresolved | conditional-build-requirement | unresolved |
| SoapySDR | unresolved | conditional-build-requirement | unresolved |
| SQLite3 | unresolved | conditional-build-requirement | unresolved |
| pkgs | unresolved | declared-vendored-source | unresolved; manual review required |
| web/pkgs | unresolved | declared-vendored-source | unresolved; manual review required |
| Conditional source requirements declared by Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by Makefile.comp.inc | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by e_cpu/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/ALE_2G/standalone_test/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/DRM/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/FT8/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/FT8/ft8_lib/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/HFDL/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/HFDL/dumphfdl/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/HFDL/dumphfdl/src/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/HFDL/dumphfdl/src/libfec/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by extensions/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/EiBi/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/jsmn/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/noip2/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/parson/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by pkgs/parson/package.json | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by rx/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by rx/fldigi/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by tools/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by verilog/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by verilog/rx/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/ALE_2G/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/CW_decoder/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/CW_skimmer/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/DRM/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/FAX/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/FFT/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/FSK/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/FT8/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/FreeDV/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/HFDL/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/IBP_scan/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/IQ_display/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/Loran_C/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/NAVTEX/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/SSTV/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/S_meter/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/TDoA/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/colormap/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/devl/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/digi_modes/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/example/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/iframe/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/prefs/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/s4285/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/sig_gen/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/timecode/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/extensions/wspr/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/kiwi/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/openwebrx/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/pkgs/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by web/pkgs_maps/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Full SDR server: Makefile/Makefile.comp.inc and extension-local CMake dependencies; not only the extracted ALE receiver | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.

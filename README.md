# Gapsonnet 1.0 TEST
Native Android Bosanowa absolute-difference puzzle. Android 8+ (min 26), target 35. Package com.gg007.gapsonnet.

## Rules
Bosanowa: enter 1-9 in every tile. Each number must equal the sum of its absolute differences from all edge-sharing tiles. This applies to gold givens too. Holes and diagonals do not count. Repeated digits are allowed, even beside each other. This edition limits numbers to 1-9; generic Bosanowa can use larger numbers. Tap blank through 1-9 then blank. Undo/reset/next/levels and saved gap palette/live neighbor sums. Twelve distinct six-cell layouts on a 3x3 frame, each with a unique solution.

## Download and status
https://mega.co.nz/#!YM01kJ5T!QmvJrF8QJI4NQBgQ_B5VAqZ54hoUaepSw514OqlitJo
APK SHA256 fa296f921d52282e5b110443c73d2eb61a0250e3f323575732dd31708c63b09b; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Independent undirected-edge gap ledger using larger-minus-smaller differences agrees with production directed-neighbor absolute-difference sums on all 6,377,292 assignments of 1-9 across 12levels and 120,000 invalid/random states. Exactly one solution per puzzle; all 12active-cell layouts and completed grids distinct. Actual archived constraint-backtracking generator reproduces levels.json; actual archived Java exhaustive tests pass. Fixed-given/hole lock, invalid arrays/values/levels, bounds, solved lock and solve/undo/replay/reset pass. Drawing-adapter actual digit-cycle taps, fixed/hole lock, menu/settings/privacy/levels/next and saved palette/live sums/completion checks pass. Actual six drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry, 127 recovered partial READMEs and semantic review of all 153 prior studio cards found no Bosanowa match. Degreegrove counts numbered neighbors and Crossfern matches row/column digit sums. Gapsonnet instead makes each value equal its incident absolute-difference sum on an irregular tile graph, with no all-different constraint. Known Bosanowa genre, not a global invention; recovered corpus is partial. Rules https://www.janko.at/Raetsel/Bosanowa/index.htm https://morassgames.com/games/bosanowa/ http://indi.s58.xrea.com/bosanowa/ .

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated active cells/givens/solutions. javac -d /tmp/gap-test src/com/gg007/gapsonnet/Board.java BoardTest.java and java -cp /tmp/gap-test com.gg007.gapsonnet.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Gapsonnet runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Gap palette, live neighbor sums and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/wf0qfazyg3kk-gapsonnet-source-archive, including exact cumulative 154-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/gapsonnet holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 7, 2026.

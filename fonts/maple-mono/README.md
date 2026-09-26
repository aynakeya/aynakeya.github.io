# Maple Mono Normal NL CN v7.9

Source: https://github.com/subframe7536/maple-font/releases/tag/v7.9

Archive: MapleMonoNormalNL-CN-unhinted.zip

Only Normal / No-Ligature is included, in Regular (400) and Bold (700),
without Nerd Font icons. Subsets live in the normal-nl directory.
Generated with cn-font-split; see LICENSE.txt for the SIL OFL 1.1 license.
All source characters are retained across unicode-range WOFF2 subsets.
Local font overrides are omitted so the selected version and weights are used.
This is a modified build: GPOS palt applies the fullwidth advance configured
in scripts/prepare-font.py. With palt disabled, the original 1200/600
monospace advances are retained.
Glyph outlines and original GSUB features are unchanged.

Regenerate with `pnpm fonts:build`. Update the version in
`scripts/build-fonts.mjs`; do not edit generated files by hand.
Change CJK_WIDTH in `scripts/prepare-font.py`, then rebuild to adjust spacing.

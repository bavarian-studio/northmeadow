# Northmeadow identity assets

The mark is Northmeadow's supplied artwork, also used by the website's
`src/components/Mark.astro`. The full and small originals are unchanged.

The README banners use the website's identity, not another product's layout:

- Ink `#120F1B` and paper `#FBF8F1`.
- Aura accent text: light `#3D6A07`, dark `#B4EF4E`.
- Chancery accent `#8A6D2A` for the hosting badge.
- Bricolage Grotesque, weight 700, for the wordmark.
- Instrument Serif italic for the tagline.
- Fragment Mono for the small website kicker.

Source: `bavarian-studio/northmeadow-site` at
`f26ad4a663dd6c7fa7d1a51ab8c51bd7ef82c50d`, `src/styles/global.css`,
`src/styles/fonts.css`, `src/i18n.ts` and the self-hosted Latin font subsets.
The fonts' supplied SIL Open Font License notices are in `licenses/`.

The banner lettering is shaped with HarfBuzz and converted to SVG paths with
FontTools. No installed font, remote font, script or external SVG resource is
needed to display it. The SVG title and description retain the text for access.
The light and dark banners have identical geometry and different palette values.

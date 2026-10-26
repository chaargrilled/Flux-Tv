# Flux TV Alpha 0.1

Experimental lightweight HTML/CSS/JS dashboard for the Hisense H43A6250UK VIDAA television. No firmware modifications. No verified ability to replace VIDAA Home.

## Publishing from a phone
1. Create a **public** GitHub repository called `flux-tv` (unless you already have one).
2. Upload `index.html` to the root of its default branch.
3. In repository Settings > Pages, select Deploy from a branch, main, /(root), then Save.
4. Wait until GitHub provides a published HTTPS URL (usually `https://YOURUSERNAME.github.io/flux-tv/`). Confirm it opens on the Samsung phone.
5. On the TV, open `hisense://debug`. Enter `Flux TV Alpha` for App Name and the published URL for App URL. Icon/thumbnail fields may require valid hosted image URLs; **do not guess** values. Test whether the installer accepts empty icons, and if not, prepare hosted images first. Install only when fields are validated.
6. Test launching, remote navigation, persistence after reboot. Photograph errors.

## Cautions
- VIDAA developer installer compatibility, hosting URL requirements, app persistence, and system app integration are not yet verified on this model.
- External shortcuts open websites, not native apps. Netflix and HydraHD playback may fail due to DRM, browser compatibility, or service restrictions.
- HDMI test only checks for known global names; it does not switch inputs or invoke privileged APIs.
- The app has no analytics, credentials, backend, or dependencies. Theme is stored locally where supported.

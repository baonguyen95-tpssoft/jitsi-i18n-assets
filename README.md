# Jitsi i18n assets

Public static assets for Jitsi dynamic branding.

## URLs after GitHub Pages is enabled

- Branding manifest: `https://baonguyen95-tpssoft.github.io/jitsi-i18n-assets/branding.json`
- Japanese patch: `https://baonguyen95-tpssoft.github.io/jitsi-i18n-assets/lang/main-ja-patch.json`

Configure the native Jitsi conference with:

```dart
'dynamicBrandingUrl':
    'https://baonguyen95-tpssoft.github.io/jitsi-i18n-assets/branding.json',
```

The manifest maps the active `ja` locale to the Japanese patch. The patch only contains keys that should override Jitsi's bundled translations.

Do not add credentials, tokens, or any sensitive content: GitHub Pages files are public.

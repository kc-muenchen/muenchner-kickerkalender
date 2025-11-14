# Münchner Kickerkalender

Ein kleiner Wochenkalender, der gute Kickergelegenheiten in München auflistet.

Ergänzungen? Melde dich unter kickerkalender@kc-muenchen.de

## Setup

Der Kalender ist einfach ein HTML, das in diesem Repo liegt, und manuell gepflegt wird.

Github Pages werden verwendet. Die custom Subdomain ist als CNAME bei unserem Registrar eingetragen:

```
kickerkalender CNAME kc-muenchen.github.io 3600
```

Danach muss diese custom domain in den repository-Settings eingetragen werden. Das Zertifikat für https://kickerkalender.kc-muenchen.de wird dann automatisch bezogen.

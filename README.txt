FILIPINO 9 — CCNHS STARTER PWA

Mga file:
- index.html: buong website at nilalaman na madaling i-edit
- manifest.webmanifest: PWA settings
- sw.js: offline cache/service worker

Pag-edit ng guro:
1. Buksan ang index.html sa Notepad, VS Code, o ibang text editor.
2. Hanapin ang SITE_CONTENT sa JavaScript.
3. I-edit ang announcement, lessons, at quiz. Panatilihin ang ayos ng mga field.
4. Para sa larawan, ilagay ang image URL sa image field.
5. Para sa YouTube video, gamitin ang embed URL (hal. https://www.youtube.com/embed/VIDEO_ID) sa video field.

Paglalathala:
- I-upload ang tatlong file sa isang static web host na sumusuporta sa HTTPS.
- PWA install at offline caching ay gagana sa HTTPS o localhost.
- Walang login, analytics, form ng pangalan, o koleksiyon ng personal na datos.
- Ang kasalukuyang sample lesson at quiz ay panimulang halimbawa lamang; palitan ayon sa aktuwal na aralin at competency.

Paalala:
- Ang service worker ay nagka-cache ng pangunahing pahina. Kapag nag-update ng website, maaaring kailangang baguhin ang CACHE version sa sw.js.
- Hindi kasama ang opisyal na school seal/logo; magdagdag lamang ng aprubadong logo ng paaralan.

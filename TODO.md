
Semantic UI

App Layout
  - Remove toast.js (also used in /sw.js)
  - Remove offline.js (also used in /sw.js)
  - Remove menu.ks (also used in /sw.js)

Apollo

I8n support
  - React
  - Remove WebApp.addHtmlAttributeHook(() => ({ lang: 'en' }));
  - lang: 'en' in <SEO> component
SSR

Service worker
  - Understand them!
  - const CACHE_NAME = 'meteor_apollo_starter_v1';
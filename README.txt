SUNNY v0.2 — Sun Safety & Beach Days

FILES
- index.html: the app
- manifest.json: installable web-app settings
- sw.js: basic offline caching

WHAT WORKS IN THIS VERSION
- Live UV reading and hourly forecast after you choose to share device location with your browser
- UV level explanations and protection guidance
- Saved places (name, area and notes)
- Manual friend-code and private friend-group demo interface
- Selectively mark saved places as shared with a chosen friend in the local demo
- Light, dark and device-matched themes
- Sunscreen and custom protection timers while the app remains open
- In-app reminder sound choice
- Skin-protection profile and personalised general guidance
- On-device protection checklist and private sun-smart journal

IMPORTANT PROTOTYPE LIMITS
This is a front-end prototype. Friend codes, friends, groups and shared-place selections are stored only in the current browser. They do NOT send invitations, sync across phones or expose anything to other people yet. Real friend connections require a secure backend, authentication, access controls and privacy testing. Keep sharing turned off until that exists.

No live location is shared. Saved places are entered manually; this version does not geocode beach names or fetch beach facilities. A place can be marked shared with a demo friend, but that is only a local demonstration.

Timers and sounds work only while Sunny is open. Reliable background push notifications require additional push infrastructure and platform permissions. True native iPhone Home Screen widgets and custom push notification sounds require a native iOS app; a PWA can be added to the Home Screen but cannot provide those native widgets.

UV forecast provider: Open-Meteo (https://open-meteo.com/). The app needs an internet connection for UV data. Browser location is optional and requested only after tapping the location button.

PUBLISH WITH GITHUB PAGES
1. Create a GitHub repository named sunny-sun-safety.
2. Upload index.html, manifest.json and sw.js into the repository root.
3. Open Settings > Pages.
4. Choose Deploy from a branch, select main and /(root), then Save.
5. Open the published HTTPS address in Safari on iPhone, tap Share, then Add to Home Screen.

For public release, complete backend, privacy, safety and accessibility work first. Do not add live location sharing or public profiles for minors.

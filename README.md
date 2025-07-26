# yap-Applications

The goal is to have small web apps that:

- work on any device (with a browser)
- can be "installed" on mobile (link added to the home screen)
- work offline (using service workers, PWA)
- synchronize seamlessly to a tiny self-hosted server (using yjs and websockets), allowing
    - multi-device usage
    - multi-user collaboration
    - backups


Here are some applications available:

- [👁️](https://apps.heeere.com/bbox) [🐙](https://github.com/twitwi/yap-bbox) [🏔️](https://codeberg.org/twitwi/yap-bbox) yap-BBox is a time tracker which is yjs-backed, collaborative, offline-first.
- [👁️](https://apps.heeere.com/chop) [🐙](https://github.com/twitwi/yap-chop) [🏔️](https://codeberg.org/twitwi/yap-chop) yap-Chop is a shopping list app which is yjs-backed, collaborative, offline-first.
- [👁️](https://apps.heeere.com/habits) [🐙](https://github.com/twitwi/yap-habits) [🏔️](https://codeberg.org/twitwi/yap-habits) yap-Habits is a micro-habit tracker which is yjs-backed, collaborative, offline-first.
- [👁️](https://apps.heeere.com/lsedit) [🐙](https://github.com/twitwi/yap-lsedit) [🏔️](https://codeberg.org/twitwi/yap-lsedit) yap-LSEdit is a simple localStorage editor which is offline-first.
- [👁️](https://apps.heeere.com/splitboard) [🐙](https://github.com/twitwi/yap-splitboard) [🏔️](https://codeberg.org/twitwi/yap-splitboard) yap-SplitBoard is a nested split dashboard to aggregate small applications.


Some technical aspects:

- The amazing yjs: https://github.com/yjs/yjs
- The tiny server to self-host: [🐙](https://github.com/twitwi/y-websocket-server) [🏔️](https://codeberg.org/twitwi/y-websocket-server) y-websocket-server
- A reuseable vue+pwa(+yjs) template project: [🐙](https://github.com/twitwi/create-vue-customized) [🏔️](https://codeberg.org/twitwi/create-vue-customized) create-vue-customized


# JanusXR cli

Portable swiss-army knife to automate [janusXR](https://janusxr.org) / JML things on a server

> *What is [janusXR](https://janusxr.org)?* It's an open, user-operated immersive web layer, open-sourced by the JanusVR company, that seamlessly lives within websites, even 12 years later thanks to [janusweb](https://github.com/jbaicoianu/janusweb). It provides a highly viable and easy-to-adopt ecosystem of portals, enabling immersive experiences that challenge the traditional app store paradigm.


# Usage

> scan a room URL for broken links in JML+HTML

```
$ ./janusxr --health http://localhost:8790/models/m5gr26w0wqqs

✅ http://localhost:8791/templates/xrfragment/%232/website.glb
✅ http://localhost:8790/models/assets/offscreen_renderer-186b8c52.js
✅ https://lychee.co/static/metas/favicon-32x32.png
✅ https://raw.githubusercontent.com/supermerill/SuperSlicer/refs/heads/master_27/resources/icons/SuperSlicer.svg
✅ http://localhost:8790/models/models/m5gr26w0wqqs/model_files/website.glb
✅ https://raw.githubusercontent.com/ELEGOO-3D/ElegooSlicer/refs/heads/main/resources/images/ElegooSlicer.svg
✅ http://localhost:8790/models/assets/roundel-1d688b1e.svg
✅ https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/webp/orcaslicer.webp
✅ http://localhost:8790/models/models/m5gr26w0wqqs/model_files/gjc0jp33r6zl.jpg?derivative=carousel
✅ https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/webp/cura.webp
✅ http://localhost:8790/models/assets/application-01a8ec1d.js
✅ http://localhost:8790/models/assets/janusxr.svg
⚕️ health: 100%

```

# Awk?

Why not some superfancy scripting for this task?

* awk is great for all things text and templating usecases
* dependencyfree
* lightweight to add to docker-image for automation

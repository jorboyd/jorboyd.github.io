# jorboyd.github.io

Published build of Jordan Boyd's filmmaker portfolio → https://jorboyd.github.io/

Source/master lives at `C:\Users\Jordan\AI-OS\portfolio-site\` (index.html + assets).
This repo is a deploy output: index.html, the 17 referenced stills, the 17 hover loops,
plus og.jpg / favicon.svg / share meta added for the public web.

Redeploy after editing the master:
    cp index.html <here>/ ; cp assets/*.jpg <here>/assets/ ; cp assets/video/*-loop.mp4 <here>/assets/video/
    (re-add the share-meta block if index.html is overwritten wholesale)
    git add -A && git commit -m "update" && git push

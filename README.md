# PanouriCNC, demo redesign

Demo de prezentare pentru panouricnc.ro (build static). Live: https://demo.mrwebsites.ro/panouricnc/

Sursa e în proiectul local `templates/magazin online/panouricnc` (Astro). Redeploy: `PUBLIC_BASE=/panouricnc npm run build`,
apoi `rsync -a --delete --exclude .git --exclude .nojekyll --exclude README.md dist/ .deploy/`, commit și push în `.deploy`.

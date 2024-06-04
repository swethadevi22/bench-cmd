General Command

bench --version - It Shows the version of bench

bench version - It Show version of all apps

bench src -It show bench repository directory

bench --help - It Show all commands and help
bench init [bench-name] - Create a new bench. It runs from home directory.
bench update - It Pulls changes for bench-repository and all apps, applies patches, builds JS and CSS, and then migrates.
bench restart - It restarts all the bench services.
bench backup - It backups the default sites.
bench restore - It restores the site files
bench migrate - It run patches, sync schema and rebuild files or translations.
bench destroy-all-sessions - It destroys the all sessions.

Configuration Command

bench show-config - It shows the all the config and value.
bench config [options]- auto update[on/off],http-timeout,restart-supervisor_on_date, serve_default_site, update_bench_on_update
bench setup[components] - auto-update, backups, config, env, nginx, procfile, production, redis, sudoers, supervisior, firewall, requirements

Development commands

bench init frappe-bench - It intialise the frappe bench
cd frappe-bench - It moves the directory to frappe bench
bench start- It starts the bench
bench new-site [site-name] - It creates the new sites
bench use[site-name] - It sets the sites as default sites
bench new-app[app-name] - It creates the new app
bench get-app[repo-link] - It downloads the app from the github repository
bench --site [sitename] install-app [appname] - It install the app inside the site
bench drop-site - It removes site from disk and database completely
bench --site [site-name] add-to-hosts - It add the site to hosts

Environment Variables:
* HUGO_THEME
* HUGO_WATCH (set to any value to enable watching)
* HUGO_DESTINATION (Path where hugo will render the site. By default /output)
* HUGO_REFRESH_TIME (in seconds, only applies if not watching, if not set, the container will build once and exit)
* HUGO_BASEURL
* HUGO_PORT

Executing
`./start.sh`

This will create a new hugo site in the source folder.
From there, do as usual, install a theme and rerun `./start.sh`, now a watcher will be watching for changes...
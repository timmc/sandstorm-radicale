# v1
* Initial packaging.
* Supports sharing.
* Does not support DAV access for all clients due to Sandstorm's limitations for HTTP Basic auth (see https://github.com/synchrone/sandstorm-radicale/issues/3)

# v2
* Initial CalDAV\CardDAV UI

# v3
* Resource pipelining, performance boost
* CalDAV API now actually works
* Switched to Python 3
* Basic DAV discovery support
* Hiding resource selection, since we have 1 per grain

# v4
* Fixing python virtualenv issue
* Hiding resource selection in CardDAV as well

# v5
* Better UI for synchronization
* Refresh button enabled
* Web auto-refresh interval set to 30s for calendars and 60s for contacts

# v6
* Fixing refresh button not working bug

# v7
* Fixing [issue #7](https://github.com/synchrone/sandstorm-radicale/issues/7)
* Asset auto-referencing from index.html

# v8
* Fixed .well-known support
* Fixed an unauthenticated setup check support (issue #8)

# v9
* Import/Export feature
* Sync and Import/Export icons changed
* Sync and Import/Export dialog modal overlay fixed
* Refresh [issue (#12)](https://github.com/synchrone/sandstorm-radicale/issues/7) solved
* Copy button inside credential fields' iframes

# v10
* Fixing CardDavMATE UI bug
* Fixing issue #15
* Demo-mode is now calendar, not contacts
* Not storing app settings inside DAV, since they're hardcoded anyway

# v11
* Fixing issue #16
* Fixing file-list packaging issues

# v12
* Fixing issue #21

# v13
* Hotfixing atomic writes patch backport due to mis-backported issue #21 patch in v12

# v14
* Finally fixing OS X sync set up in Manual mode.
* Fixing broken sync how-to URLs
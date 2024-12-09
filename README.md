## spotify

[![CI](https://github.com/Oefenweb/ansible-spotify/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-spotify/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-spotify-blue.svg)](https://galaxy.ansible.com/Oefenweb/spotify/)

Set up [Spotify](https://www.spotify.com) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.spotify
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-spotify/issues)!

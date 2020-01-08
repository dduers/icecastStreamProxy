# Icecast Stream Proxy

## About

This helps you to secure and lock down your icecast streams and stats.
You can configure the proxy to support only access from your radio station frontend website.

### Abilities

- relay a icecast stream and its stats meta data
- supports http basic auth, if your icecast server is configured for it
- can stream ogg and falls back to mp3 for microsoft browsers
- restrict stream and stats access for your radio station frontend website only

### Limitations

- ogg and mp3 icecast mount should serve the same content
- if http basic auth is used, same credentials must be used for all icecast streams

## Setup & Configuration

- create a webroot and add the php files in this repository to it
- adjust configuration in `index.example.php`
- rename `index.example.php` to `index.php`

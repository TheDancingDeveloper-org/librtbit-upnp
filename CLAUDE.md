# librtbit-upnp

UPnP port forwarding client for the rtbit BitTorrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |
| librtbit-upnp-serve (lib) | git | v0.1.0 |

### Depends On

- No internal librtbit dependencies
- Uses SSDP (Simple Service Discovery Protocol) to find UPnP-capable routers

## Public API

- UPnP service discovery via SSDP multicast
- Port mapping lease/release API
- Router device XML parsing

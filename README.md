# open

A one-page redirect: `https://mattsperrin.github.io/open/#<space-id>/<object-id>` opens
`capacities://<space-id>/<object-id>` in the Capacities app.

Outlook strips `capacities://` links from calendar entries but keeps `https` ones, so
[CapWrap](https://github.com/mattsperrin/CapWrap) writes its task blocks with this link. The ids are
after the `#`, which browsers never send to the server.

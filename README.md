# Gatekeeper

This is a SMTP service that will listen for new messages, validate that the destinations are valid, and proxy the messages to their final inbox.

## TODO
- [ ] Listen for SMTP traffic
- [ ] Parse SMTP traffic
- [ ] Validate email against a "postmaster" api
- [ ] Proxy messages to their owner
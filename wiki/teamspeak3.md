# Teamspeak3

[Teamspeak3](https://www.teamspeak.com) is a voice-over-IP service.

## Server

A server can be setup via docker with the [teamspeak image](./docker-images/teamspeak.md).

## DNS

### Link Teamspeak3 to a subdomain

To link Teamspeak3 to one of your subdomains you need to add a [DNS](./dns.md)
SRV-record:

```txt
type: SRV
name: ts3 (or alternative subdomain)
service: _ts3
proto: UDP
TTL: <configure to your liking>
class: IN
priority: 0
weight: 5
port: 9987 (or your teamspeak3 port)
target: ts3.<domain>.<TLD>
```

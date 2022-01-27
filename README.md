# Host Deployment

This repository represents an Ansible role that's responsible for deploying a web host

## Specifications

This web host is able to host multiple websites on a single IP address (Multiple containers)

## Contents

- NGiNX Reverse Proxy server: NGiNX Container Hosted on ports 80 and 443, routes traffic based on domain name to different servers (Other containers)
- Let's Encrypt certificate generator: Container that generates and renews SSL certificates for the different websites hosted on the server

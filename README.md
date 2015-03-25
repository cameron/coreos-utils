# CoreOS Utils

Scripts to bootstrap a fresh CoreOS host (including Vagrant VMs):
- enable the daemon's remote API
- generate a TLS certificate and client/server keys for secure remote communication
- install unit files
  - e.g., skydock and skydns give containers DNS names like name.image.env.docker 

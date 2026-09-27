# Moltis stack

This repository contains the standalone Moltis Compose stack. Moltis is not
deployed on the Lighthouse host. The service stores its configuration under
`/var/lib/moltis`, uses the host Docker socket, and is intended to sit behind
the `moltis.yusoofsh.id` reverse proxy route defined in `compose.yaml`.

Copy `.env.example` to `.env` and set the password and provider credentials
before starting the stack. Keep the resulting `.env` out of version control.


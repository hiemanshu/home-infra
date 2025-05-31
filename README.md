# Talos setup

## To get talos to use tailscale, do this

After bootstrap, and before apps install, do this:
`talosctl patch mc -p @tailscale.patch.yaml`

Details on the patch here: https://github.com/siderolabs/extensions/tree/main/network/tailscale#usage

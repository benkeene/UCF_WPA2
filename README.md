# UCF_WPA2
NetworkManager config for UCF_WPA2 (WPA2 enterprise, peap, mschapv2, no cert)

# STEPS
In UCF_WPA2.nmconnection, perform the following:
  - set uuid equal to the output of `uuidgen`
  - set identity equal to your NID (ab123456)
  - set password equal to your NID password

Move UCF_WPA2.nmconnection to: `/etc/NetworkManager/system-connections/`

Restart NetworkManager - `sudo systemctl restart NetworkManager`


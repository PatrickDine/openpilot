# Research fork status

This is a source-review and offline-adaptation fork. It is **not a validated vehicle-software release or a comma four installation recommendation**.

## Source and branches

- Upstream: [leomondes/openpilot, Jeep branch](https://github.com/leomondes/openpilot/tree/jeep).
- Preserved source commit: `87c8337a398c1d185a5e39f9b47fa0d765858d1e`.
- `jeep` preserves that original source revision.
- `jeep-research` starts from the same revision and adds research-status documentation only. The original README, source, licensing and attribution are retained.

## Validation limits

The source declares a 2022 Jeep Renegade 4xe implementation with its own Jeep interface, controller and Panda safety mode. It has not been independently validated here on comma four or another target vehicle.

No complete build, installation, controller test or Panda safety validation has been performed for this fork. Offline received-message checks in a separate research project do not validate this controller, firmware or a deployment.

Before any deployment is considered, the target vehicle's state inputs, bus routing, firmware identification, hardware/software compatibility, and control/safety behavior need independent validation. This fork does not resolve missing inputs by changing vehicle selection or bypassing safeguards.

No installer, device-configuration change or vehicle-control test is provided by this research branch.

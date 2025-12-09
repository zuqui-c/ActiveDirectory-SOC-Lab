# Sysmon Modular Configuration (Reference)

For this project, I used Olaf Hartong’s Sysmon Modular configuration as the
base config for event logging and telemetry generation.

Original source:
- GitHub: https://github.com/olafhartong/sysmon-modular

I selected this config because it provides strong coverage for process creation,
network connections, registry modifications, and script execution — which
aligned with my goal of generating telemetry during RDP brute-force and Atomic
Red Team testing.

No ownership claimed — config is publicly available under original licensing.

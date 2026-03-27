# <Vendor> <Model> — IPMX Switch Recipe

## Summary
Brief description of what this configuration enables (e.g., “Baseline IPMX multicast operation with PTP support”).

## Tested Environment
- Switch Model:
- Firmware Version:
- Configuration Interface: (CLI / Web UI)
- Test Setup:
  - Number of endpoints:
  - Endpoint types (if known):

## Use Case
Describe the intended deployment scenario:
- IPMX baseline (no PTP)
- IPMX with PTP
- Mixed IPMX / ST 2110
- Other:

## Assumptions
List any assumptions:
- Layer 2 or Layer 3 network
- Dedicated or shared network
- Default VLAN or specific VLAN configuration

## Configuration Steps

### 1. Base Network Setup
Step-by-step instructions

### 2. Multicast Configuration
- IGMP Snooping:
- IGMP Querier:

### 3. PTP Configuration (if applicable)
- PTP profile:
- Boundary/Transparent clock settings:

### 4. QoS Configuration
- Priority mapping:
- Queue configuration:

### 5. Additional Settings (if applicable)
- Jumbo frames
- Storm control
- Energy-saving features (disabled if required)

## Validation
How to confirm correct operation:
- Expected behavior:
- Indicators (e.g., PTP lock, multicast flow, no packet loss)

## Known Limitations
List any observed constraints or caveats.

## Contributor Validation Statement
Describe how this configuration was validated:
(e.g., “Tested in lab with 4 IPMX endpoints using multicast video and PTP timing”)

## Notes
Optional clarifications. Keep factual and concise.

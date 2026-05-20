# Ara Mesh

Ara is a delay-tolerant, offline-first mesh sync SDK for applications that need shared state without central infrastructure.

Built for field operations where cell coverage is absent — teams share waypoints, logs, and positions across LoRa, MQTT, BLE, and UDP transports using conflict-free CRDT sync.

## SDKs

| Platform | Repo | Install |
|----------|------|---------|
| Go | [ara-sdk-go](https://github.com/ara-mesh/ara-sdk-go) | `go get github.com/ara-mesh/ara-sdk-go` |
| Android | [ara-sdk-android](https://github.com/ara-mesh/ara-sdk-android) | Maven: `com.aramesh:ara-sdk:v1` |

## Transports

| Transport | Throughput | Use case |
|-----------|-----------|----------|
| UDP LAN | Unconstrained | Local network / WiFi |
| MQTT | Unconstrained | WiFi or cellular via broker |
| Meshtastic LoRa | ~110 bytes/min sustained | Off-grid, no infrastructure |

## Documentation

[ara-mesh.github.io/ara-docs](https://ara-mesh.github.io/ara-docs)

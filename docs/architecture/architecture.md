# SignalForge Architecture

## Current High-Level Flow

Telemetry File

↓

PacketReader

↓

Packet

↓

Decoder

↓

DecodedPacket

↓

Writer

↓

Output (JSON / CSV / Parquet)

---

This architecture is currently under active design and will evolve during development.
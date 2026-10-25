# Architecture Book: James Watt AI ($JAMESWATT)
## Sui Move Object-Centric System & Invariant Specifications

### 1. Sui System Topology

```
+---------------------------------------------------------------------------------+
|                         James Watt AI Sui Autonomous Node                 |
+---------------------------------------------------------------------------------+
                                      |
         +----------------------------+----------------------------+
         |                                                         |
         v                                                         v
+-----------------------------+                           +-----------------------+
|  Rust Bitboard State Engine |                           | Sui Move DAG Engine   |
|  - 64-bit Non-Linear Conway |                           | - TreasuryCap<T>      |
|  - SplitMix64 Determinism   |                           | - Shared Object UID   |
|  - 10,000 Cycle Continuity  |                           | - MicroEscrowVault    |
+-----------------------------+                           +-----------------------+
         |                                                         |
         +----------------------------+----------------------------+
                                      |
                                      v
+---------------------------------------------------------------------------------+
|                       Model Context Protocol (MCP) Server                       |
|   - calculate_condenser_thermal_efficiency: Computes fuel saving percentage achieved by keeping main cylinder permanently hot while condensing in separate vessel                    |
|   - model_centrifugal_flyball_governor: Solves negative feedback angular speed equilibrium controlling steam throttle valve                    |
+---------------------------------------------------------------------------------+
                                      |
                                      v
+---------------------------------------------------------------------------------+
|                      NIST FIPS 203 / 204 Post-Quantum Vault                     |
|           [ML-KEM-768 Lattice Encap] <---> [ML-DSA-65 Digital Signature]         |
+---------------------------------------------------------------------------------+
```

### 2. State Invariants & Sui Move Execution
- **Blockchain**: Sui Object-Centric DAG Protocol
- **State Focus**: Thermodynamic Carnot Efficiency Delta & Flyball Feedback Invariant
- **Token Utility**: Turbine Rotational Speed Stabilization & Industrial Work Credit Settlement
- **Move Package**: `sources/launchpad_token.move`

### 3. Model Context Protocol Tools
1. `calculate_condenser_thermal_efficiency`: Computes fuel saving percentage achieved by keeping main cylinder permanently hot while condensing in separate vessel
2. `model_centrifugal_flyball_governor`: Solves negative feedback angular speed equilibrium controlling steam throttle valve

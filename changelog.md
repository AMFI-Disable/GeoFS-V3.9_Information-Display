# Changelog

All notable changes, cockpit telemetry gauges, and version releases for GeoFS-V3.9 Information Display are documented in this file.

---

## [2.0.1] - HUD Telemetry Readouts And Dynamic Badging

### Added
- **Color-Coded Telemetry Alerts**: Real-time threshold-based color coding for Vertical Speed (V/S), normal load factor (G-Force), and Angle of Attack (AOA).
- **Live Aircraft Identification**: Dynamic badge parsing active aircraft name, model, and simulator identifier.

### Fixed
- **Screen Resizing Geometry**: Repositions telemetry displays gracefully across browser window viewport adjustments.
- **Data Stream Throttling**: Regulated telemetry query cadence to avoid redundant DOM updates during high framerate flight.

---

## [2.0.0] - Integrated Cockpit Data Hub

### Added
- **Unified Navigation Hub**: Multi-tab interface consolidating flight metrics, navigation data, and addon shortcut toggles.
- **Glassmorphic Instrument Strip**: Modern heads-up telemetry ribbon displaying IAS, TAS, Mach, Altitude, and Heading.

---

## [1.0.0] - Initial Production Release

Initial release of the central cockpit information overlay for GeoFS.

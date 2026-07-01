# OrcaSlicer-profile-validator

This repository archives generated user preset snapshots from past OrcaSlicer releases. Each snapshot is produced from that release’s system profiles using OrcaSlicer_profile_validator --generate_presets, then preserved as a compatibility fixture.
The fixtures are intended to be validated against the current OrcaSlicer system profiles to catch backward compatibility regressions, especially renamed or removed parent presets, profile inheritance gaps, and stale compatibility references in older user presets.

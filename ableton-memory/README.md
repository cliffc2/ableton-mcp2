# Ableton Memory Skill Set

## Files

| File | Contents |
|------|----------|
| `plugins.md` | Full inventory of all VST3/VST/AUv2 plugins |
| `presets.md` | Custom presets and their parameter mappings |
| `master-chain.md` | Master chain template (8 slots) with default picks + alternatives |

## Commands Reference

### Load plugin onto track
```
POST /api/command {"command": "load_instrument_or_effect", "params": {"track_index": N, "uri": "<URI>"}}
```

### Load to master
```
POST /api/command {"command": "load_item_to_master", "params": {"uri": "<URI>"}}
```

### Set parameter
```
POST /api/command {"command": "set_device_parameter", "params": {"track_index": N, "device_index": N, "parameter_index": N, "value": F}}
```

### Get parameters
```
POST /api/command {"command": "get_device_parameters", "params": {"track_index": N, "device_index": N}}
```

## Track Indexing (0-based)
- Track 1 = index 0, Track 2 = index 1, etc.
- Device 0 = first device on track

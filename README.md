# OnePlus Device Kernel Action

GitHub Action for automated OnePlus device kernel updates.

## Supported Devices
- OnePlus 13

## Features
- Automated firmware updates
- Device-specific configuration
- Artifact cleanup
- Scheduled execution

## Usage
Add to your workflow:
```yaml
- name: OnePlus Action
  uses: iniabi/action_oneplus@main
  with:
    device_model: 'OnePlus13'
```

## Workflows
| Workflow | Description |
|----------|-------------|
| `Cleanup.yml` | Cleans up old artifacts and logs |
| `OnePlus13.yml` | Manages OnePlus 13 kernel updates |
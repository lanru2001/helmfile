# Key Commands

# Install Helmfile:
```bashbrew install helmfile     # macOS
```
# or download binary from GitHub releases
Add Helm repos and sync dependencies:
```
bashhelmfile repos
```
# Preview what will be deployed (diff):
```
bashhelmfile --environment dev diff
helmfile --environment qa diff

helmfile --environment dev sync

helmfile --environment qa sync

helmfile --environment dev destroy

helmfile --environment dev status
```

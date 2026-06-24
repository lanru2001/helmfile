# Key Commands

# Install Helmfile:
```
brew install helmfile     
helmfile repos
```
# Preview what will be deployed (diff):
```
helmfile --environment dev diff

helmfile --environment qa diff

helmfile --environment dev sync

helmfile --environment qa sync

helmfile --environment dev destroy

helmfile --environment dev status
```

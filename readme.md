## Add the unsigned rolling repo
```
echo 'deb [trusted=yes] https://github.com/Ackerman-00/devuan-nexus/releases/download/rolling/ ./' \
  | sudo tee /etc/apt/sources.list.d/devuan-nexus.list
```

## Update and verify
```
sudo apt-get update
```

## Example (package install)

```
sudo apt-get install niri-git
```

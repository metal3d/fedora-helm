# Helm package for Fedora

See Helm project here: https://tytel.org/helm/

This repository is the starting point to use metal3d/helm Copr reposity. If you want to install Helm or the LV2 plugin, you may first enable the repository:

```
sudo dnf copr enable metal3d/helm
```

Then choose wich package to install

- "helm" package is the standalone version
- "lv2-helm" is the plugin to be able to use it as LV2 plugin (eg. in Ardour, Rosegarden, and so on)

```
sudo dnf install helm
# and / or
sudo dnf install lv2-helm
```



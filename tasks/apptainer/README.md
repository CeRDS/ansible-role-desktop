```bash
sudo apt-get -y install \
 uidmap \
 squashfuse \
 fuse2fs \
 fuse-overlayfs

wget https://github.com/apptainer/apptainer/releases/download/v1.1.3/apptainer_1.1.3_amd64.deb
sudo dpkg -i ./apptainer_1.1.3_amd64.deb
```

```console
$ sudo dpkg -i ./apptainer_1.1.3_amd64.deb 
Selecting previously unselected package apptainer.
(Reading database ... 245839 files and directories currently installed.)
Preparing to unpack ./apptainer_1.1.3_amd64.deb ...
Unpacking apptainer (1.1.3) ...
dpkg: dependency problems prevent configuration of apptainer:
 apptainer depends on uidmap; however:
  Package uidmap is not installed.
 apptainer depends on squashfuse; however:
  Package squashfuse is not installed.
 apptainer depends on fuse2fs; however:
  Package fuse2fs is not installed.
 apptainer depends on fuse-overlayfs; however:
  Package fuse-overlayfs is not installed.

dpkg: error processing package apptainer (--install):
 dependency problems - leaving unconfigured
Processing triggers for man-db (2.10.2-1) ...
Errors were encountered while processing:
 apptainer
```

# Parallels-Tools-Linux-kernel-5.0
Update for Parallels Tools kernel 5.0. For full working Shared Folder:
- Launch Terminal (gnome-terminal) 

```shell
cd Parallels-Tools-Linux-kernel-5.0
sudo chmod 777 * -Rv
```

- For Disk-Share 

  ```shell
  sudo chmod +x /usr/bin/prlfsmountd && sudo reboot
  ```
- For Ctrl-Tab Issue run
```shell
sudo rm -rf /usr/share/gnome-shell/extensions/coherence-gnome-shell@parallels.com
```

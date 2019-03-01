## ansible-role-mounts

Just easy way to add additional static mounts to fstab

#### Variables

```
static_mounts:
 - { path: "/lustre/mgt", fstype: "lustre", src: "/dev/mapper/vgroot-lv_mgt" }
```


# vm-sync
A tool for syncing remote disk/image to local disk/image and reset cloud-init config via chroot

Usage vm-transfer:
```
vm-transfer -H <hypervisor_address> -S <source_path> -T <target_path> -K <path_to_sshkey>

Available options:
  --hypervisor | -H : Hypervisor address or hostname.
  --spath      | -S : Source path for the data to be transferred.
  --tpath      | -T : Openstack volume UUID for the target device.
  --sshkey     | -K : SSH key path for authentication.
  --callback   | -C : URL to GET on success completion.
```

syncStatus will exit with code 69 if there is active job running, when completed it will exit with 0.

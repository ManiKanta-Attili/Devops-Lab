### Issue 1

vim package missing

### Reason

RHEL Minimal installs vim-minimal only.

### Resolution

Installed vim-enhanced.

### Verification

rpm -q vim-enhanced



### Issue 2

Duplicate machine-id after cloning.

### Cause

Virtual machine cloned from a template.

### Resolution

Removed `/etc/machine-id` and regenerated it using:

systemd-machine-id-setup

### Verification

Compared machine-id values across all servers.

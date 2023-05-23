# kubeadm installation error

- Get:4 https://packages.cloud.google.com/apt kubernetes-xenial InRelease [8993 B]
- Err:4 https://packages.cloud.google.com/apt kubernetes-xenial InRelease
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY B53DC80D13EDEF05
  Reading package lists... Done
- W: GPG error: https://packages.cloud.google.com/apt kubernetes-xenial InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY B53DC80D13EDEF05
- E: The repository 'http://apt.kubernetes.io kubernetes-xenial InRelease' is not signed.
- N: Updating from such a repository can't be done securely, and is therefore disabled by default.
- N: See apt-secure(8) manpage for repository creation and user configuration details.
  
# Solution
https://github.com/kubernetes/release/issues/2862#issuecomment-1557620921

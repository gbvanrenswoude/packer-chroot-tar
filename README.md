# packer-chroot-tar
packer-chroot-tar

Tars up disk part of an AMI. Uploads it to Artifactory.
From there, pull, untar, ovr disk and create AMI.
(Pull based encrypted AMI propagation)


Solves large scale mass AMI sharing if encryption is mandatory in all phases of the process.
(discover an encrypted AMI to begin with)

# gcloud-ssh

This is a wrapper script for `gcloud compute ssh`.

It helps you to:

1. Fuzzy search a project
2. Fuzzy search a instance
3. SSH connect to the instance

By default, it uses IAP tunneling and a key with an expiration datetime to connect to the instance.

You need to have the gcloud SDK installed and be logged into your account to use this script.

# srsn overlay

This is a testing overlay for funtoo linux meant to be used as local overlay for ebuild modification

## setup

Follow the guide of [Local Overlay] (https://www.funtoo.org/Local_Overlay) to setup local overlay.
And use the following command to link the overlay config file to repos.conf

```sh
$ ln -s /var/git/overlay/srsn_overlay/srsn_overlay.conf /etc/portage/repos.conf/srsn_overlay.conf
```


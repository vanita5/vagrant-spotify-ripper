# vagrant-spotify-ripper

Made with :heart: for [pertinaxo](https://twitter.com/pertinaxo)

## Installation

1. Install [Virtualbox](https://www.virtualbox.org/)
2. Install [Vagrant](https://www.vagrantup.com/downloads.html)

## Usage

Download an application key file spotify_appkey.key from https://devaccount.spotify.com/my-account/keys/ 
(requires a Spotify Premium Account) and move the file to the 'data/' directory.

```bash
$ vagrant up
[...]
$ vagrant ssh
vagrant@127.0.0.1's password: vagrant

vagrant@vagrant-ubuntu-trusty-64:/vagrant_data$ spotify-ripper --fail-log rip_fail.log -u <username> -p <password> spotify:user:eliah94:playlist:6jinO48gLLNQDS7v02Xf48
```

# blobs

You can find the GoCD .zips here:

* [go-server](http://download01.thoughtworks.com/go/13.4.1/ga/go-server-13.4.1-18342.zip)
* [go-agent](http://download01.thoughtworks.com/go/13.4.1/ga/go-agent-13.4.1-18342.zip)

The `git` and `openjdk` blobs can be grabbed from
[cf-release](https://github.com/cloudfoundry/cf-release).

```
bosh add blob go-agent-13.4.1-18342.zip gocd
bosh add blob go-server-13.4.1-18342.zip gocd
bosh add blob git-1.7.11.2.tar.gz git
bosh add blob openjdk-1.7.0_51.tar.gz openjdk
```

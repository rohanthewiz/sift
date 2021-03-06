# sift

A fast and powerful open source alternative to grep.

Please go to [sift-tool.org](https://sift-tool.org) for more information.


## Installation

### Download Binaries
You can download binaries for the current version at https://sift-tool.org/download.

sift is available for Linux, Windows, OS X and *BSD.


### Install from Package Repositories

#### Arch Linux
Download and install the binary from http://sift-tool.org/download:

```sh
$ yaourt -S sift-bin
```

Or build and install sift from source at https://github.com/svent/sift:

```sh
$ yaourt -S sift
```

#### OS X

Using [Homebrew](http://brew.sh/):

```sh
$ brew install sift
```

### Install with Working Go Environment

If you have a working go environment, you can install sift using "go get":

```go get github.com/svent/sift```


## Contributing

### Feature Requests
If there is a feature or option you would like to see in sift,
please open an issue and describe what you are missing.
Where possible, please include an example (input file,
expected output etc.) to better convey your idea.

### Bugs / Unexpected Behavior
If you found a bug, please check the open issues and the
[limitations and restrictions](https://sift-tool.org/docs)
described in the documentation.
If you cannot find any documentation about it, please open a new issue,
name the sift version you used and describe the steps to reproduce the problem.

### Pull requests
Please do not send pull requests and open an issue instead as
accepting substantial contributions cannot be done correctly without some
[legal](http://producingoss.com/en/copyright-assignment.html)
[hassle](https://en.wikipedia.org/wiki/Contributor_License_Agreement).
Moreover, this allows me to consider already planned features while implementing
smaller changes.


## License

Copyright (C) 2014-2016 Sven Taute

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.


# Autopack

## Description

### What is it?

Autopack is a small Bash script written to expedite the process of cleaning, compressing, and sending files over scp.

### Why did I make it?

This is a personal project but may be of use to anyone looking to compress and send files overs scp quickly. In particular, this was designed to assist in future projects during my ComS 327 at Iowa State University. 

## Getting Started

### Prerequisites

##### Windows (Cygwin)

[Tutorial I Used](http://www.catonmat.net/blog/windows-through-ssh/)
1. Download and [install Cygwin](https://www.cygwin.com/install.html) (making sure to include OpenSSH and Cygrunsrv in your package manager)
2. "Start Cygwin and run `ssh-host-config` to configure ssh"
3. "Run `cygrunsrv -S sshd` to start sshd as a Windows service"

### Download and Run

1. `git clone https://github.com/JamKelley22/Autopack.git`
2. `cd Autopack`
3. `./autopack` 
* *Note* Running Autopack with < 3 or > 5 arguments will show the format Autopack expects as well as a couple use cases

## Authors

* **Jameel Kelley** - [Github](https://github.com/JamKelley22) | [Website] (http://www.public.iastate.edu/~jkelley/)

## Acknowledgments

* [README Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [Semantic Versioning](http://semver.org/spec/v2.0.0.html)
* [OpenSSH + Cygrunsrv](http://www.catonmat.net/blog/windows-through-ssh/)
* [Color Output](https://stackoverflow.com/questions/5947742/how-to-change-the-output-color-of-echo-in-linux)
* [SCP](http://www.hypexr.org/linux_scp_help.php)
* [Bash Guide](https://www.panix.com/~elflord/unix/bash-tute.html)

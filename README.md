# chef-roswell
[![Build Status](https://circleci.com/gh/Rudolph-Miller/chef-roswell.svg?style=shield)](https://circleci.com/gh/Rudolph-Miller/chef-roswell)

- Chef cookbook for [Roswell](https://github.com/snmsts/roswell)
- [Roswell](https://github.com/snmsts/roswell) is the project of installing Common Lisp and setting up everything just work is still difficult and you have to learn some tips.
- Chef-roswell install ros itself, setup roswell, and install SBCL of the specific version.

## Attribues
- branch(default: "release"): Branch of Roswell.
- user(default: nil): User to install Roswell
- prefix(default: "/usr/local"): Prefix for ./configure
- version(default: nil): Version of SBCL

## Author of Roswell
SANO Masatoshi (snmsts@gmail.com)

## Author
Rudolph Miller (chopsticks.tk.ppfm@gmail.com)

## License
MIT

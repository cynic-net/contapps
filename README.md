contapps - Containerized Applications
=====================================

This repo contains some tools and configurations to help Docker help
you in your daily life.

All command-line tools you might use in daily work are in `bin/` or
are symlinked from there. This allows you to add that to your path
or clone this under `~/.home/` and use [`dot-home`] to add them to
your `~/.local/bin/` directory.

Tools
-----

* [`dent/`]: "Docker ENTer" tool to run a shell or command in a
  container. It can automatically create containers and images. It's
  particularly helpful with persistent interactive containers with
  non-root logins used for testing, sandboxed terminal sharing, etc.



<!-------------------------------------------------------------------->
[`dent/`]: dent/
[`dot-home`]: https://github.com/dot-home/_dot-home

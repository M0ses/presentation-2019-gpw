<!-- .slide: data-state="section-break" id="tips-and-tricks-for-perl-developers" data-timing="10s" -->
# Tips and Tricks for Perl developers


<!-- .slide: data-state="normal" id="public-vs-private" data-timing="60s" -->
# Public vs. Private

## build.o.o - The reference platform

* https://build.opensuse.org - build your open source software
  * `osc branch devel:languages:perl <PKG> <MY_REPO>`

## OBS@Home - Private instances

* https://openbuildservice.org/download/
  * Choose your favourite virtualization
  * `osc branch opensuse.org:<OFFICIAL_PACKAGE> <MY_HOME_REPO>`


<!-- .slide: data-state="normal" id="pre-packaged-cpan-modules-in-obs" data-timing="60s" -->
# Pre-packaged CPAN Modules in OBS

## devel:languages:perl

* building CPAN Packages

## devel:languages:perl:CPAN-(A-Z)

* Staging projects for devel:languages:perl


<!-- .slide: data-state="normal" id="perl-packaging-guidelines" data-timing="60s" -->
## Perl Packaging Guidelines

How to package perl in my favourite distribution.

* https://en.opensuse.org/openSUSE:Packaging_Perl
* https://fedoraproject.org/wiki/Packaging:Perl
* https://wiki.debian.org/PerlFAQ


<!-- .slide: data-state="normal" id="packaging-cpan-manually" data-timing="60s" -->
# Packaging CPAN manually

## cpanspec - Mind the gap

* [Fedora - cpanspec](https://fedoraproject.org/wiki/Perl/cpanspec)
* [openSUSE - cpanspec](https://en.opensuse.org/openSUSE:Packaging_Perl#cpanspec)
* [openSUSE - cpanspec_obs](https://en.opensuse.org/openSUSE:Packaging_Perl#cpanspec_obs)

## cpan2dist?

* [CPANPLUS based cli-tool to package multiple distributions](https://en.opensuse.org/openSUSE:Packaging_Perl#cpan2dist)


<!-- .slide: data-state="normal" id="building-images-and-containers" data-timing="60s" -->
## Building images/containers

* kiwi
* docker
* podman 

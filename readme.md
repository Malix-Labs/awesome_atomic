# Awesome Immutable [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> image-based Linux desktops

This guide is for people looking for information on running image-based Linux distributions and associated tools and goodies. Note that these systems aren't totally immutable, but no one would ever click on an `awesome-anti-hysteresis` list.
For this list server distributions like CoreOS and Flatcar are not included, this is intended for users who have been using traditional linux distributions on their desktop and need consolidated information. 

## Introductory Blogs

These should be enough to get you started:

- [“Immutable” → reprovisionable, anti-hysteresis](https://blog.verbum.org/2020/08/22/immutable-%E2%86%92-reprovisionable-anti-hysteresis/)- Colin Walters
- [The Birth of the Kubic Desktop](https://rootco.de/2017-11-16-hackweek-2017-conclusion/) - Richard Brown
- [Project Atomic + Docker: A post package world?](https://blog.verbum.org/2014/07/10/project-atomic-docker-a-post-package-world/) - Colin Walters - it's an older post but it checks out

## Talks and Videos

- [Linux Downtime - Episode 39](https://www.youtube.com/watch?v=CiyjZwd4Jrs) - I went on this podcast to talk about this list, image based desktops, flatpaks, and all that stuff. If you are lost start here! 
- [Kubic - openSUSEs Container Starship](https://speakerdeck.com/sysrich/kubic-opensuses-container-starship) - Richard Brown
- [openSUSE MicroOS](https://www.youtube.com/watch?v=nIwqzGbX-oc) - Richard Brown
- [Can MicroOS Desktop be your Daily Driver?](https://www.youtube.com/watch?v=6F7iCntjWB8) - Dario Faggioli
- [MicroOS Desktop: The Road to Daily Driving](https://www.youtube.com/watch?v=cZLckDUDYjw) - Richard Brown
- [19 talks on Fedora Silverblue and related technologies](https://silverblue.fedoraproject.org/elsewhere) - many recorded talks here, too many to list here, but worth it! 
- [ostree CLI for OS management](https://www.youtube.com/watch?v=B0xvrXkEwr4) - Denis Pynkin
- [Let's try Fedora Silverblue](https://www.youtube.com/watch?v=-hpV5l-gJnQ) - Adam Šamalik
- [How Nix and NixOS Get So Close to Perfect](https://christine.website/talks/nixos-pain-2021-11-10) - Xe
- [Fedora Silverblue: is this the FUTURE of Linux? - Project of the Month](https://www.youtube.com/watch?v=5TjIzUJtF-I) - older video but an excellent review of the major components
- [Learning the difference between Red Hat distributions and what Fedora Silverblue is](https://www.youtube.com/watch?v=U8U2pEyeI6E) - JJ Asghar
- [Linux After Dark – Episode 07](https://linuxafterdark.net/linux-after-dark-episode-07/) - the hosts try silverblue and did an episode on their experiences. 
- [Fedora Silverblue: An Immutable OS](https://www.youtube.com/watch?v=K-FqVWFh01w)
- [What's new in (rpm-)ostree - 2022 edition! - DevConf.CZ 2022](https://www.youtube.com/watch?v=lEDihzhsIjE)
- [Fedora 36 Silverblue: The 3 Guiding Principles for a Successful Experience](https://www.youtube.com/watch?v=zhBnuVVdd6Y) - excellent introduction video that covers lots of tips and tricks.

## Distributions

The Future is Now(tm), try one of these today!

- [Fedora Silverblue](https://silverblue.fedoraproject.org/) - Silverblue is a variant of Fedora Workstation. It looks, feels and behaves like a regular desktop operating system, and the experience is similar to what you find with using a standard Fedora Workstation.
  - [Development on Fedora Silverblue and Fedora Kinoite](https://tim.siosm.fr/blog/2021/12/10/fedora-kinoite-silverblue-dev-guide/#development-using-flatpak)
  - [Setting yourself up for success before trying Fedora Silverblue](https://www.ypsidanger.com/setting-yourself-up-for-success-before-moving-to-fedora-silverblue/)
  - [Day-to-day differences between Fedora Silverblue and Ubuntu](https://www.ypsidanger.com/day-to-day-advantages-of-fedora-silverblue/)
- [Fedora Kinoite](https://kinoite.fedoraproject.org/) - Similar to Silverblue, but based on KDE
- [openSUSE MicroOS](https://microos.opensuse.org/) - a variant of openSUSE Tumbleweed and serves as a base of openSUSE Kubic, a Container as a Service platform.
- [NixOS](https://nixos.org/) - a Linux distribution based on Nix package manager
  - [awesome-nix](https://github.com/nix-community/awesome-nix) - A curated list of the best resources in the Nix community
  - Note: The nix community has both an OS and a packaging system and is already large and vibrant, I can't do it justice so just use the list above to dive in
- [Guix System](https://guix.gnu.org/) - a Linux distribution based on the Guix package manager based on Nix
- [EndlessOS](https://endlessos.com/home/) - A Debian derivative distribution with a read-only root filesystem managed by OSTree and Flatpak for application delivery and update
- [ChromeOS Flex](https://chromeenterprise.google/os/chromeosflex/) - the cloud-first, fast, easy-to-manage, and secure Chrome OS for PCs and Macs. 
  - [ChromiumOS](https://www.chromium.org/chromium-os/chromiumos-design-docs/filesystem-autoupdate/) - Good design document on how Chromium implements its autoupdate mechanism
- [rlxos](https://rlxos.dev/) - A immutable, independent general-purpose distribution with primary focus on single file per application.
- [carbonOS](https://carbon.sh/) - An open operating system designed from the ground-up to be intuitive and robust. The [blog post](https://carbon.sh/blog/2021-11-25-release.html) explains the goals
- [astOS](https://github.com/CuBeRJAN/astOS) - An immutable Arch based distribution utilizing btrfs snapshots.

## Toolboxes

There historically have been a few versions of "toolbox", and we're probably to a point where it's more of a class of software than an individual project. 
I classify toolboxes as "A terminal front end to container runtimes focusing on transparent ease of use of container images".
Someone smarter please make a better definition. 

- [Toolbx](https://github.com/containers/toolbox) - Tool for containerized command line environments on Linux
  - [Toolbx Tuner](https://github.com/13hannes11/toolbx-tuner) - Toolbx Tuner is a tool to improve the experience with toolbx.
- [Distrobox](https://github.com/89luca89/distrobox) - Tool for containerized command line environments on Linux, distribution agnostic, supports a wide variety of containers , works both with podman and docker - This is a great tool to start with on your existing distro to learn working with day-to-day container workflows.
- [nxbox](https://github.com/refi64/nsbox) - Pet container manager based on systemd-nspawn and supporting DBus and desktop files.
- [coretoolbox](https://github.com/cgwalters/coretoolbox) - Toolbx alternative in rust with a focus on container builds. (Older project, appears unmaintained, but if I don't include rust stuff people will get upset :smiley:)

## Core Tools

Things that are the building blocks for all the stuff we're talking about here.

- [podman](https://podman.io/) - Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System.
  - [gnome-shell-extension-containers](https://github.com/rgolangh/gnome-shell-extension-containers) - This neat extension lets you see what containers you have, start/stop/restart, pause, and shell into them right from the notification area.
  - [Podman Desktop](https://github.com/containers/podman-desktop) - Manage different container engines from a single UI and tray icon
  - [Podman desktop companion](https://iongion.github.io/podman-desktop-companion/) - graphical management of your desktop containers
  - [Pods](https://github.com/marhkb/pods) - a podman desktop application (formely known as Symfony)
- [Flatpak](https://flatpak.org/) - a utility for software deployment and package management for Linux. It is advertised as offering a sandbox environment in which users can run application software in isolation from the rest of the system.

## Lower level tools

Most of us will not use these tools directly, but useful for developers:

- [libostree](https://github.com/ostreedev/ostree) - Operating system and container binary deployment and upgrades 
  - [Upcoming experimental features in rpm-ostree](https://coreos.github.io/rpm-ostree/experimental/)
  - [flatpak-ostree-dedup-stats.py](https://gist.github.com/powpingdone/001a46aa7db190b9c935f71c6091eb71) - script to show you how well the ostree deduplication is working, this one is neat
  - [apt2ostree](https://github.com/stb-tester/apt2ostree) - apt2ostree is used for building Debian/Ubuntu based ostree images. It performs the same task as debootstrap/multistrap but the output is an ostree tree rather than a rootfs in a directory.
- [Endless OSTree Builder](https://github.com/dbnicholson/deb-ostree-builder) - Stripped down Endless ostree builder for Debian 
- [osbuilder](https://www.osbuild.org/) - Build-Pipelines for Operating System Artifacts
  - [How to: Image Builder + OSTree + Anaconda](https://www.osbuild.org/news/2020-06-01-how-to-ostree-anaconda.html)  
  - [osbuild user guide](https://www.osbuild.org/guides/user-guide/user-guide.html)

## Integration Resources

aka. duct tape.

- [Integrate VSCode and Distrobox](https://distrobox.privatedns.org/posts/integrate_vscode_distrobox.html) 
- [silverblue-nix](https://gitlab.com/ahayzen/silverblue-nix) - Andrew Hayzen's steps for getting nix working on Fedora Silverblue. 
- [Toolbox Visual Studio Code Integration](https://github.com/owtaylor/toolbox-vscode) -  Toolbox Visual Studio Code integration
- [silverblue-tools](https://github.com/A6GibKm/silverblue-tools) - Collection of scripts for silverblue related technologies  

## Configs from the Community

OSTree based systems allow for composable derivative distributions.
If you're automating the config on systems like this please PR your config to share:

- [workstation-ostree-config](https://pagure.io/workstation-ostree-config) - Manifests for rpm-ostree based Fedora variants (start here!)
- [ostree-pitti-workstation](https://github.com/martinpitt/ostree-pitti-workstation) - Fedora minimal sway developer desktop
- [vauxite](https://github.com/hyperreal64/vauxite) - This is an rpm-ostree-based Fedora Xfce desktop.
- [zepyros-dev's config](https://github.com/zephyros-dev/silverblue-config)
- [JayDoubleau's config (ansiblue)](https://github.com/JayDoubleu/ansiblue)
- [castrojo's config (ublue)](https://github.com/castrojo/ublue) - A familiar(ish) Ubuntu desktop for Fedora Silverblue. 
- [ansible-silverblue](https://github.com/j1mc/ansible-silverblue) - Jim Campbell's ansible playbook for silverblue
- [Sodalite: A Pantheon Experience for Silverblue](https://github.com/electricduck/sodalite)

## Tips

- [Using Automatic Updates on Fedora Silverblue](https://miabbott.github.io/2018/06/13/rpm-ostree-automatic-updates.html)

## Miscellaneous

Things that don't fit anywhere else but might be useful reference material 

- [Introducing flox - Nix for simplicity and scale](https://discourse.nixos.org/t/introducing-flox-nix-for-simplicity-and-scale/11275)- Barry Plunkett


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first. We need more nix resources so if you have good ones please consider PRing one.

If you don't know how to use git then file an issue and leave a link, I'll integrate it into the list!

# Fun Stats
  
  ![Alt](https://repobeats.axiom.co/api/embed/a8b746311ae37bead7de66fb5e735b146cefb0e8.svg "Repobeats analytics image")


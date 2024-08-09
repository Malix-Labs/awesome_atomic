# [Awesome Atomic](https://github.com/Malix-off/awesome_atomic) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome Atomic Illustration](https://img.freepik.com/premium-photo/3d-illustration-atom-with-atom-computer-circuit-board-background_779834-6339.jpg)](https://images.app.goo.gl/S1xCGtUmMfXGr5N96)

An awesome curated knowledge-base about atomic systems

## Introductory Blogs and Publications

These should be enough to get you started:

- [“Immutable” → reprovisionable, anti-hysteresis](https://blog.verbum.org/2020/08/22/immutable-%E2%86%92-reprovisionable-anti-hysteresis/) - Colin Walters
- [The Birth of the Kubic Desktop](https://rootco.de/2017-11-16-hackweek-2017-conclusion/) - Richard Brown
- [Project Atomic + Docker: A post package world?](https://blog.verbum.org/2014/07/10/project-atomic-docker-a-post-package-world/) - Colin Walters - it's an older post but it checks out
- [Immutable Operating Systems: A Survey](https://www.researchgate.net/publication/370528248_Immutable_Operating_Systems_A_Survey) - Sebastian Böhm and Guido Wirtz, University of Bamberg, Germany - A short scientific publication that conceptualizes, defines, and outlines use cases and limitations of Immutable Operating Systems.

## Talks and Videos

- [The Fedora Podcast - Episode 30](https://www.youtube.com/watch?v=cHYyGVOae84) - Jorge Castro and Timothee Ravier talk about Silverblue and the future of Immutable Desktops.
- [Linux Downtime - Episode 39](https://www.youtube.com/watch?v=CiyjZwd4Jrs) - I went on this podcast to talk about this list, image based desktops, flatpaks, and all that stuff. If you are lost start here!
- [The Read Only Scenario](https://linuxunplugged.com/468) - An excellent introduction to these kinds of desktops
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
- [Linux After Dark – Episode 07](https://linuxafterdark.net/linux-after-dark-episode-07/) - the hosts tried silverblue and did an episode on their experiences.
- [Fedora Silverblue: An Immutable OS](https://www.youtube.com/watch?v=K-FqVWFh01w)
- [What's new in (rpm-)ostree - 2022 edition! - DevConf.CZ 2022](https://www.youtube.com/watch?v=lEDihzhsIjE)
- [Fedora 36 Silverblue: The 3 Guiding Principles for a Successful Experience](https://www.youtube.com/watch?v=zhBnuVVdd6Y) - excellent introduction video that covers lots of tips and tricks.
- [How we build and maintain Kairos](https://www.youtube.com/watch?v=XD5nfMf59v4) - Mauro Morales, FOSDEM 2023
- [Meet Kairos, an OSS project building the immutable Kubernetes edge](https://www.youtube.com/watch?v=kiDQujibz2k) - Ettore Di Giacinto and Nic Vermande

## Distributions

The Future is Now™, try one of these today!

- [Fedora Atomic](https://fedoraproject.org/atomic-desktops/) - The official atomic editons of Fedora
	- Useful Documentation
		- [Ostree Native Container](https://fedoraproject.org/wiki/Changes/OstreeNativeContainerStable) - Spec on Silverblue moving to a native OCI container model (Huge change)
		- [Development on Fedora Silverblue and Fedora Kinoite](https://tim.siosm.fr/blog/2021/12/10/fedora-kinoite-silverblue-dev-guide/#development-using-flatpak)
		- [Setting yourself up for success before trying Fedora Silverblue](https://www.ypsidanger.com/setting-yourself-up-for-success-before-moving-to-fedora-silverblue/)
		- [Day-to-day differences between Fedora Silverblue and Ubuntu](https://www.ypsidanger.com/day-to-day-advantages-of-fedora-silverblue/)
	- Spins
		- [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue) - An atomic-based Fedora based on the GNOME desktop environment
		- [Fedora Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/) - An atomic-based Fedora based on KDE Plasma desktop enviroment
		- [Fedora Sway Atomic](https://fedoraproject.org/atomic-desktops/sway) - An atomic-based Fedora based on the Sway tiling window manager
		- [Fedora Budgie Atomic](https://fedoraproject.org/atomic-desktops/budgie) - An atomic-based Fedora based on Budgie desktop environment
		- [Fedora CoreOS](https://fedoraproject.org/coreos/) - An atomic-based Fedora focused on servers
	- Related Projects
		- [Universal Blue](https://universal-blue.org/) - An organization dedicated to build and distribute cloud-native OSTree OCI images originally based on Fedora Atomic. [list of source images](https://github.com/orgs/ublue-os/packages), [list of end-user images](https://universal-blue.org/#images)
			- [Bazzite](https://github.com/ublue-os/bazzite/) - An Universal Blue OCI image focused on Desktop Gaming, based on [Fedora Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/); the gold standard of atomic desktop linux gaming
			- [Bluefin](https://projectbluefin.io/) - An Universal Blue OCI image focused on general and development use, based on [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue)
			- [Aurora](https://getaurora.dev/) - An Universal Blue OCI image focused on general and development use, based on [Fedora Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/)
			- [uCore](https://projectucore.io/) - An Universal Blue OCI image focused on server use, based on [Fedora CoreOS](https://fedoraproject.org/coreos/)
- openSUSE Atomic
	- [openSUSE MicroOS](https://microos.opensuse.org/) - An atomic variant of openSUSE for servers that serves as a base of openSUSE Kubic, a Container as a Service platform.
	- [openSUSE Aeon](https://aeondesktop.org) - An atomic variant of openSUSE with the GNOME desktop environment,featuring containers with Distrobox.
	- [openSUSE Kalpa](https://en.opensuse.org/Portal:Kalpa) - An atomic variant of openSUSE with the KDE Plasma desktop environment,featuring containers with Distrobox.
- [NixOS](https://nixos.org/) - a Linux distribution based on Nix package manager
	- [awesome-nix](https://github.com/nix-community/awesome-nix) - A curated list of the best resources in the Nix community
	- Note: The nix community has both an OS and a packaging system and is already large and vibrant, I can't do it justice so just use the list above to dive in
- [SnowflakeOS](https://snowflakeos.org/) - A [NixOS](https://nixos.org/) based Linux distribution focused on beginner friendliness and ease of use.
- [Guix System](https://guix.gnu.org/) - a Linux distribution based on the Guix package manager based on Nix
- [RDE](http://trop.in/rde/) - Developer and power user friendly GNU/Linux distribution based on GNU Guix functional package manager
- [EndlessOS](https://endlessos.com/home/) - A Debian derivative distribution with a read-only root filesystem managed by OSTree, and is Flatpak-only for application delivery and update. One of the easiest (but constraining) linux distribution
- [ChromiumOS](https://www.chromium.org/chromium-os/chromiumos-design-docs/filesystem-autoupdate/) - Good design document on how Chromium implements its autoupdate mechanism
	- [ChromeOS Flex](https://chromeenterprise.google/os/chromeosflex/) - the cloud-first, fast, easy-to-manage, and secure Chrome OS for PCs and Macs.
- [rlxos](https://rlxos.dev/) - A immutable, independent general-purpose distribution with a primary focus on single file per application.
- [VanillaOS](https://vanillaos.org/) - Vanilla OS is a Debian Sid Linux-based Point Release distribution that receives updates at the right time without sacrificing security and functionality.
- [Nitrux OS](https://nxos.org/) ([2.6.0](https://nxos.org/changelog/release-announcement-nitrux-2-6-0/)+) - A Debian-based Linux distribution that features [NX Desktop](https://nxos.org/english/nxd/) and the [MauiKit Applications](https://mauikit.org/) suite.
- [blendOS](https://blendos.co/) - blendOS is an operating system that seamlessly blends all your Linux distributions into one.
- [Kairos](https://github.com/kairos-io/kairos) - The immutable Linux meta-distribution for edge Kubernetes.
- [Mocaccino Desktop](https://www.mocaccino.org/docs/desktop/) - A Gentoo-based distribution (derived from Sabayon) oriented towards Desktop systems.
- [ChimeraOS](https://chimeraos.org/) - A Steam Big Picture based couch gaming OS
- [Arkane Linux](https://arkanelinux.org/) - Arch based immutable distro which uses [Arkdep](https://github.com/arkanelinux/arkdep)

## Toolboxes

There historically have been a few versions of "toolbox", and we're probably at a point where it's more of a class of software than an individual project.
I classify toolboxes as "A terminal front end to container runtimes focusing on transparent ease of use of container images".
Someone smarter please make a better definition.

- [Toolbx](https://github.com/containers/toolbox) - Tool for containerized command line environments on Linux
	- [Toolbx Tuner](https://github.com/13hannes11/toolbx-tuner) - Toolbx Tuner is a tool to improve the experience with toolbx.
	- [Toolbx Images](https://github.com/toolbx-images/images) - Community maintained container images to use with toolbx  (Check these out if you need other distros outside the default Fedora ones)
	- [toolbox-images](https://github.com/akdev1l/toolbox-images) - a collection of container images for usage with the toolbox command. This is an attempt at providing more feature parity with regard to toolboxes for distributions other than Fedora.
	- [Toolbox GUI](https://github.com/Dvlv/toolbox-gui) - A graphical interface for interacting with Toolbox, written with GTK3 and Python
- [Distrobox](https://github.com/89luca89/distrobox) - Tool for containerized command line environments on Linux, distribution agnostic, supports a wide variety of containers , works both with podman and docker - This is a great tool to start with on your existing distro to learn working with day-to-day container workflows.
	- [BoxBuddy](https://flathub.org/apps/io.github.dvlv.boxbuddyrs) - A GUI manager for your Distroboxes, made with GTK4 and Libadwaita.
- [devbox](https://github.com/jetpack-io/devbox) - Devbox is a command-line tool that lets you easily create isolated shells and containers.
- [nsbox](https://github.com/refi64/nsbox) - Pet container manager based on systemd-nspawn and supporting DBus and desktop files.
- [unbox](https://github.com/lopukhov/unbox) - New (a little bit experimental) implementation of a toolbox that does not rely on existing container engines like `podman` or `docker`, instead opting to use Linux namespaces directly to improve performance.
- [coretoolbox](https://github.com/cgwalters/coretoolbox) - Toolbx alternative in rust with a focus on container builds. (Older project, appears unmaintained, but if I don't include rust stuff people will get upset :smiley:)
- [folderbox](https://github.com/ahayzen/folderbox) - Folder based containers that isolate project environments with escapes to the host for development.
- [apx](https://github.com/Vanilla-OS/apx) - The default package manager for VanillaOS, utilising Distrobox to manage containers for various distros on the user's behalf.

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
- [ABRoot](https://github.com/Vanilla-OS/ABRoot) - A utility which provides full immutability and atomicity to a Linux system, by transacting between two root filesystems. Updates are performed using OCI images, to ensure that the system is always in a consistent state.
- [BootC](https://github.com/containers/bootc) - Transactional, in-place operating system updates using OCI/Docker container images. (Experimental)
- [bootupd](https://github.com/coreos/bootupd) - Distribution-independent updates for bootloaders.
- [Elemental Toolkit](https://rancher.github.io/elemental-toolkit/) - A toolkit which allows container images to be bootable in VMs, baremetals, embedded devices, and much more. Elemental and derivatives share a common feature set, can be upgraded with a A/B mechanism, and upgrades are delivered with standard container registries.
- [GoldBoot](https://github.com/fossable/goldboot) - a command-line utility that builds machine images for both servers and workstations alike.
- [Arkdep](https://github.com/arkanelinux/arkdep) - Toolkit for building, deploying and maintaining immutable, atomic, btrfs-based systems

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
- [Universal BLue](https://github.com/ublue-os) - Community built OS images based on Fedora Silverblue
- [ansible-silverblue](https://github.com/j1mc/ansible-silverblue) - Jim Campbell's ansible playbook for silverblue
- [Sodalite: A Pantheon Experience for Silverblue](https://github.com/electricduck/sodalite)
- [silvernobara](https://github.com/VinnyVynce/silvernobara) - Fedora Silverblue with Project Nobara enhancements

## Desktop Tours

Here are some people walking through their setups:

- [Schykle's Dell XPS 13 and Silverblue Setup](https://www.youtube.com/watch?v=CeiPUxLf-dQ)
- [Jorge Castro's Desktop](https://www.youtube.com/watch?v=PM5exNztbXE)

## Tips

- [Using Automatic Updates on Fedora Silverblue](https://miabbott.github.io/2018/06/13/rpm-ostree-automatic-updates.html)

## Discussion

- Reddit:
	- [r/silverblue](https://www.reddit.com/r/silverblue/)
	- [r/NixOS](https://www.reddit.com/r/NixOS/)
	- [r/flatpak](https://www.reddit.com/r/flatpak/)

- Discord Servers:
	- [Immutable Linux Discord](https://discord.gg/N4mswFw6ds)
	- [Universal Blue Discord](https://discord.gg/Xsk7n54fFY)
	- [NixOS Discord](https://discord.gg/RbvHtGa)
	- [VanillaOS Discord](https://discord.gg/vanilla-os-1023243680829681704)
	- [ChimeraOS Discord](https://discord.gg/rgB8utyteK)

- Matrix Rooms:
	- [Fedora Silverblue Matrix Room](https://matrix.to/#/#silverblue:fedoraproject.org)
	- [NixOS Matrix Room](https://matrix.to/#/#nix:matrix.org)
	- [OpenSUSE Aeon / Kalpa](https://matrix.to/#/#microos-desktop:opensuse.org)

## Miscellaneous

Things that don't fit anywhere else but might be useful reference material

- [Introducing flox - Nix for simplicity and scale](https://discourse.nixos.org/t/introducing-flox-nix-for-simplicity-and-scale/11275) - Barry Plunkett

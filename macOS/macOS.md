# macOS

## Clean install

You can clean install by going to Recovery mode (restart with `cmd+r` pressed). Then Disk Utility > Select disk > Erase (Format it) > Close Disk Utility > Select option Reinstall MacOS (Choose macOS ver. to install).

## Notes

- In save dialogues I can press these keys:
  - `Return` or `⌘ + S` = Save
  - `ESC` = Cancel
- I can also press `/` or `~` to quickly go to some directory from a save dialogue. And I can press `⌘ + ↑` to go to `parent directory`.
- Recovery mode: Power off the machine, press the power button and immediately hold Cmd-R.
- [Both Windows and MacOS are at a point where clean installs are unnecessary.](https://www.reddit.com/r/MacOS/comments/90g4h9/is_it_worth_the_effort_to_do_a_clean_install_of/)
  - I can appreciate someone wanting to do a clean install if they've installed and removed many apps and just want to clear out everything spread around all the system and hidden folders, even if it doesn't really affect performance and won't save a ton of disk space. There is something cathartic about a clean install.
- `/usr/local/bin` is a good place to put raw binaries available in the path, that are not installed with Nix.
- [`defaults write NSGlobalDomain KeyRepeat -int 1` setup keyboard repeat.](https://twitter.com/jordwalke/status/1230582824224165888)
- [Can select text from middle of link's text by holding down alt while you drag and select with the mouse](https://twitter.com/MBoffin/status/1218668903586394112)
- [plutil tool support the generation of Swift or Objective-C code directly from plists. For example: plutil -convert swift.](https://twitter.com/dmartincy/status/1295029196503351298)

## Links

- [macOS developer tutorials](https://www.raywenderlich.com/category/macos)
- [A Pro’s Guide to the Best Secret Mac Features](https://matthewpalmer.net/blog/2018/04/14/ultimate-pro-guide-best-secret-mac-features/index.html)
- [macOS open source](https://opensource.apple.com/)
- [Create bootable USB macOS installer](https://macdaddy.io/create-bootable-usb-macos-installer/)
- [macOS Security and Privacy Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
- [Quick Look plugins](https://github.com/sindresorhus/quick-look-plugins)
- [cron is dead, long live launchd! (2017)](http://blog.jan-ahrens.eu/2017/01/13/cron-is-dead-long-live-launchd.html)
- [Control Mac Keyboard Brightness](https://github.com/pirate/mac-keyboard-brightness) - Programmatically flash the keyboard lights and control display brightness on Macs.
- [maclaunchmaclaunch](https://github.com/HazCod/maclaunch) - Manage your macOS startup items.
- [Objective-See](https://www.objective-see.com/) - Simple, yet effective macOS security tools.
- [Caliguvara - another approach to Touch Bar Presets (2019)](https://community.folivora.ai/t/caliguvara-c2-my-first-update-great-new-calendar-widgets-a-totally-new-way-to-share-your-music-design-fixes-and-more/6996)
- [AppUpdater](https://github.com/mxcl/AppUpdater) - Simple app-updater for macOS, checks your GitHub releases for a binary asset once a day and silently updates your app.
- [Brooklyn](https://github.com/pedrommcarrasco/Brooklyn) - Screensaver inspired by Apple's Event on October 30, 2018.
- [How macOS versions evolved and changed over the time](https://www.reddit.com/r/MacOS/comments/bc1lvk/how_macos_versions_evolved_and_changed_over_the/)
- [PureDarwin](https://github.com/PureDarwin/PureDarwin) - Community project to make Darwin more usable. ([HN](https://news.ycombinator.com/item?id=23799331))
- [Curated list of shell commands and tools specific to macOS](https://github.com/herrbischoff/awesome-macos-command-line)
- [The new Mac Pro is a design remix (2019)](https://www.arun.is/blog/mac-pro/)
- [BlockBlock](https://www.objective-see.com/products/blockblock.html) - Continually monitors common persistence locations and displays an alert whenever a persistent component is added to the OS.
- [Impact](https://github.com/ChimeHQ/Impact) - Crash detection and recording library for Apple platforms.
- [Designing LookUp for macOS (2019)](https://medium.com/lookup-design/designing-lookup-for-macos-bf5b8fea1a01)
- [macOS screenshot tips](https://twitter.com/CoreyGinnivan/status/1187209574303973376)
- [gon](https://github.com/mitchellh/gon) - CLI and Go Library for macOS Notarization.
- [Shipping a Catalyst App - Peter Steinberger (2019)](https://www.youtube.com/watch?v=Xo3zGlyxXcI)
- [Open-source components of macOS](https://github.com/apple-open-source/macos)
- [macOS Headers](https://github.com/w0lfschild/macOS_headers) - Consistently maintained dump of most macOS Headers.
- [Every macOS white paper](https://github.com/0xmachos/mac-white-papers)
- [AppMover](https://github.com/OskarGroth/AppMover) - Framework for moving your application bundle to Applications folder on launch.
- [Lilu](https://github.com/acidanthera/Lilu) - Arbitrary kext and process patching on macOS.
- [osx-hid-inspector](https://github.com/pqrs-org/osx-hid-inspector) - Command line tool for macOS for inspecting human input devices (HID).
- [macOS Kernel Extensions are officially deprecated](https://developer.apple.com/support/kernel-extensions/) ([HN](https://news.ycombinator.com/item?id=22251076))
- [mas-cli](https://github.com/mas-cli/mas) - Simple command line interface for the Mac App Store. Designed for scripting and automation.
- [apply-user-defaults](https://github.com/zero-sh/apply-user-defaults) - Small utility to set macOS user defaults declaratively from a YAML file.
- [Zero.sh](https://github.com/zero-sh/zero.sh) - Radically simple personal bootstrapping tool for macOS.
- [DefaultApp](https://tyler.io/default-app-for-mac-ios/) - Template for starting macOS projects. ([Code](https://github.com/tylerhall/DefaultApp)) ([HN](https://news.ycombinator.com/item?id=22582456))
- [Awesome macOS](https://github.com/iCHAIT/awesome-macOS)
- [macOS and iOS Security Related Tools](https://github.com/ashishb/osx-and-ios-security-awesome)
- [BlackHole](https://github.com/ExistentialAudio/BlackHole) - Modern MacOS virtual audio driver that allows applications to pass audio to other applications with zero additional latency.
- [xcnotary](https://github.com/akeru-inc/xcnotary) - Missing macOS app notarization helper, built with Rust. ([HN](https://news.ycombinator.com/item?id=22743659))
- [skhd](https://github.com/koekeishiya/skhd) - Simple hotkey daemon for macOS.
- [Proxy Audio Driver](https://github.com/briankendall/proxy-audio-device) - Virtual audio driver for macOS to sends all audio to another output.
- [Icons.app](https://github.com/SAP/macOS-icon-generator) - App for macOS which is designed to generate consistent sized icons of an existing application in various states, jiggling (shaking) etc.
- [OpenCore](https://dortania.github.io/OpenCore-Desktop-Guide/) - Open-source, unconventional, first-in-class piece of software designed to intercept kernel loading to insert a highly advanced rootkit, designed to be an alternative to Clover. ([Code](https://github.com/dortania/OpenCore-Desktop-Guide)) ([HN](https://news.ycombinator.com/item?id=22916281))
- [Creating a macOS App with SwiftUI](https://developer.apple.com/tutorials/swiftui/creating-a-macos-app)
- [Syphon](https://github.com/Syphon/Syphon-Framework) - macOS technology to allow applications to share video and still images with one another in realtime, instantly.
- [Mac Bare Metal](https://flow.swiss/mac-bare-metal) - Enterprise-class IaaS for macOS.
- [React Native for macOS](https://github.com/microsoft/react-native-macos) - Build native macOS apps with React. ([HN](https://news.ycombinator.com/item?id=23160075))
- [My Mac App Store Debate (2020)](https://inessential.com/2020/05/12/my_mac_app_store_debate)
- [Kernel debugging macOS with SIP (2020)](https://www.offensive-security.com/offsec/kernel-debugging-macos-with-sip/)
- [Mac App Store Sandbox Escape (2020)](https://saagarjha.com/blog/2020/05/20/mac-app-store-sandbox-escape/)
- [macOS 10.15: Slow by Design (2020)](https://sigpipe.macromates.com/2020/macos-catalina-slow-by-design/) ([HN](https://news.ycombinator.com/item?id=23273247))
- [Catalina is checking notarization of unsigned executables (2020)](https://lapcatsoftware.com/articles/catalina-executables.html) ([HN](https://news.ycombinator.com/item?id=23281564))
- [Push-Button Installer of macOS Guests in VirtualBox for Windows, Linux, macOS](https://github.com/myspaghetti/macos-virtualbox) ([HN](https://news.ycombinator.com/item?id=23284987))
- [macOS in a Docker Container](https://github.com/sickcodes/Docker-OSX) ([HN](https://news.ycombinator.com/item?id=23419101)) ([Reddit](https://www.reddit.com/r/jailbreak/comments/gwg3e4/free_release_dockerosx_run_xcode_on_linux_sign/))
- [netboot.nix](https://github.com/grahamc/netboot.nix) - Create full netboot images in 15 seconds.
- [Swizzle](https://github.com/NSExceptional/Swizzle) - Extensible tweak to create simple tweaks for any app, from within any app.
- [What’s New in macOS Big Sur: Human Interface Guidelines (2020)](https://developer.apple.com/design/human-interface-guidelines/macos/overview/whats-new-in-macos/) ([HN](https://news.ycombinator.com/item?id=23606052))
- [About the Rosetta Translation Environment (2020)](https://developer.apple.com/documentation/apple_silicon/about_the_rosetta_translation_environment) ([HN](https://news.ycombinator.com/item?id=23613995))
- [The End of OS X (2020)](https://stratechery.com/2020/the-end-of-os-x/) ([HN](https://news.ycombinator.com/item?id=23617629))
- [Common Mac OS X Cursors as PNGs](https://tobiasahlin.com/blog/common-mac-os-x-lion-cursors/)
- [Apple’s Relentless Strategy, Execution, and Point of View (2020)](https://medium.learningbyshipping.com/apples-relentless-strategy-and-execution-7544a76aa26) ([HN](https://news.ycombinator.com/item?id=23670722))
- [Extract the system libraries on macOS Big Sur (2020)](https://lapcatsoftware.com/articles/bigsur.html)
- [Apple Technologies Search](https://developer.apple.com/documentation/technologies)
- [AquaticPrime](https://github.com/bdrister/AquaticPrime) - Mac software licensing code using cryptographically signed license files.
- [SimpleVM](https://github.com/KhaosT/SimpleVM) - Sample code for Virtualization framework.
- [macOS 11 Big Sur UI Kit](https://products.ls.graphics/macos/)
- [The Art Of Mac Malware](https://taomm.org/)
- [Compromising the macOS Kernel through Safari by Chaining Six Vulnerabilities](https://github.com/sslab-gatech/pwn2own2020)
- [Mac keyboard shortcuts](https://support.apple.com/en-us/HT201236) ([HN](https://news.ycombinator.com/item?id=24080378))
- [Ask HN: What feature did you find after years of using macOS? (2020)](https://news.ycombinator.com/item?id=24091707)
- [Sinter](https://github.com/trailofbits/sinter) - User-mode application authorization system for MacOS written in Swift. ([Article](https://blog.trailofbits.com/2020/08/12/sinter-new-user-mode-security-enforcement-for-macos/))
- [MacPorts package manager](https://www.macports.org/) ([Code](https://github.com/macports/macports-ports))
- [macOS icon pack](https://macosicons.com/) - Beautiful open source icons for Big Sur. ([Code](https://github.com/elrumo/macOS_Big_Sur_icons_replacements))
- [Thoughts on macOS Package Managers (2019)](https://saagarjha.com/blog/2019/04/26/thoughts-on-macos-package-managers/)
- [Sparkle](https://github.com/sparkle-project/Sparkle) - Software update framework for macOS.
- [Hard to discover tips and apps for macOS (2020)](https://thume.ca/2020/09/04/macos-tips/) ([HN](https://news.ycombinator.com/item?id=24391899)) ([Lobsters](https://lobste.rs/s/kpar4v/hard_discover_tips_apps_for_making_macos))
<div align="center">

<img
    src="https://github.com/accrescent/accrescent/blob/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png"
    alt="Accrescent icon"
    width="160"
    height="160">

# This is Accrescent

A novel Android app store focused on security, privacy, and usability.

</div>

**Note: Accrescent is not yet ready for production usage. Consider all software
and services run by this organization as in a "pre-alpha" stage and fit only for
development and preliminary testing. The apps Accrescent contains are there only
for testing purposes and will be removed (except for Accrescent itself) when
Accrescent enters public alpha.**

## About

Accrescent aims to deliver a secure, private, and usable Android app store. It
does this primary through the following features:

- Repository metadata is signed to protect served content against malicious
  tampering.
- App signing keys are pinned in repository metadata to ensure first-time app
  installs are legitimate (no more TOFU).
- Signed metadata verifies certain app metadata is legitimate so users can't be
  tricked into installing a fake, unapproved, or copycat app even if the server
  is compromised.
- Automatic, unattended background updates are supported without any special
  privileges.
- Apps are signed by their developers so even if Accrescent was compromised, the
  developer's keys wouldn't be.
- No account is required to install apps.
- Split APKs are the primary app distribution format so downloads are optimized
  for your device.
- Hosted apps must meet strict privacy and security requirements such as
  targeting a modern SDK, only requesting necessary sensitive permissions, etc.
- TLS certificate pinning is enabled on the client.

...and more

Accrescent currently supports Android 12 and up.

## Subprojects

- [Accrescent] - the Android client for browsing and installing apps
- [apkstat] - an APK parsing tool and Go library used in the developer portal
- [devportal] - the web portal for developers to manage their apps in Accrescent

## Trademark

The name "Accrescent" and the Accrescent logo are common law trademarks owned by
the Accrescent project. All other parties are forbidden from using Accrescent's
name and branding, as are derivatives of Accrescent. Derivatives include, but
are not limited to forks and unofficial builds.

[Accrescent]: https://github.com/accrescent/accrescent
[apkstat]: https://github.com/accrescent/apkstat
[devportal]: https://github.com/accrescent/devportal

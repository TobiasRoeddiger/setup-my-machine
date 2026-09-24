# Mac Setup – Checklist

## 1. Baseline and Inventory

- [ ] Check available disk space and macOS/CPU version
- [ ] Inventory existing applications and command-line tools
- [ ] Install Homebrew and run `brew doctor`
- [ ] Install Xcode Command Line Tools

## 2. General Applications

- [ ] Install Visual Studio Code
- [ ] Install WhatsApp Desktop
- [ ] Install Signal Desktop
- [ ] Install Mozilla Thunderbird
- [ ] Install Spotify
- [ ] Install Zoom
- [ ] Install Audacity
- [ ] Install Arduino IDE
- [ ] Install Bambu Studio
- [ ] Install KiCad
- [ ] Install EasyEDA Pro
- [ ] Install PreForm

## 3. Microsoft Office

- [ ] Install Microsoft Word
- [ ] Install Microsoft Excel
- [ ] Install Microsoft PowerPoint
- [ ] Install Microsoft Teams
- [ ] Launch Office applications and verify installation status
- [ ] If necessary: Microsoft sign-in/license activation by the user

## 4. Terminal and Zsh

- [ ] Zsh available (`/bin/zsh`)
- [ ] Zsh is the login shell
- [ ] Install Oh My Zsh or a suitable prompt framework
- [ ] Install a Powerline-compatible Nerd Font
- [ ] Configure the Solarized Dark color scheme for the Terminal
- [ ] Configure a Powerline prompt with wide arrow segments
- [ ] Disable emojis in the prompt
- [ ] Check Git, folder, and status segments
- [ ] Check the appearance in a new Terminal window

## 5. Nordic, J-Link, and OpenEarable 2

- [ ] Install nRF Connect for Desktop
- [ ] Install nRF Connect for VS Code extensions
- [ ] Install nRF Connect SDK 3.0.1
- [ ] Install nRF Toolchain 3.0.1
- [ ] Install SEGGER J-Link Software
- [ ] Check `JLinkExe` and other J-Link tools from the command line
- [ ] Download the OpenEarable-2 repository or locate an existing repository
- [ ] Clone the OpenEarable-2 repository into the `tobi` user's home directory
- [ ] Initialize dependencies/submodules
- [ ] Compile board `openearable_v2/nrf5340/cpuapp` with a clean build
- [ ] Compile the optional FOTA build
- [ ] Document build artifacts and exit status
- [ ] If hardware is connected: verify J-Link device detection

## 6. Flutter, Xcode, and Android

- [ ] Install Flutter SDK
- [ ] Permanently add Flutter to `PATH`
- [ ] Install Xcode
- [ ] Accept the Xcode license and complete the initial setup
- [ ] Install iOS Simulator/required platforms
- [ ] Install CocoaPods
- [ ] Install Android Studio
- [ ] Install Android SDK, Platform Tools, and Command-line Tools
- [ ] Accept Android licenses
- [ ] Run `flutter doctor -v`
- [ ] Fix all errors reported by `flutter doctor`
- [ ] Document a final error-free `flutter doctor -v` run
- [ ] Clone the OpenEarable `app` repository (OpenWearables) into the `tobi` user's home directory
- [ ] Install app dependencies
- [ ] Successfully compile the Android app
- [ ] Successfully compile the iOS app
- [ ] Document Android and iOS build artifacts

## 7. Trackpad

- [ ] Determine the current scroll direction
- [ ] Set the scroll direction to the Windows native scroll direction
- [ ] Verify the setting

## 8. Python and Jupyter

- [ ] Install the latest Python 3
- [ ] Check `python3` in a new Zsh session
- [ ] Make `pip3` and `pip` available and verify them
- [ ] Install JupyterLab and Jupyter Notebook in isolation
- [ ] Register the Python kernel
- [ ] Start Jupyter with a test notebook and verify kernel execution

## 9. Git and SSH

- [ ] Check the existing Git and SSH configuration
- [ ] Configure the Git user as `TobiasRoeddiger`
- [ ] Create a dedicated Ed25519 SSH key or use a suitable existing key
- [ ] Securely store the GitHub host key
- [ ] Add the public key to the `TobiasRoeddiger` GitHub account
- [ ] Configure the SSH agent and macOS Keychain
- [ ] Verify access with `ssh -T git@github.com`
- [ ] Perform a final Git access test over SSH

## 10. Final Verification

- [ ] Check all GUI applications under `/Applications`
- [ ] Check all required CLI commands in a new Zsh session
- [ ] Document any outstanding sign-ins, licenses, or user actions
- [ ] Create a final report with versions and test results

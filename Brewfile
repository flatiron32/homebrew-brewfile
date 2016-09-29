########################################
# Jody Lent
# Brewfile for building a new Mac
########################################

# Handled via Strap (https://github.com/MikeMcQuaid/strap):
# Install Prereqs: Xcode, brew, cask and pip
# cask is installed via tap, pip comes with brew's python install
tap 'homebrew/core'
tap 'caskroom/cask'

# Packages
brew 'git'
brew 'python'
brew 'tree'
brew 'wget'

# Apps
cask 'beardedspice'
cask 'caffeine'
cask 'charles'
cask 'docker'
cask 'dropbox'
cask 'firefox'
cask 'google-chrome'
cask 'hipchat'
cask 'karabiner'
cask 'macdown'
cask 'macid'
cask 'macpass'
cask 'osxfuse'
cask 'slack'
cask 'spectacle'
cask 'sublime'
cask 'tunnelblick'
#cask 'veracrypt' # see issue below
cask 'vlc'

# VERACRYPT issue https://github.com/caskroom/homebrew-cask/issues/20726
# Allow `brew bundle` to run (or just `brew cask install osxfuse`) and then:
# -- run `open /usr/local/Caskroom/osxfuse/*/Install\ OSXFUSE*.pkg`
# -- install with MacFUSE compatibility layer
# -- run `brew cask install veracrypt`

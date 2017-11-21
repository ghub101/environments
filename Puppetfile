#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com"

# A module from the Puppet Forge
mod 'puppetlabs-stdlib'

# A module from git
mod 'puppetlabs-ntp',
   :git => 'git://github.com/puppetlabs/puppetlabs-ntp.git'

# A module from a git branch/tag
mod 'puppetlabs-apt',
   :git => 'https://github.com/puppetlabs/puppetlabs-apt.git',
   :ref => '1.4.x'

mod 'testrepo',
   :git => 'https://github.com/ghub101/testrepo.git',
   :branch => 'master'

mod 'apache',
   :git => 'https://github.com/ghub101/apache.git',
   :branch => 'master'

# A module from Github pre-packaged tarball
# mod 'puppetlabs-apache', '0.6.0', :github_tarball => 'puppetlabs/puppetlabs-apache'

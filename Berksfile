source 'https://supermarket.chef.io'

cookbook 'omnibus_sensu', path: 'site-cookbooks/omnibus_sensu'
cookbook 'omnibus', git: 'https://github.com/sensu/omnibus-cookbook.git', ref: 'sensu'

# Uncomment to use the latest version of the Omnibus cookbook from GitHub
# cookbook 'omnibus', github: 'opscode-cookbooks/omnibus'

group :integration do
  cookbook 'apt',      '~> 2.8'
  cookbook 'yum-epel', '~> 0.6'
end

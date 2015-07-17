# -*- mode: python; -*-

#
# Copyright (c) 2014 Juniper Networks, Inc. All rights reserved.
#

Import('DnsEnv')
env = DnsEnv.Clone()

utils_scripts = [
  'add_virtual_dns.py',
  'add_virtual_dns_record.py',
  'associate_virtual_dns.py',
  'del_virtual_dns.py',
  'del_virtual_dns_record.py',
  'set_dns_nameserver.py',
  'disassociate_virtual_dns.py']

for utils in utils_scripts:
  env.Alias('install',env.Install(env['INSTALL_EXAMPLE'], utils))

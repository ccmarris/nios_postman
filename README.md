# nios_postman
## Infoblox NIOS API Examples

| Version: 0.1.1
| Author: Chris Marrison
| Email: chris@infoblox.com

This collection provides examples of working with the NIOS APIs.

The collections require several environment variables to be configured::

  - version: <version_string> 
  - base_url: https://\<gm\>/wapi/\{{version}}
  - auth_user:  username
  - auth_pw: password

Where <gm> is the name/ip of the Grid Master and <version_string> is the wapi version (v2.12.0 NIOS 8.6.x)

## License

These collections are licensed under the BSD 2-Clause License, see LICENSE for details.

## Acknowledgements

Thanks to Ross Gibson for the scripted DTC API Examples

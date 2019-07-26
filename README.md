
# Forum Access

This is module has been partially ported from Drupal 7 to Backdrop CMS,
but it is not yet functional. Please, feel free to help by testing,
reporting issues, and/or creating pull requests.

New maintainers are welcome.

## Overview

Forum Access changes your forum administration pages to let you apply
role-based permissions to each forum, and to give each forum individual
moderators.

Moderators automatically get all privileges on all posts in that forum,
including edit and delete.

## Requirements

Forum Access requires the current versions of the following modules:

- ACL <https://backdropcms.org/project/acl>
- Chain Menu Access API <https://backdropcms.org/project/chain_menu_access>

## Permissions

Administering Forum Access requires Core's Administer Forums permission.
Detailed explanations of how Forum Access' grants work together with Core's
other permissions are available on the administration pages.

## Configuration

Forum Access does not have its own administration page -- it adds its controls
to Core's forum administration pages. Go to admin/structure/forum, click on an
'edit forum' link and set Access Control for the selected forum.
Repeat this for every other forum.

## Troubleshooting

Step-by-step troubleshooting instructions are provided on the administration
pages.

In case you have additional node access modules enabled, the administration
pages will provide additional information on how to make them work together,
and you should probably follow the troubleshooting instructions to install
DNA and learn about how your combination of node access modules works.

## Installation

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

## Issues

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/forum_access/issues.

## Credits

### Acknowledgements

Originally written for Drupal 5 and maintained by merlinofchaos.
Ported to Drupal 6 and 7 and maintained by salvis.

A full list of contributors can be found at:
https://www.drupal.org/node/87986/committers

### Temporary Maintainers

- Tim Erickson (https://github.com/stpaultim).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

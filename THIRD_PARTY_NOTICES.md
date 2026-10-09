# THIRD PARTY NOTICES

This project uses ideas, feature concepts, and compatibility data from the Piko project, which is licensed under the GNU General Public License v3.0 or later.

## Project provenance

### Piko

- Repository: https://github.com/crimera/piko
- License: https://github.com/crimera/piko/blob/main/LICENSE
- License type: GPL-3.0-or-later
- Description: Morphe patches for Twitter/X and Instagram

### InstaFree

- Repository: https://github.com/iumansam/instafree
- License: https://github.com/iumansam/instafree/blob/main/LICENSE
- License type: Unlicense

## Licensing status

This repository is not a direct derivative of the Piko source tree. The Piko material reviewed here has been used as a research and feature-analysis reference only.

However, because Piko is GPL-3.0-or-later, any future code import or derivative work that includes a significant portion of its source must be reviewed under GPL requirements before distribution.

## Required downstream notice

If any Piko-derived source code is copied or incorporated into a future build, the following obligation applies:

- preserve copyright and license notices
- disclose the source code of the derivative work
- license the derivative work under GPL-3.0-or-later or a compatible GPL license
- keep license notices in place and document the provenance of the code

## Practical interpretation

For this project, the safest approach is:

- treat Piko as a research reference for feature intent, UX, and compatibility strategy
- avoid direct code imports unless legal and engineering review is complete
- keep all imported logic minimal, well documented, and isolated from the original InstaFree flow

## Additional references

- Piko README: https://github.com/crimera/piko/blob/main/README.md
- Piko changelog: https://github.com/crimera/piko/blob/main/CHANGELOG.md
- Piko patches metadata: https://github.com/crimera/piko/blob/main/patches-list.json
- InstaFree README: https://github.com/iumansam/instafree/blob/main/Readme.md

## Conclusion

This repository is using Piko as a feature reference, not as a licensed code import. Any future production-level integration that includes copied Piko logic must be re-evaluated under the GPL conditions before shipping.

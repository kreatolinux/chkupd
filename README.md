# chkupd v2
The ultimate update checker for Kreato Linux.
The repository also contains libchkupd, the main part of chkupd which is meant to be sourced by other scripts.
This is done so other Kreato Linux projects can use chkupd without invoking it directly, giving more control.

# Dependencies
* jq
* curl

# Backends
Current backends include;
* nyaa_chkupd which checks for nyaa-repo-bin packages' updates
* arch_chkupd which checks from the Arch repository for updates

# License
Copyright (C) 2022 Kreato

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

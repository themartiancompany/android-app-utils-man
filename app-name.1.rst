..
   SPDX-License-Identifier: AGPL-3.0-or-later

   -------------------------------------------------------
   Copyright © 2024, 2025, 2026
               Pellegrino Prevete

   All rights reserved
   -------------------------------------------------------

   This program is free software: you can redistribute it
   and/or modify it under the terms of the
   GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will
   be useful, but WITHOUT ANY WARRANTY; without even the
   implied warranty of MERCHANTABILITY or FITNESS FOR A
   PARTICULAR PURPOSE.
   See the GNU Affero General Public License
   for more details.

   You should have received a copy of the
   GNU Affero General Public License
   along with this program.
   If not, see <https://www.gnu.org/licenses/>.


=============================
app-name
=============================

--------------------------------------------------------------
Returns the application label for a package
--------------------------------------------------------------
:Version: app-name |version|
:Manual section: 1


Synopsis
========

app-name *[options]* *package-name*


Description
===========

Shows Android virtual keyboard.


Application options
=====================


-m                   Method to use to
                     retrieve the application
                     label.
                     It can be 'root'.

-h                   Display help.

-c                   Enable color output

-v                   Enable verbose output


Bugs
====

https://github.com/themartiancompany/android-app-utils/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* app-installed
* activities-info
* windows-info
* keyboard-hide
* coordinates-orthonormal
* activity-launch
* activity-focused
* bbrightnessctl
* displayctl
* powerctl
* sissystemctl

.. include:: variables.rst

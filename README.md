# NAME

Lazy::Utils - Utilities for lazy

# VERSION

version 1.01

# SYNOPSIS

Utilities for lazy

## Methods

### trim

trims given string

> trim($str)
>
> **$str:** string will be trimed
>
> **return value:** trimed string

### ltrim

trims left given string

> ltrim($str)
>
> **$str:** string will be trimed
>
> **return value:** trimed string

### rtrim

trims right given string

> rtrim($str)
>
> **$str:** string will be trimed
>
> **return value:** trimed string

### file\_get\_contents

get all contents of file, by string type

> file\_get\_contents($path)
>
> **$path:** path of file
>
> **return value:** file contents by string type

### shellmeta

escape metacharacters for double-quoted shell string

> shellmeta($s)
>
> **$s:** double-quoted shell string
>
> **return value:** escaped string

# INSTALLATION

To install this module type the following

        perl Makefile.PL
        make
        make test
        make install

from CPAN

        cpan -i Lazy::Utils

# DEPENDENCIES

This module requires these other modules and libraries:

- Switch
- FindBin
- Cwd
- File::Basename

# REPOSITORY

**GitHub** [https://github.com/orkunkaraduman/Lazy-Utils](https://github.com/orkunkaraduman/Lazy-Utils)

**CPAN** [https://metacpan.org/release/Lazy-Utils](https://metacpan.org/release/Lazy-Utils)

# AUTHOR

Orkun Karaduman &lt;orkunkaraduman@gmail.com&gt;

# COPYRIGHT AND LICENSE

Copyright (C) 2016  Orkun Karaduman &lt;orkunkaraduman@gmail.com&gt;

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see &lt;http://www.gnu.org/licenses/&gt;.

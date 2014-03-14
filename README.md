open-stack-clients
==================

Based on rAPIdo language we provide a specification for each OpenStack components based on REST.

## Introduction

Current clients in `Python` for instance provides seamless access to OpenStack components using
REST services. But in parallel such client are not based on a common core. Therefor such approach
implies complexity in the code because the way the client works (pattern) is different and exceptions
are not homogeneous. In addition such clients exist also for different languages like `Java` etc.
implying also maintenance difficulties.

## Specification and Generation

This project proposes a complete specification of OpenStack clients using the [rAPIdo](https://github.com/d-plaindoux/rapido) DSL. Then once such specification is ready a transpiler
stage can be performed generating clients for all supported languages providing at the same time
a complete api for `Python`, `Scala` etc.

## License 

Copyright (C)2014 D. Plaindoux.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program; see the file COPYING. If not, write to the Free Software Foundation, 675 Mass Ave, Cambridge, MA 02139, USA.

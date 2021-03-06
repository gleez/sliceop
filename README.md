# sliceop

Golang []string operations: Prefill, Map, Includes, NotIncludes, Select, Reject

Works well in combination with https://github.com/linkosmos/mapop

[![Build Status](https://travis-ci.org/linkosmos/sliceop.svg?branch=master)](https://travis-ci.org/linkosmos/sliceop)
[![Coverage Status](https://coveralls.io/repos/github/linkosmos/sliceop/badge.svg?branch=master)](https://coveralls.io/github/linkosmos/sliceop?branch=master)
[![GoDoc](http://godoc.org/github.com/linkosmos/sliceop?status.svg)](http://godoc.org/github.com/linkosmos/sliceop)
[![Go Report Card](http://goreportcard.com/badge/linkosmos/sliceop)](http://goreportcard.com/report/linkosmos/sliceop)
[![BSD License](http://img.shields.io/badge/license-BSD-blue.svg)](http://opensource.org/licenses/BSD-3-Clause)

### Methods
 - Prefill(size int, symbol string) (output []string)
 - Map(f func(input string) string, input ...string) (output []string)
 - Includes(input []string, key string) bool
 - NotIncludes(input []string, key string) bool
 - Reject(input []string, toReject ...string) (output []string)
 - Select(input []string, toSelect ...string) (output []string)
 - Unique(input ...string) (output []string)
 - Intersection(u1, u2 []string) (output []string)
 - CountFunc(f func(input string) bool, input ...string) (sum int)
 - Compact(input ...string) (output []string)

### License

Copyright (c) 2015, linkosmos
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of sliceop nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

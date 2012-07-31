Financier
=========

* Author: Samuel G. D. Williams (<http://www.oriontransfer.co.nz>)
* Copyright (C) 2012 Samuel G. D. Williams.
* Released under the MIT license.

Financier is a comprehensive business management platform.

Installation
------------

Install the ruby gem as follows:

	git clone https://github.com/ioquatix/financier.git
	cd financier
	
	bundle install

You need to have CouchDB running and create a database, e.g. `$company-financier`. To load the default design document into CouchDB, use `relaxo`:

	relaxo $company-financier lib/financier.yaml

Finally to start the server:

	thin start -p 3000

You can now open <http://localhost:3000> in your browser. The default username and password is `admin`/`admin`.

License
-------

Copyright (c) 2010, 2011 Samuel G. D. Williams. <http://www.oriontransfer.co.nz>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
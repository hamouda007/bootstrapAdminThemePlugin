h1. Installation

Extract the bootstrapAdminThemePlugin directory into the /plugins directory and enable the plugin in your ProjectConfiguration class.

h2. Usage

Enable the plugin by setting the theme on creation of the admin generator module.

e.g.

bc. ./symfony doctrine:generate-admin --theme=bootstrap backend ModelName

or in generator.yml if you've already created your module

bc. generator:
bc.   param:
bc.     theme:                 bootstrap

h2. Licence (MIT)

Copyright (c) 2012 Malcolm Fell <malcoholm@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

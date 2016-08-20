PHPCoinAddress
==============
PHPCoinAddress is a PHP object that creates public/private key pairs for:
Bitcoin, Namecoin, Litecoin, PPCoin and many other cryptocoins.

PHPCoinAddress is intended to be easy to integrate into other PHP projects. 

Version 0.2.0.pre

Notes:
==============
* modded from https://gist.github.com/scintill/3549107
* includes Pure PHP Elliptic Curve Cryptography Library from https://github.com/mdanter/phpecc
* Requires GMP or bcmath extension (GMP preferred for better performance)

Prefix List:
=============
<pre>Key:
Pub Dec = Prefix for Public Key, Decimal
Pub Hex = Prefix for Public Key, Hexadecimal
Pub lead = leading character in Public Key
Priv Dec = Prefix for Private Key, Decimal 
Priv Hex = Prefix for Private Key, Hexadecimal
Priv lead = leading character in Private Key (Wallet Import Format)
PrvC lead = leading character in Private Key (Compressed Wallet Import Format)
test = Test results for importing PHPCoinAddress created keys into standard client
src = source code repository


Roadmap:
==============
* confirm prefix settings for all coin types, test importing
* add coin types: IXcoin, Fairbrix, royalcoin, etc
* improved error checking + return values

MIT License:
==============
Copyright (C) 2013 PHPCoinAddress Developers

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES
OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.


# api documentation for  [jsbn (v1.1.0)](https://github.com/andyperlitch/jsbn#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsbn.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsbn) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsbn.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsbn)
#### The jsbn library is a fast, portable implementation of large-number math in pure JavaScript, enabling public-key crypto and other applications on desktop and mobile browsers.

[![NPM](https://nodei.co/npm/jsbn.png?downloads=true)](https://www.npmjs.com/package/jsbn)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsbn/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-jsbn_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsbn/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsbn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsbn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tom Wu"
    },
    "bugs": {
        "url": "https://github.com/andyperlitch/jsbn/issues"
    },
    "dependencies": {},
    "description": "The jsbn library is a fast, portable implementation of large-number math in pure JavaScript, enabling public-key crypto and other applications on desktop and mobile browsers.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "b01307cb29b618a1ed26ec79e911f803c4da0040",
        "tarball": "https://registry.npmjs.org/jsbn/-/jsbn-1.1.0.tgz"
    },
    "gitHead": "038459dc74668bfb43b45d78b33ffc9c8e7bf34a",
    "homepage": "https://github.com/andyperlitch/jsbn#readme",
    "keywords": [
        "biginteger",
        "bignumber",
        "big",
        "integer"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "andyperlitch",
            "email": "andyperlitch@gmail.com"
        }
    ],
    "name": "jsbn",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andyperlitch/jsbn.git"
    },
    "scripts": {
        "test": "mocha test.js"
    },
    "version": "1.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module jsbn](#apidoc.module.jsbn)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>BigInteger (a, b, c)](#apidoc.element.jsbn.BigInteger)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>SecureRandom ()](#apidoc.element.jsbn.SecureRandom)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>default (a, b, c)](#apidoc.element.jsbn.default)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>default.prototype.Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett)
1.  object <span class="apidocSignatureSpan">jsbn.</span>SecureRandom.prototype
1.  object <span class="apidocSignatureSpan">jsbn.</span>default.prototype
1.  object <span class="apidocSignatureSpan">jsbn.</span>default.prototype.Barrett.prototype

#### [module jsbn.SecureRandom](#apidoc.module.jsbn.SecureRandom)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>SecureRandom ()](#apidoc.element.jsbn.SecureRandom.SecureRandom)

#### [module jsbn.SecureRandom.prototype](#apidoc.module.jsbn.SecureRandom.prototype)
1.  [function <span class="apidocSignatureSpan">jsbn.SecureRandom.prototype.</span>nextBytes (ba)](#apidoc.element.jsbn.SecureRandom.prototype.nextBytes)

#### [module jsbn.default](#apidoc.module.jsbn.default)
1.  [function <span class="apidocSignatureSpan">jsbn.</span>default (a, b, c)](#apidoc.element.jsbn.default.default)
1.  object <span class="apidocSignatureSpan">jsbn.default.</span>ONE
1.  object <span class="apidocSignatureSpan">jsbn.default.</span>ZERO

#### [module jsbn.default.prototype](#apidoc.module.jsbn.default.prototype)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>abs ()](#apidoc.element.jsbn.default.prototype.abs)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>add (a)](#apidoc.element.jsbn.default.prototype.add)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>addTo (a, r)](#apidoc.element.jsbn.default.prototype.addTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>am (i, x, w, j, c, n)](#apidoc.element.jsbn.default.prototype.am)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>and (a)](#apidoc.element.jsbn.default.prototype.and)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>andNot (a)](#apidoc.element.jsbn.default.prototype.andNot)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitCount ()](#apidoc.element.jsbn.default.prototype.bitCount)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitLength ()](#apidoc.element.jsbn.default.prototype.bitLength)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitwiseTo (a, op, r)](#apidoc.element.jsbn.default.prototype.bitwiseTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>byteValue ()](#apidoc.element.jsbn.default.prototype.byteValue)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>changeBit (n, op)](#apidoc.element.jsbn.default.prototype.changeBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>chunkSize (r)](#apidoc.element.jsbn.default.prototype.chunkSize)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clamp ()](#apidoc.element.jsbn.default.prototype.clamp)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clearBit (n)](#apidoc.element.jsbn.default.prototype.clearBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clone ()](#apidoc.element.jsbn.default.prototype.clone)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>compareTo (a)](#apidoc.element.jsbn.default.prototype.compareTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>copyTo (r)](#apidoc.element.jsbn.default.prototype.copyTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dAddOffset (n, w)](#apidoc.element.jsbn.default.prototype.dAddOffset)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dMultiply (n)](#apidoc.element.jsbn.default.prototype.dMultiply)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divRemTo (m, q, r)](#apidoc.element.jsbn.default.prototype.divRemTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divide (a)](#apidoc.element.jsbn.default.prototype.divide)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divideAndRemainder (a)](#apidoc.element.jsbn.default.prototype.divideAndRemainder)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dlShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.dlShiftTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>drShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.drShiftTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>equals (a)](#apidoc.element.jsbn.default.prototype.equals)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>exp (e, z)](#apidoc.element.jsbn.default.prototype.exp)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>flipBit (n)](#apidoc.element.jsbn.default.prototype.flipBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromInt (x)](#apidoc.element.jsbn.default.prototype.fromInt)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromNumber (a, b, c)](#apidoc.element.jsbn.default.prototype.fromNumber)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromRadix (s, b)](#apidoc.element.jsbn.default.prototype.fromRadix)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromString (s, b)](#apidoc.element.jsbn.default.prototype.fromString)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>gcd (a)](#apidoc.element.jsbn.default.prototype.gcd)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>getLowestSetBit ()](#apidoc.element.jsbn.default.prototype.getLowestSetBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>intValue ()](#apidoc.element.jsbn.default.prototype.intValue)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>invDigit ()](#apidoc.element.jsbn.default.prototype.invDigit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>isEven ()](#apidoc.element.jsbn.default.prototype.isEven)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>isProbablePrime (t)](#apidoc.element.jsbn.default.prototype.isProbablePrime)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>lShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.lShiftTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>max (a)](#apidoc.element.jsbn.default.prototype.max)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>millerRabin (t)](#apidoc.element.jsbn.default.prototype.millerRabin)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>min (a)](#apidoc.element.jsbn.default.prototype.min)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>mod (a)](#apidoc.element.jsbn.default.prototype.mod)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modInt (n)](#apidoc.element.jsbn.default.prototype.modInt)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modInverse (m)](#apidoc.element.jsbn.default.prototype.modInverse)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modPow (e, m)](#apidoc.element.jsbn.default.prototype.modPow)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modPowInt (e, m)](#apidoc.element.jsbn.default.prototype.modPowInt)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiply (a)](#apidoc.element.jsbn.default.prototype.multiply)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyLowerTo (a, n, r)](#apidoc.element.jsbn.default.prototype.multiplyLowerTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyTo (a, r)](#apidoc.element.jsbn.default.prototype.multiplyTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyUpperTo (a, n, r)](#apidoc.element.jsbn.default.prototype.multiplyUpperTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>negate ()](#apidoc.element.jsbn.default.prototype.negate)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>not ()](#apidoc.element.jsbn.default.prototype.not)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>or (a)](#apidoc.element.jsbn.default.prototype.or)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>pow (e)](#apidoc.element.jsbn.default.prototype.pow)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>rShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.rShiftTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>remainder (a)](#apidoc.element.jsbn.default.prototype.remainder)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>setBit (n)](#apidoc.element.jsbn.default.prototype.setBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shiftLeft (n)](#apidoc.element.jsbn.default.prototype.shiftLeft)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shiftRight (n)](#apidoc.element.jsbn.default.prototype.shiftRight)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shortValue ()](#apidoc.element.jsbn.default.prototype.shortValue)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>signum ()](#apidoc.element.jsbn.default.prototype.signum)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>square ()](#apidoc.element.jsbn.default.prototype.square)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>squareTo (r)](#apidoc.element.jsbn.default.prototype.squareTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>subTo (a, r)](#apidoc.element.jsbn.default.prototype.subTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>subtract (a)](#apidoc.element.jsbn.default.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>testBit (n)](#apidoc.element.jsbn.default.prototype.testBit)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toByteArray ()](#apidoc.element.jsbn.default.prototype.toByteArray)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toRadix (b)](#apidoc.element.jsbn.default.prototype.toRadix)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toString (b)](#apidoc.element.jsbn.default.prototype.toString)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>xor (a)](#apidoc.element.jsbn.default.prototype.xor)
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>DB
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>DM
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>DV
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>F1
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>F2
1.  number <span class="apidocSignatureSpan">jsbn.default.prototype.</span>FV

#### [module jsbn.default.prototype.Barrett](#apidoc.module.jsbn.default.prototype.Barrett)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett.Barrett)

#### [module jsbn.default.prototype.Barrett.prototype](#apidoc.module.jsbn.default.prototype.Barrett.prototype)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>convert (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.convert)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>mulTo (x, y, r)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.mulTo)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>reduce (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>revert (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.revert)
1.  [function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>sqrTo (x, r)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.sqrTo)



# <a name="apidoc.module.jsbn"></a>[module jsbn](#apidoc.module.jsbn)

#### <a name="apidoc.element.jsbn.BigInteger"></a>[function <span class="apidocSignatureSpan">jsbn.</span>BigInteger (a, b, c)](#apidoc.element.jsbn.BigInteger)
- description and source-code
```javascript
function BigInteger(a, b, c) {
  if(a != null)
    if("number" == typeof a) this.fromNumber(a,b,c);
    else if(b == null && "string" != typeof a) this.fromString(a,256);
    else this.fromString(a,b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.SecureRandom"></a>[function <span class="apidocSignatureSpan">jsbn.</span>SecureRandom ()](#apidoc.element.jsbn.SecureRandom)
- description and source-code
```javascript
function SecureRandom() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default"></a>[function <span class="apidocSignatureSpan">jsbn.</span>default (a, b, c)](#apidoc.element.jsbn.default)
- description and source-code
```javascript
function BigInteger(a, b, c) {
  if(a != null)
    if("number" == typeof a) this.fromNumber(a,b,c);
    else if(b == null && "string" != typeof a) this.fromString(a,256);
    else this.fromString(a,b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.Barrett"></a>[function <span class="apidocSignatureSpan">jsbn.</span>default.prototype.Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett)
- description and source-code
```javascript
function Barrett(m) {
  // setup Barrett
  this.r2 = nbi();
  this.q3 = nbi();
  BigInteger.ONE.dlShiftTo(2*m.t,this.r2);
  this.mu = this.r2.divide(m);
  this.m = m;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbn.SecureRandom"></a>[module jsbn.SecureRandom](#apidoc.module.jsbn.SecureRandom)

#### <a name="apidoc.element.jsbn.SecureRandom.SecureRandom"></a>[function <span class="apidocSignatureSpan">jsbn.</span>SecureRandom ()](#apidoc.element.jsbn.SecureRandom.SecureRandom)
- description and source-code
```javascript
function SecureRandom() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbn.SecureRandom.prototype"></a>[module jsbn.SecureRandom.prototype](#apidoc.module.jsbn.SecureRandom.prototype)

#### <a name="apidoc.element.jsbn.SecureRandom.prototype.nextBytes"></a>[function <span class="apidocSignatureSpan">jsbn.SecureRandom.prototype.</span>nextBytes (ba)](#apidoc.element.jsbn.SecureRandom.prototype.nextBytes)
- description and source-code
```javascript
function rng_get_bytes(ba) {
  var i;
  for(i = 0; i < ba.length; ++i) ba[i] = rng_get_byte();
}
```
- example usage
```shell
...
      }
    }
  }
  else {
    // new BigInteger(int,RNG)
    var x = new Array(), t = a&7;
    x.length = (a>>3)+1;
    b.nextBytes(x);
    if(t > 0) x[0] &= ((1<<t)-1); else x[0] = 0;
    this.fromString(x,256);
  }
}

// (public) convert to bigendian byte array
function bnToByteArray() {
...
```



# <a name="apidoc.module.jsbn.default"></a>[module jsbn.default](#apidoc.module.jsbn.default)

#### <a name="apidoc.element.jsbn.default.default"></a>[function <span class="apidocSignatureSpan">jsbn.</span>default (a, b, c)](#apidoc.element.jsbn.default.default)
- description and source-code
```javascript
function BigInteger(a, b, c) {
  if(a != null)
    if("number" == typeof a) this.fromNumber(a,b,c);
    else if(b == null && "string" != typeof a) this.fromString(a,256);
    else this.fromString(a,b);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbn.default.prototype"></a>[module jsbn.default.prototype](#apidoc.module.jsbn.default.prototype)

#### <a name="apidoc.element.jsbn.default.prototype.Barrett"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett)
- description and source-code
```javascript
function Barrett(m) {
  // setup Barrett
  this.r2 = nbi();
  this.q3 = nbi();
  BigInteger.ONE.dlShiftTo(2*m.t,this.r2);
  this.mu = this.r2.divide(m);
  this.m = m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.abs"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>abs ()](#apidoc.element.jsbn.default.prototype.abs)
- description and source-code
```javascript
function bnAbs() { return (this.s<0)?this.negate():this; }
```
- example usage
```shell
...
  r.t = i;
  r.clamp();
}

// (protected) r = this * a, r != this,a (HAC 14.12)
// "this" should be the larger one if appropriate.
function bnpMultiplyTo(a,r) {
  var x = this.abs(), y = a.abs();
  var i = x.t;
  r.t = i+y.t;
  while(--i >= 0) r[i] = 0;
  for(i = 0; i < y.t; ++i) r[i+x.t] = x.am(0,y[i],r,i,0,x.t);
  r.s = 0;
  r.clamp();
  if(this.s != a.s) BigInteger.ZERO.subTo(r,r);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.add"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>add (a)](#apidoc.element.jsbn.default.prototype.add)
- description and source-code
```javascript
function bnAdd(a) { var r = nbi(); this.addTo(a,r); return r; }
```
- example usage
```shell
...
      if(ac) c.subTo(a,c);
      d.subTo(b,d);
    }
  }
  if(v.compareTo(BigInteger.ONE) != 0) return BigInteger.ZERO;
  if(d.compareTo(m) >= 0) return d.subtract(m);
  if(d.signum() < 0) d.addTo(m,d); else return d;
  if(d.signum() < 0) return d.add(m); else return d;
}

var lowprimes = [2,3,5,7,11,13,17,19,23,29,31,37,41,43,47,53,59,61,67,71,73,79,83,89,97,101,103,107,109,113,127,131,137,139,149,
151,157,163,167,173,179,181,191,193,197,199,211,223,227,229,233,239,241,251,257,263,269,271,277,281,283,293,307,311,313,317,331,
337,347,349,353,359,367,373,379,383,389,397,401,409,419,421,431,433,439,443,449,457,461,463,467,479,487,491,499,503,509,521,523,
541,547,557,563,569,571,577,587,593,599,601,607,613,617,619,631,641,643,647,653,659,661,673,677,683,691,701,709,719,727,733,739,
743,751,757,761,769,773,787,797,809,811,821,823,827,829,839,853,857,859,863,877,881,883,887,907,911,919,929,937,941,947,953,967,
971,977,983,991,997];
var lplim = (1<<26)/lowprimes[lowprimes.length-1];

// (public) test primality with certainty >= 1-.5^t
function bnIsProbablePrime(t) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.addTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>addTo (a, r)](#apidoc.element.jsbn.default.prototype.addTo)
- description and source-code
```javascript
function bnpAddTo(a, r) {
  var i = 0, c = 0, m = Math.min(a.t,this.t);
  while(i < m) {
    c += this[i]+a[i];
    r[i++] = c&this.DM;
    c >>= this.DB;
  }
  if(a.t < this.t) {
    c += a.s;
    while(i < this.t) {
      c += this[i];
      r[i++] = c&this.DM;
      c >>= this.DB;
    }
    c += this.s;
  }
  else {
    c += this.s;
    while(i < a.t) {
      c += a[i];
      r[i++] = c&this.DM;
      c >>= this.DB;
    }
    c += a.s;
  }
  r.s = (c<0)?-1:0;
  if(c > 0) r[i++] = c;
  else if(c < -1) r[i++] = this.DV+c;
  r.t = i;
  r.clamp();
}
```
- example usage
```shell
...
  if(c > 0) r[i++] = c;
  else if(c < -1) r[i++] = this.DV+c;
  r.t = i;
  r.clamp();
}

// (public) this + a
function bnAdd(a) { var r = nbi(); this.addTo(a,r); return r; }

// (public) this - a
function bnSubtract(a) { var r = nbi(); this.subTo(a,r); return r; }

// (public) this * a
function bnMultiply(a) { var r = nbi(); this.multiplyTo(a,r); return r; }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.am"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>am (i, x, w, j, c, n)](#apidoc.element.jsbn.default.prototype.am)
- description and source-code
```javascript
function am3(i, x, w, j, c, n) {
  var xl = x&0x3fff, xh = x>>14;
  while(--n >= 0) {
    var l = this[i]&0x3fff;
    var h = this[i++]>>14;
    var m = xh*l+h*xl;
    l = xl*l+((m&0x3fff)<<14)+w[j]+c;
    c = (l>>28)+(m>>14)+xh*h;
    w[j++] = l&0xfffffff;
  }
  return c;
}
```
- example usage
```shell
...
// (protected) r = this * a, r != this,a (HAC 14.12)
// "this" should be the larger one if appropriate.
function bnpMultiplyTo(a,r) {
  var x = this.abs(), y = a.abs();
  var i = x.t;
  r.t = i+y.t;
  while(--i >= 0) r[i] = 0;
  for(i = 0; i < y.t; ++i) r[i+x.t] = x.am(0,y[i],r,i,0,x.t);
  r.s = 0;
  r.clamp();
  if(this.s != a.s) BigInteger.ZERO.subTo(r,r);
}

// (protected) r = this^2, r != this (HAC 14.16)
function bnpSquareTo(r) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.and"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>and (a)](#apidoc.element.jsbn.default.prototype.and)
- description and source-code
```javascript
function bnAnd(a) { var r = nbi(); this.bitwiseTo(a,op_and,r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.andNot"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>andNot (a)](#apidoc.element.jsbn.default.prototype.andNot)
- description and source-code
```javascript
function bnAndNot(a) { var r = nbi(); this.bitwiseTo(a,op_andnot,r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.bitCount"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitCount ()](#apidoc.element.jsbn.default.prototype.bitCount)
- description and source-code
```javascript
function bnBitCount() {
  var r = 0, x = this.s&this.DM;
  for(var i = 0; i < this.t; ++i) r += cbit(this[i]^x);
  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.bitLength"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitLength ()](#apidoc.element.jsbn.default.prototype.bitLength)
- description and source-code
```javascript
function bnBitLength() {
  if(this.t <= 0) return 0;
  return this.DB*(this.t-1)+nbits(this[this.t-1]^(this.s&this.DM));
}
```
- example usage
```shell
...
I felt compelled to put this on github and publish to npm. I haven't tested every other big integer library out there, but the few
 that I have tested in comparison to this one have not even come close in performance. I am aware of the 'bi' module on npm, however
 it has been modified and I wanted to publish the original without modifications. This is jsbn and jsbn2 from Tom Wu's original
website above, with the module pattern applied to prevent global leaks and to allow for use with node.js on the server side.

## usage

    var BigInteger = require('jsbn').BigInteger;

    var bi = new BigInteger('91823918239182398123');
    console.log(bi.bitLength()); // 67


## API

### bi.toString()

returns the base-10 number as a string
...
```

#### <a name="apidoc.element.jsbn.default.prototype.bitwiseTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>bitwiseTo (a, op, r)](#apidoc.element.jsbn.default.prototype.bitwiseTo)
- description and source-code
```javascript
function bnpBitwiseTo(a, op, r) {
  var i, f, m = Math.min(a.t,this.t);
  for(i = 0; i < m; ++i) r[i] = op(this[i],a[i]);
  if(a.t < this.t) {
    f = a.s&this.DM;
    for(i = m; i < this.t; ++i) r[i] = op(this[i],f);
    r.t = this.t;
  }
  else {
    f = this.s&this.DM;
    for(i = m; i < a.t; ++i) r[i] = op(f,a[i]);
    r.t = a.t;
  }
  r.s = op(this.s,a.s);
  r.clamp();
}
```
- example usage
```shell
...
    function bnpFromNumber(a,b,c) {
if("number" == typeof b) {
  // new BigInteger(int,int,RNG)
  if(a < 2) this.fromInt(1);
  else {
    this.fromNumber(a,c);
    if(!this.testBit(a-1))    // force MSB set
      this.bitwiseTo(BigInteger.ONE.shiftLeft(a-1),op_or,this);
    if(this.isEven()) this.dAddOffset(1,0); // force odd
    while(!this.isProbablePrime(b)) {
      this.dAddOffset(2,0);
      if(this.bitLength() > a) this.subTo(BigInteger.ONE.shiftLeft(a-1),this);
    }
  }
}
...
```

#### <a name="apidoc.element.jsbn.default.prototype.byteValue"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>byteValue ()](#apidoc.element.jsbn.default.prototype.byteValue)
- description and source-code
```javascript
function bnByteValue() { return (this.t==0)?this.s:(this[0]<<24)>>24; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.changeBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>changeBit (n, op)](#apidoc.element.jsbn.default.prototype.changeBit)
- description and source-code
```javascript
function bnpChangeBit(n, op) {
  var r = BigInteger.ONE.shiftLeft(n);
  this.bitwiseTo(r,op,r);
  return r;
}
```
- example usage
```shell
...
function bnpChangeBit(n,op) {
  var r = BigInteger.ONE.shiftLeft(n);
  this.bitwiseTo(r,op,r);
  return r;
}

// (public) this | (1<<n)
function bnSetBit(n) { return this.changeBit(n,op_or); }

// (public) this & ~(1<<n)
function bnClearBit(n) { return this.changeBit(n,op_andnot); }

// (public) this ^ (1<<n)
function bnFlipBit(n) { return this.changeBit(n,op_xor); }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.chunkSize"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>chunkSize (r)](#apidoc.element.jsbn.default.prototype.chunkSize)
- description and source-code
```javascript
function bnpChunkSize(r) { return Math.floor(Math.LN2*this.DB/Math.log(r)); }
```
- example usage
```shell
...
  else return 1;
}

// (protected) convert to radix string
function bnpToRadix(b) {
  if(b == null) b = 10;
  if(this.signum() == 0 || b < 2 || b > 36) return "0";
  var cs = this.chunkSize(b);
  var a = Math.pow(b,cs);
  var d = nbv(a), y = nbi(), z = nbi(), r = "";
  this.divRemTo(d,y,z);
  while(y.signum() > 0) {
    r = (a+z.intValue()).toString(b).substr(1) + r;
    y.divRemTo(d,y,z);
  }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.clamp"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clamp ()](#apidoc.element.jsbn.default.prototype.clamp)
- description and source-code
```javascript
function bnpClamp() {
  var c = this.s&this.DM;
  while(this.t > 0 && this[this.t-1] == c) --this.t;
}
```
- example usage
```shell
...
    sh += k;
    if(sh >= this.DB) sh -= this.DB;
  }
  if(k == 8 && (s[0]&0x80) != 0) {
    this.s = -1;
    if(sh > 0) this[this.t-1] |= ((1<<(this.DB-sh))-1)<<sh;
  }
  this.clamp();
  if(mi) BigInteger.ZERO.subTo(this,this);
}

// (protected) clamp off excess high words
function bnpClamp() {
  var c = this.s&this.DM;
  while(this.t > 0 && this[this.t-1] == c) --this.t;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.clearBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clearBit (n)](#apidoc.element.jsbn.default.prototype.clearBit)
- description and source-code
```javascript
function bnClearBit(n) { return this.changeBit(n,op_andnot); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.clone"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>clone ()](#apidoc.element.jsbn.default.prototype.clone)
- description and source-code
```javascript
function bnClone() { var r = nbi(); this.copyTo(r); return r; }
```
- example usage
```shell
...
    }
  }
  return z.revert(r);
}

// (public) gcd(this,a) (HAC 14.54)
function bnGCD(a) {
  var x = (this.s<0)?this.negate():this.clone();
  var y = (a.s<0)?a.negate():a.clone();
  if(x.compareTo(y) < 0) { var t = x; x = y; y = t; }
  var i = x.getLowestSetBit(), g = y.getLowestSetBit();
  if(g < 0) return x;
  if(i < g) g = i;
  if(g > 0) {
    x.rShiftTo(g,x);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.compareTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>compareTo (a)](#apidoc.element.jsbn.default.prototype.compareTo)
- description and source-code
```javascript
function bnCompareTo(a) {
  var r = this.s-a.s;
  if(r != 0) return r;
  var i = this.t;
  r = i-a.t;
  if(r != 0) return (this.s<0)?-r:r;
  while(--i >= 0) if((r=this[i]-a[i]) != 0) return r;
  return 0;
}
```
- example usage
```shell
...
var ys = y.t;
var y0 = y[ys-1];
if(y0 == 0) return;
var yt = y0*(1<<this.F1)+((ys>1)?y[ys-2]>>this.F2:0);
var d1 = this.FV/yt, d2 = (1<<this.F1)/yt, e = 1<<this.F2;
var i = r.t, j = i-ys, t = (q==null)?nbi():q;
y.dlShiftTo(j,t);
if(r.compareTo(t) >= 0) {
  r[r.t++] = 1;
  r.subTo(t,r);
}
BigInteger.ONE.dlShiftTo(ys,t);
t.subTo(y,y);  // "negative" y so we can replace sub with am later
while(y.t < ys) y[y.t++] = 0;
while(--j >= 0) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.copyTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>copyTo (r)](#apidoc.element.jsbn.default.prototype.copyTo)
- description and source-code
```javascript
function bnpCopyTo(r) {
  for(var i = this.t-1; i >= 0; --i) r[i] = this[i];
  r.t = this.t;
  r.s = this.s;
}
```
- example usage
```shell
...
// r != q, this != m.  q or r may be null.
function bnpDivRemTo(m,q,r) {
  var pm = m.abs();
  if(pm.t <= 0) return;
  var pt = this.abs();
  if(pt.t < pm.t) {
    if(q != null) q.fromInt(0);
    if(r != null) this.copyTo(r);
    return;
  }
  if(r == null) r = nbi();
  var y = nbi(), ts = this.s, ms = m.s;
  var nsh = this.DB-nbits(pm[pm.t-1]);   // normalize modulus
  if(nsh > 0) { pm.lShiftTo(nsh,y); pt.lShiftTo(nsh,r); }
  else { pm.copyTo(y); pt.copyTo(r); }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.dAddOffset"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dAddOffset (n, w)](#apidoc.element.jsbn.default.prototype.dAddOffset)
- description and source-code
```javascript
function bnpDAddOffset(n, w) {
  if(n == 0) return;
  while(this.t <= w) this[this.t++] = 0;
  this[w] += n;
  while(this[w] >= this.DV) {
    this[w] -= this.DV;
    if(++w >= this.t) this[this.t++] = 0;
    ++this[w];
  }
}
```
- example usage
```shell
...
  if(x < 0) {
    if(s.charAt(i) == "-" && this.signum() == 0) mi = true;
    continue;
  }
  w = b*w+x;
  if(++j >= cs) {
    this.dMultiply(d);
    this.dAddOffset(w,0);
    j = 0;
    w = 0;
  }
}
if(j > 0) {
  this.dMultiply(Math.pow(b,j));
  this.dAddOffset(w,0);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.dMultiply"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dMultiply (n)](#apidoc.element.jsbn.default.prototype.dMultiply)
- description and source-code
```javascript
function bnpDMultiply(n) {
  this[this.t] = this.am(0,n-1,this,0,0,this.t);
  ++this.t;
  this.clamp();
}
```
- example usage
```shell
...
  var x = intAt(s,i);
  if(x < 0) {
    if(s.charAt(i) == "-" && this.signum() == 0) mi = true;
    continue;
  }
  w = b*w+x;
  if(++j >= cs) {
    this.dMultiply(d);
    this.dAddOffset(w,0);
    j = 0;
    w = 0;
  }
}
if(j > 0) {
  this.dMultiply(Math.pow(b,j));
...
```

#### <a name="apidoc.element.jsbn.default.prototype.divRemTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divRemTo (m, q, r)](#apidoc.element.jsbn.default.prototype.divRemTo)
- description and source-code
```javascript
function bnpDivRemTo(m, q, r) {
  var pm = m.abs();
  if(pm.t <= 0) return;
  var pt = this.abs();
  if(pt.t < pm.t) {
    if(q != null) q.fromInt(0);
    if(r != null) this.copyTo(r);
    return;
  }
  if(r == null) r = nbi();
  var y = nbi(), ts = this.s, ms = m.s;
  var nsh = this.DB-nbits(pm[pm.t-1]);   // normalize modulus
  if(nsh > 0) { pm.lShiftTo(nsh,y); pt.lShiftTo(nsh,r); }
  else { pm.copyTo(y); pt.copyTo(r); }
  var ys = y.t;
  var y0 = y[ys-1];
  if(y0 == 0) return;
  var yt = y0*(1<<this.F1)+((ys>1)?y[ys-2]>>this.F2:0);
  var d1 = this.FV/yt, d2 = (1<<this.F1)/yt, e = 1<<this.F2;
  var i = r.t, j = i-ys, t = (q==null)?nbi():q;
  y.dlShiftTo(j,t);
  if(r.compareTo(t) >= 0) {
    r[r.t++] = 1;
    r.subTo(t,r);
  }
  BigInteger.ONE.dlShiftTo(ys,t);
  t.subTo(y,y);  // "negative" y so we can replace sub with am later
  while(y.t < ys) y[y.t++] = 0;
  while(--j >= 0) {
    // Estimate quotient digit
    var qd = (r[--i]==y0)?this.DM:Math.floor(r[i]*d1+(r[i-1]+e)*d2);
    if((r[i]+=y.am(0,qd,r,j,0,ys)) < qd) {   // Try it out
      y.dlShiftTo(j,t);
      r.subTo(t,r);
      while(r[i] < --qd) r.subTo(t,r);
    }
  }
  if(q != null) {
    r.drShiftTo(ys,q);
    if(ts != ms) BigInteger.ZERO.subTo(q,q);
  }
  r.t = ys;
  r.clamp();
  if(nsh > 0) r.rShiftTo(nsh,r); // Denormalize remainder
  if(ts < 0) BigInteger.ZERO.subTo(r,r);
}
```
- example usage
```shell
...
  if(nsh > 0) r.rShiftTo(nsh,r); // Denormalize remainder
  if(ts < 0) BigInteger.ZERO.subTo(r,r);
}

// (public) this mod a
function bnMod(a) {
  var r = nbi();
  this.abs().divRemTo(a,null,r);
  if(this.s < 0 && r.compareTo(BigInteger.ZERO) > 0) a.subTo(r,r);
  return r;
}

// Modular reduction using "classic" algorithm
function Classic(m) { this.m = m; }
function cConvert(x) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.divide"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divide (a)](#apidoc.element.jsbn.default.prototype.divide)
- description and source-code
```javascript
function bnDivide(a) { var r = nbi(); this.divRemTo(a,r,null); return r; }
```
- example usage
```shell
...

// Barrett modular reduction
function Barrett(m) {
  // setup Barrett
  this.r2 = nbi();
  this.q3 = nbi();
  BigInteger.ONE.dlShiftTo(2*m.t,this.r2);
  this.mu = this.r2.divide(m);
  this.m = m;
}

function barrettConvert(x) {
  if(x.s < 0 || x.t > 2*this.m.t) return x.mod(this.m);
  else if(x.compareTo(this.m) < 0) return x;
  else { var r = nbi(); x.copyTo(r); this.reduce(r); return r; }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.divideAndRemainder"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>divideAndRemainder (a)](#apidoc.element.jsbn.default.prototype.divideAndRemainder)
- description and source-code
```javascript
function bnDivideAndRemainder(a) {
  var q = nbi(), r = nbi();
  this.divRemTo(a,q,r);
  return new Array(q,r);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.dlShiftTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>dlShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.dlShiftTo)
- description and source-code
```javascript
function bnpDLShiftTo(n, r) {
  var i;
  for(i = this.t-1; i >= 0; --i) r[i+n] = this[i];
  for(i = n-1; i >= 0; --i) r[i] = 0;
  r.t = this.t+n;
  r.s = this.s;
}
```
- example usage
```shell
...
else { pm.copyTo(y); pt.copyTo(r); }
var ys = y.t;
var y0 = y[ys-1];
if(y0 == 0) return;
var yt = y0*(1<<this.F1)+((ys>1)?y[ys-2]>>this.F2:0);
var d1 = this.FV/yt, d2 = (1<<this.F1)/yt, e = 1<<this.F2;
var i = r.t, j = i-ys, t = (q==null)?nbi():q;
y.dlShiftTo(j,t);
if(r.compareTo(t) >= 0) {
  r[r.t++] = 1;
  r.subTo(t,r);
}
BigInteger.ONE.dlShiftTo(ys,t);
t.subTo(y,y);  // "negative" y so we can replace sub with am later
while(y.t < ys) y[y.t++] = 0;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.drShiftTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>drShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.drShiftTo)
- description and source-code
```javascript
function bnpDRShiftTo(n, r) {
  for(var i = n; i < this.t; ++i) r[i-n] = this[i];
  r.t = Math.max(this.t-n,0);
  r.s = this.s;
}
```
- example usage
```shell
...
    if((r[i]+=y.am(0,qd,r,j,0,ys)) < qd) {   // Try it out
      y.dlShiftTo(j,t);
      r.subTo(t,r);
      while(r[i] < --qd) r.subTo(t,r);
    }
  }
  if(q != null) {
    r.drShiftTo(ys,q);
    if(ts != ms) BigInteger.ZERO.subTo(q,q);
  }
  r.t = ys;
  r.clamp();
  if(nsh > 0) r.rShiftTo(nsh,r); // Denormalize remainder
  if(ts < 0) BigInteger.ZERO.subTo(r,r);
}
...
```

#### <a name="apidoc.element.jsbn.default.prototype.equals"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>equals (a)](#apidoc.element.jsbn.default.prototype.equals)
- description and source-code
```javascript
function bnEquals(a) { return(this.compareTo(a)==0); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.exp"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>exp (e, z)](#apidoc.element.jsbn.default.prototype.exp)
- description and source-code
```javascript
function bnpExp(e, z) {
  if(e > 0xffffffff || e < 1) return BigInteger.ONE;
  var r = nbi(), r2 = nbi(), g = z.convert(this), i = nbits(e)-1;
  g.copyTo(r);
  while(--i >= 0) {
    z.sqrTo(r,r2);
    if((e&(1<<i)) > 0) z.mulTo(r2,g,r);
    else { var t = r; r = r2; r2 = t; }
  }
  return z.revert(r);
}
```
- example usage
```shell
...
  return z.revert(r);
}

// (public) this^e % m, 0 <= e < 2^32
function bnModPowInt(e,m) {
  var z;
  if(e < 256 || m.isEven()) z = new Classic(m); else z = new Montgomery(m);
  return this.exp(e,z);
}

// protected
BigInteger.prototype.copyTo = bnpCopyTo;
BigInteger.prototype.fromInt = bnpFromInt;
BigInteger.prototype.fromString = bnpFromString;
BigInteger.prototype.clamp = bnpClamp;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.flipBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>flipBit (n)](#apidoc.element.jsbn.default.prototype.flipBit)
- description and source-code
```javascript
function bnFlipBit(n) { return this.changeBit(n,op_xor); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.fromInt"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromInt (x)](#apidoc.element.jsbn.default.prototype.fromInt)
- description and source-code
```javascript
function bnpFromInt(x) {
  this.t = 1;
  this.s = (x<0)?-1:0;
  if(x > 0) this[0] = x;
  else if(x < -1) this[0] = x+this.DV;
  else this.t = 0;
}
```
- example usage
```shell
...
  this.s = (x<0)?-1:0;
  if(x > 0) this[0] = x;
  else if(x < -1) this[0] = x+this.DV;
  else this.t = 0;
}

// return bigint initialized to value
function nbv(i) { var r = nbi(); r.fromInt(i); return r; }

// (protected) set from string and radix
function bnpFromString(s,b) {
  var k;
  if(b == 16) k = 4;
  else if(b == 8) k = 3;
  else if(b == 256) k = 8; // byte array
...
```

#### <a name="apidoc.element.jsbn.default.prototype.fromNumber"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromNumber (a, b, c)](#apidoc.element.jsbn.default.prototype.fromNumber)
- description and source-code
```javascript
function bnpFromNumber(a, b, c) {
  if("number" == typeof b) {
    // new BigInteger(int,int,RNG)
    if(a < 2) this.fromInt(1);
    else {
      this.fromNumber(a,c);
      if(!this.testBit(a-1))    // force MSB set
        this.bitwiseTo(BigInteger.ONE.shiftLeft(a-1),op_or,this);
      if(this.isEven()) this.dAddOffset(1,0); // force odd
      while(!this.isProbablePrime(b)) {
        this.dAddOffset(2,0);
        if(this.bitLength() > a) this.subTo(BigInteger.ONE.shiftLeft(a-1),this);
      }
    }
  }
  else {
    // new BigInteger(int,RNG)
    var x = new Array(), t = a&7;
    x.length = (a>>3)+1;
    b.nextBytes(x);
    if(t > 0) x[0] &= ((1<<t)-1); else x[0] = 0;
    this.fromString(x,256);
  }
}
```
- example usage
```shell
...
// JavaScript engine analysis
var canary = 0xdeadbeefcafe;
var j_lm = ((canary&0xffffff)==0xefcafe);

// (public) Constructor
function BigInteger(a,b,c) {
  if(a != null)
    if("number" == typeof a) this.fromNumber(a,b,c);
    else if(b == null && "string" != typeof a) this.fromString(a,256);
    else this.fromString(a,b);
}

// return new, unset BigInteger
function nbi() { return new BigInteger(null); }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.fromRadix"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromRadix (s, b)](#apidoc.element.jsbn.default.prototype.fromRadix)
- description and source-code
```javascript
function bnpFromRadix(s, b) {
  this.fromInt(0);
  if(b == null) b = 10;
  var cs = this.chunkSize(b);
  var d = Math.pow(b,cs), mi = false, j = 0, w = 0;
  for(var i = 0; i < s.length; ++i) {
    var x = intAt(s,i);
    if(x < 0) {
      if(s.charAt(i) == "-" && this.signum() == 0) mi = true;
      continue;
    }
    w = b*w+x;
    if(++j >= cs) {
      this.dMultiply(d);
      this.dAddOffset(w,0);
      j = 0;
      w = 0;
    }
  }
  if(j > 0) {
    this.dMultiply(Math.pow(b,j));
    this.dAddOffset(w,0);
  }
  if(mi) BigInteger.ZERO.subTo(this,this);
}
```
- example usage
```shell
...
var k;
if(b == 16) k = 4;
else if(b == 8) k = 3;
else if(b == 256) k = 8; // byte array
else if(b == 2) k = 1;
else if(b == 32) k = 5;
else if(b == 4) k = 2;
else { this.fromRadix(s,b); return; }
this.t = 0;
this.s = 0;
var i = s.length, mi = false, sh = 0;
while(--i >= 0) {
  var x = (k==8)?s[i]&0xff:intAt(s,i);
  if(x < 0) {
    if(s.charAt(i) == "-") mi = true;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.fromString"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>fromString (s, b)](#apidoc.element.jsbn.default.prototype.fromString)
- description and source-code
```javascript
function bnpFromString(s, b) {
  var k;
  if(b == 16) k = 4;
  else if(b == 8) k = 3;
  else if(b == 256) k = 8; // byte array
  else if(b == 2) k = 1;
  else if(b == 32) k = 5;
  else if(b == 4) k = 2;
  else { this.fromRadix(s,b); return; }
  this.t = 0;
  this.s = 0;
  var i = s.length, mi = false, sh = 0;
  while(--i >= 0) {
    var x = (k==8)?s[i]&0xff:intAt(s,i);
    if(x < 0) {
      if(s.charAt(i) == "-") mi = true;
      continue;
    }
    mi = false;
    if(sh == 0)
      this[this.t++] = x;
    else if(sh+k > this.DB) {
      this[this.t-1] |= (x&((1<<(this.DB-sh))-1))<<sh;
      this[this.t++] = (x>>(this.DB-sh));
    }
    else
      this[this.t-1] |= x<<sh;
    sh += k;
    if(sh >= this.DB) sh -= this.DB;
  }
  if(k == 8 && (s[0]&0x80) != 0) {
    this.s = -1;
    if(sh > 0) this[this.t-1] |= ((1<<(this.DB-sh))-1)<<sh;
  }
  this.clamp();
  if(mi) BigInteger.ZERO.subTo(this,this);
}
```
- example usage
```shell
...
var canary = 0xdeadbeefcafe;
var j_lm = ((canary&0xffffff)==0xefcafe);

// (public) Constructor
function BigInteger(a,b,c) {
  if(a != null)
    if("number" == typeof a) this.fromNumber(a,b,c);
    else if(b == null && "string" != typeof a) this.fromString(a,256);
    else this.fromString(a,b);
}

// return new, unset BigInteger
function nbi() { return new BigInteger(null); }

// am: Compute w_j += (x*this_i), propagate carries,
...
```

#### <a name="apidoc.element.jsbn.default.prototype.gcd"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>gcd (a)](#apidoc.element.jsbn.default.prototype.gcd)
- description and source-code
```javascript
function bnGCD(a) {
  var x = (this.s<0)?this.negate():this.clone();
  var y = (a.s<0)?a.negate():a.clone();
  if(x.compareTo(y) < 0) { var t = x; x = y; y = t; }
  var i = x.getLowestSetBit(), g = y.getLowestSetBit();
  if(g < 0) return x;
  if(i < g) g = i;
  if(g > 0) {
    x.rShiftTo(g,x);
    y.rShiftTo(g,y);
  }
  while(x.signum() > 0) {
    if((i = x.getLowestSetBit()) > 0) x.rShiftTo(i,x);
    if((i = y.getLowestSetBit()) > 0) y.rShiftTo(i,y);
    if(x.compareTo(y) >= 0) {
      x.subTo(y,x);
      x.rShiftTo(1,x);
    }
    else {
      y.subTo(x,y);
      y.rShiftTo(1,y);
    }
  }
  if(g > 0) y.lShiftTo(g,y);
  return y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.getLowestSetBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>getLowestSetBit ()](#apidoc.element.jsbn.default.prototype.getLowestSetBit)
- description and source-code
```javascript
function bnGetLowestSetBit() {
  for(var i = 0; i < this.t; ++i)
    if(this[i] != 0) return i*this.DB+lbit(this[i]);
  if(this.s < 0) return this.t*this.DB;
  return -1;
}
```
- example usage
```shell
...
}

// (public) gcd(this,a) (HAC 14.54)
function bnGCD(a) {
  var x = (this.s<0)?this.negate():this.clone();
  var y = (a.s<0)?a.negate():a.clone();
  if(x.compareTo(y) < 0) { var t = x; x = y; y = t; }
  var i = x.getLowestSetBit(), g = y.getLowestSetBit();
  if(g < 0) return x;
  if(i < g) g = i;
  if(g > 0) {
    x.rShiftTo(g,x);
    y.rShiftTo(g,y);
  }
  while(x.signum() > 0) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.intValue"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>intValue ()](#apidoc.element.jsbn.default.prototype.intValue)
- description and source-code
```javascript
function bnIntValue() {
  if(this.s < 0) {
    if(this.t == 1) return this[0]-this.DV;
    else if(this.t == 0) return -1;
  }
  else if(this.t == 1) return this[0];
  else if(this.t == 0) return 0;
  // assumes 16 < DB < 32
  return ((this[1]&((1<<(32-this.DB))-1))<<this.DB)|this[0];
}
```
- example usage
```shell
...
  if(b == null) b = 10;
  if(this.signum() == 0 || b < 2 || b > 36) return "0";
  var cs = this.chunkSize(b);
  var a = Math.pow(b,cs);
  var d = nbv(a), y = nbi(), z = nbi(), r = "";
  this.divRemTo(d,y,z);
  while(y.signum() > 0) {
    r = (a+z.intValue()).toString(b).substr(1) + r;
    y.divRemTo(d,y,z);
  }
  return z.intValue().toString(b) + r;
}

// (protected) convert from radix string
function bnpFromRadix(s,b) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.invDigit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>invDigit ()](#apidoc.element.jsbn.default.prototype.invDigit)
- description and source-code
```javascript
function bnpInvDigit() {
  if(this.t < 1) return 0;
  var x = this[0];
  if((x&1) == 0) return 0;
  var y = x&3;       // y == 1/x mod 2^2
  y = (y*(2-(x&0xf)*y))&0xf; // y == 1/x mod 2^4
  y = (y*(2-(x&0xff)*y))&0xff;   // y == 1/x mod 2^8
  y = (y*(2-(((x&0xffff)*y)&0xffff)))&0xffff;    // y == 1/x mod 2^16
  // last step - calculate inverse mod DV directly;
  // assumes 16 < DB <= 32 and assumes ability to handle 48-bit ints
  y = (y*(2-x*y%this.DV))%this.DV;       // y == 1/x mod 2^dbits
  // we really want the negative inverse, and -DV < y < DV
  return (y>0)?this.DV-y:-y;
}
```
- example usage
```shell
...
  // we really want the negative inverse, and -DV < y < DV
  return (y>0)?this.DV-y:-y;
}

// Montgomery reduction
function Montgomery(m) {
  this.m = m;
  this.mp = m.invDigit();
  this.mpl = this.mp&0x7fff;
  this.mph = this.mp>>15;
  this.um = (1<<(m.DB-15))-1;
  this.mt2 = 2*m.t;
}

// xR mod m
...
```

#### <a name="apidoc.element.jsbn.default.prototype.isEven"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>isEven ()](#apidoc.element.jsbn.default.prototype.isEven)
- description and source-code
```javascript
function bnpIsEven() { return ((this.t>0)?(this[0]&1):this.s) == 0; }
```
- example usage
```shell
...
  }
  return z.revert(r);
}

// (public) this^e % m, 0 <= e < 2^32
function bnModPowInt(e,m) {
  var z;
  if(e < 256 || m.isEven()) z = new Classic(m); else z = new Montgomery(m);
  return this.exp(e,z);
}

// protected
BigInteger.prototype.copyTo = bnpCopyTo;
BigInteger.prototype.fromInt = bnpFromInt;
BigInteger.prototype.fromString = bnpFromString;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.isProbablePrime"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>isProbablePrime (t)](#apidoc.element.jsbn.default.prototype.isProbablePrime)
- description and source-code
```javascript
function bnIsProbablePrime(t) {
  var i, x = this.abs();
  if(x.t == 1 && x[0] <= lowprimes[lowprimes.length-1]) {
    for(i = 0; i < lowprimes.length; ++i)
      if(x[0] == lowprimes[i]) return true;
    return false;
  }
  if(x.isEven()) return false;
  i = 1;
  while(i < lowprimes.length) {
    var m = lowprimes[i], j = i+1;
    while(j < lowprimes.length && m < lplim) m *= lowprimes[j++];
    m = x.modInt(m);
    while(i < j) if(m%lowprimes[i++] == 0) return false;
  }
  return x.millerRabin(t);
}
```
- example usage
```shell
...
  // new BigInteger(int,int,RNG)
  if(a < 2) this.fromInt(1);
  else {
    this.fromNumber(a,c);
    if(!this.testBit(a-1))    // force MSB set
      this.bitwiseTo(BigInteger.ONE.shiftLeft(a-1),op_or,this);
    if(this.isEven()) this.dAddOffset(1,0); // force odd
    while(!this.isProbablePrime(b)) {
      this.dAddOffset(2,0);
      if(this.bitLength() > a) this.subTo(BigInteger.ONE.shiftLeft(a-1),this);
    }
  }
}
else {
  // new BigInteger(int,RNG)
...
```

#### <a name="apidoc.element.jsbn.default.prototype.lShiftTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>lShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.lShiftTo)
- description and source-code
```javascript
function bnpLShiftTo(n, r) {
  var bs = n%this.DB;
  var cbs = this.DB-bs;
  var bm = (1<<cbs)-1;
  var ds = Math.floor(n/this.DB), c = (this.s<<bs)&this.DM, i;
  for(i = this.t-1; i >= 0; --i) {
    r[i+ds+1] = (this[i]>>cbs)|c;
    c = (this[i]&bm)<<bs;
  }
  for(i = ds-1; i >= 0; --i) r[i] = 0;
  r[ds] = c;
  r.t = this.t+ds+1;
  r.s = this.s;
  r.clamp();
}
```
- example usage
```shell
...
  if(q != null) q.fromInt(0);
  if(r != null) this.copyTo(r);
  return;
}
if(r == null) r = nbi();
var y = nbi(), ts = this.s, ms = m.s;
var nsh = this.DB-nbits(pm[pm.t-1]);   // normalize modulus
if(nsh > 0) { pm.lShiftTo(nsh,y); pt.lShiftTo(nsh,r); }
else { pm.copyTo(y); pt.copyTo(r); }
var ys = y.t;
var y0 = y[ys-1];
if(y0 == 0) return;
var yt = y0*(1<<this.F1)+((ys>1)?y[ys-2]>>this.F2:0);
var d1 = this.FV/yt, d2 = (1<<this.F1)/yt, e = 1<<this.F2;
var i = r.t, j = i-ys, t = (q==null)?nbi():q;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.max"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>max (a)](#apidoc.element.jsbn.default.prototype.max)
- description and source-code
```javascript
function bnMax(a) { return(this.compareTo(a)>0)?this:a; }
```
- example usage
```shell
...
  r.t = this.t+n;
  r.s = this.s;
}

// (protected) r = this >> n*DB
function bnpDRShiftTo(n,r) {
  for(var i = n; i < this.t; ++i) r[i-n] = this[i];
  r.t = Math.max(this.t-n,0);
  r.s = this.s;
}

// (protected) r = this << n
function bnpLShiftTo(n,r) {
  var bs = n%this.DB;
  var cbs = this.DB-bs;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.millerRabin"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>millerRabin (t)](#apidoc.element.jsbn.default.prototype.millerRabin)
- description and source-code
```javascript
function bnpMillerRabin(t) {
  var n1 = this.subtract(BigInteger.ONE);
  var k = n1.getLowestSetBit();
  if(k <= 0) return false;
  var r = n1.shiftRight(k);
  t = (t+1)>>1;
  if(t > lowprimes.length) t = lowprimes.length;
  var a = nbi();
  for(var i = 0; i < t; ++i) {
    //Pick bases at random, instead of starting at 2
    a.fromInt(lowprimes[Math.floor(Math.random()*lowprimes.length)]);
    var y = a.modPow(r,this);
    if(y.compareTo(BigInteger.ONE) != 0 && y.compareTo(n1) != 0) {
      var j = 1;
      while(j++ < k && y.compareTo(n1) != 0) {
        y = y.modPowInt(2,this);
        if(y.compareTo(BigInteger.ONE) == 0) return false;
      }
      if(y.compareTo(n1) != 0) return false;
    }
  }
  return true;
}
```
- example usage
```shell
...
  i = 1;
  while(i < lowprimes.length) {
    var m = lowprimes[i], j = i+1;
    while(j < lowprimes.length && m < lplim) m *= lowprimes[j++];
    m = x.modInt(m);
    while(i < j) if(m%lowprimes[i++] == 0) return false;
  }
  return x.millerRabin(t);
}

// (protected) true if probably prime (HAC 4.24, Miller-Rabin)
function bnpMillerRabin(t) {
  var n1 = this.subtract(BigInteger.ONE);
  var k = n1.getLowestSetBit();
  if(k <= 0) return false;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.min"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>min (a)](#apidoc.element.jsbn.default.prototype.min)
- description and source-code
```javascript
function bnMin(a) { return(this.compareTo(a)<0)?this:a; }
```
- example usage
```shell
...
  if(bs > 0) r[this.t-ds-1] |= (this.s&bm)<<cbs;
  r.t = this.t-ds;
  r.clamp();
}

// (protected) r = this - a
function bnpSubTo(a,r) {
  var i = 0, c = 0, m = Math.min(a.t,this.t);
  while(i < m) {
    c += this[i]-a[i];
    r[i++] = c&this.DM;
    c >>= this.DB;
  }
  if(a.t < this.t) {
    c -= a.s;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.mod"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>mod (a)](#apidoc.element.jsbn.default.prototype.mod)
- description and source-code
```javascript
function bnMod(a) {
  var r = nbi();
  this.abs().divRemTo(a,null,r);
  if(this.s < 0 && r.compareTo(BigInteger.ZERO) > 0) a.subTo(r,r);
  return r;
}
```
- example usage
```shell
...
  if(this.s < 0 && r.compareTo(BigInteger.ZERO) > 0) a.subTo(r,r);
  return r;
}

// Modular reduction using "classic" algorithm
function Classic(m) { this.m = m; }
function cConvert(x) {
  if(x.s < 0 || x.compareTo(this.m) >= 0) return x.mod(this.m);
  else return x;
}
function cRevert(x) { return x; }
function cReduce(x) { x.divRemTo(this.m,null,x); }
function cMulTo(x,y,r) { x.multiplyTo(y,r); this.reduce(r); }
function cSqrTo(x,r) { x.squareTo(r); this.reduce(r); }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.modInt"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modInt (n)](#apidoc.element.jsbn.default.prototype.modInt)
- description and source-code
```javascript
function bnpModInt(n) {
  if(n <= 0) return 0;
  var d = this.DV%n, r = (this.s<0)?n-1:0;
  if(this.t > 0)
    if(d == 0) r = this[0]%n;
    else for(var i = this.t-1; i >= 0; --i) r = (d*r+this[i])%n;
  return r;
}
```
- example usage
```shell
...
    return false;
  }
  if(x.isEven()) return false;
  i = 1;
  while(i < lowprimes.length) {
    var m = lowprimes[i], j = i+1;
    while(j < lowprimes.length && m < lplim) m *= lowprimes[j++];
    m = x.modInt(m);
    while(i < j) if(m%lowprimes[i++] == 0) return false;
  }
  return x.millerRabin(t);
}

// (protected) true if probably prime (HAC 4.24, Miller-Rabin)
function bnpMillerRabin(t) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.modInverse"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modInverse (m)](#apidoc.element.jsbn.default.prototype.modInverse)
- description and source-code
```javascript
function bnModInverse(m) {
  var ac = m.isEven();
  if((this.isEven() && ac) || m.signum() == 0) return BigInteger.ZERO;
  var u = m.clone(), v = this.clone();
  var a = nbv(1), b = nbv(0), c = nbv(0), d = nbv(1);
  while(u.signum() != 0) {
    while(u.isEven()) {
      u.rShiftTo(1,u);
      if(ac) {
        if(!a.isEven() || !b.isEven()) { a.addTo(this,a); b.subTo(m,b); }
        a.rShiftTo(1,a);
      }
      else if(!b.isEven()) b.subTo(m,b);
      b.rShiftTo(1,b);
    }
    while(v.isEven()) {
      v.rShiftTo(1,v);
      if(ac) {
        if(!c.isEven() || !d.isEven()) { c.addTo(this,c); d.subTo(m,d); }
        c.rShiftTo(1,c);
      }
      else if(!d.isEven()) d.subTo(m,d);
      d.rShiftTo(1,d);
    }
    if(u.compareTo(v) >= 0) {
      u.subTo(v,u);
      if(ac) a.subTo(c,a);
      b.subTo(d,b);
    }
    else {
      v.subTo(u,v);
      if(ac) c.subTo(a,c);
      d.subTo(b,d);
    }
  }
  if(v.compareTo(BigInteger.ONE) != 0) return BigInteger.ZERO;
  if(d.compareTo(m) >= 0) return d.subtract(m);
  if(d.signum() < 0) d.addTo(m,d); else return d;
  if(d.signum() < 0) return d.add(m); else return d;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.modPow"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modPow (e, m)](#apidoc.element.jsbn.default.prototype.modPow)
- description and source-code
```javascript
function bnModPow(e, m) {
  var i = e.bitLength(), k, r = nbv(1), z;
  if(i <= 0) return r;
  else if(i < 18) k = 1;
  else if(i < 48) k = 3;
  else if(i < 144) k = 4;
  else if(i < 768) k = 5;
  else k = 6;
  if(i < 8)
    z = new Classic(m);
  else if(m.isEven())
    z = new Barrett(m);
  else
    z = new Montgomery(m);

  // precomputation
  var g = new Array(), n = 3, k1 = k-1, km = (1<<k)-1;
  g[1] = z.convert(this);
  if(k > 1) {
    var g2 = nbi();
    z.sqrTo(g[1],g2);
    while(n <= km) {
      g[n] = nbi();
      z.mulTo(g2,g[n-2],g[n]);
      n += 2;
    }
  }

  var j = e.t-1, w, is1 = true, r2 = nbi(), t;
  i = nbits(e[j])-1;
  while(j >= 0) {
    if(i >= k1) w = (e[j]>>(i-k1))&km;
    else {
      w = (e[j]&((1<<(i+1))-1))<<(k1-i);
      if(j > 0) w |= e[j-1]>>(this.DB+i-k1);
    }

    n = k;
    while((w&1) == 0) { w >>= 1; --n; }
    if((i -= n) < 0) { i += this.DB; --j; }
    if(is1) {    // ret == 1, don't bother squaring or multiplying it
      g[w].copyTo(r);
      is1 = false;
    }
    else {
      while(n > 1) { z.sqrTo(r,r2); z.sqrTo(r2,r); n -= 2; }
      if(n > 0) z.sqrTo(r,r2); else { t = r; r = r2; r2 = t; }
      z.mulTo(r2,g[w],r);
    }

    while(j >= 0 && (e[j]&(1<<i)) == 0) {
      z.sqrTo(r,r2); t = r; r = r2; r2 = t;
      if(--i < 0) { i = this.DB-1; --j; }
    }
  }
  return z.revert(r);
}
```
- example usage
```shell
...
var r = n1.shiftRight(k);
t = (t+1)>>1;
if(t > lowprimes.length) t = lowprimes.length;
var a = nbi();
for(var i = 0; i < t; ++i) {
  //Pick bases at random, instead of starting at 2
  a.fromInt(lowprimes[Math.floor(Math.random()*lowprimes.length)]);
  var y = a.modPow(r,this);
  if(y.compareTo(BigInteger.ONE) != 0 && y.compareTo(n1) != 0) {
    var j = 1;
    while(j++ < k && y.compareTo(n1) != 0) {
      y = y.modPowInt(2,this);
      if(y.compareTo(BigInteger.ONE) == 0) return false;
    }
    if(y.compareTo(n1) != 0) return false;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.modPowInt"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>modPowInt (e, m)](#apidoc.element.jsbn.default.prototype.modPowInt)
- description and source-code
```javascript
function bnModPowInt(e, m) {
  var z;
  if(e < 256 || m.isEven()) z = new Classic(m); else z = new Montgomery(m);
  return this.exp(e,z);
}
```
- example usage
```shell
...
  for(var i = 0; i < t; ++i) {
    //Pick bases at random, instead of starting at 2
    a.fromInt(lowprimes[Math.floor(Math.random()*lowprimes.length)]);
    var y = a.modPow(r,this);
    if(y.compareTo(BigInteger.ONE) != 0 && y.compareTo(n1) != 0) {
      var j = 1;
      while(j++ < k && y.compareTo(n1) != 0) {
        y = y.modPowInt(2,this);
        if(y.compareTo(BigInteger.ONE) == 0) return false;
      }
      if(y.compareTo(n1) != 0) return false;
    }
  }
  return true;
}
...
```

#### <a name="apidoc.element.jsbn.default.prototype.multiply"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiply (a)](#apidoc.element.jsbn.default.prototype.multiply)
- description and source-code
```javascript
function bnMultiply(a) { var r = nbi(); this.multiplyTo(a,r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.multiplyLowerTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyLowerTo (a, n, r)](#apidoc.element.jsbn.default.prototype.multiplyLowerTo)
- description and source-code
```javascript
function bnpMultiplyLowerTo(a, n, r) {
  var i = Math.min(this.t+a.t,n);
  r.s = 0; // assumes a,this >= 0
  r.t = i;
  while(i > 0) r[--i] = 0;
  var j;
  for(j = r.t-this.t; i < j; ++i) r[i+this.t] = this.am(0,a[i],r,i,0,this.t);
  for(j = Math.min(a.t,n); i < j; ++i) this.am(0,a[i],r,i,0,n-i);
  r.clamp();
}
```
- example usage
```shell
...
function barrettRevert(x) { return x; }

// x = x mod m (HAC 14.42)
function barrettReduce(x) {
  x.drShiftTo(this.m.t-1,this.r2);
  if(x.t > this.m.t+1) { x.t = this.m.t+1; x.clamp(); }
  this.mu.multiplyUpperTo(this.r2,this.m.t+1,this.q3);
  this.m.multiplyLowerTo(this.q3,this.m.t+1,this.r2);
  while(x.compareTo(this.r2) < 0) x.dAddOffset(1,this.m.t+1);
  x.subTo(this.r2,x);
  while(x.compareTo(this.m) >= 0) x.subTo(this.m,x);
}

// r = x^2 mod m; x != r
function barrettSqrTo(x,r) { x.squareTo(r); this.reduce(r); }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.multiplyTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyTo (a, r)](#apidoc.element.jsbn.default.prototype.multiplyTo)
- description and source-code
```javascript
function bnpMultiplyTo(a, r) {
  var x = this.abs(), y = a.abs();
  var i = x.t;
  r.t = i+y.t;
  while(--i >= 0) r[i] = 0;
  for(i = 0; i < y.t; ++i) r[i+x.t] = x.am(0,y[i],r,i,0,x.t);
  r.s = 0;
  r.clamp();
  if(this.s != a.s) BigInteger.ZERO.subTo(r,r);
}
```
- example usage
```shell
...
function Classic(m) { this.m = m; }
function cConvert(x) {
  if(x.s < 0 || x.compareTo(this.m) >= 0) return x.mod(this.m);
  else return x;
}
function cRevert(x) { return x; }
function cReduce(x) { x.divRemTo(this.m,null,x); }
function cMulTo(x,y,r) { x.multiplyTo(y,r); this.reduce(r); }
function cSqrTo(x,r) { x.squareTo(r); this.reduce(r); }

Classic.prototype.convert = cConvert;
Classic.prototype.revert = cRevert;
Classic.prototype.reduce = cReduce;
Classic.prototype.mulTo = cMulTo;
Classic.prototype.sqrTo = cSqrTo;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.multiplyUpperTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>multiplyUpperTo (a, n, r)](#apidoc.element.jsbn.default.prototype.multiplyUpperTo)
- description and source-code
```javascript
function bnpMultiplyUpperTo(a, n, r) {
  --n;
  var i = r.t = this.t+a.t-n;
  r.s = 0; // assumes a,this >= 0
  while(--i >= 0) r[i] = 0;
  for(i = Math.max(n-this.t,0); i < a.t; ++i)
    r[this.t+i-n] = this.am(n-i,a[i],r,0,0,this.t+i-n);
  r.clamp();
  r.drShiftTo(1,r);
}
```
- example usage
```shell
...

function barrettRevert(x) { return x; }

// x = x mod m (HAC 14.42)
function barrettReduce(x) {
  x.drShiftTo(this.m.t-1,this.r2);
  if(x.t > this.m.t+1) { x.t = this.m.t+1; x.clamp(); }
  this.mu.multiplyUpperTo(this.r2,this.m.t+1,this.q3);
  this.m.multiplyLowerTo(this.q3,this.m.t+1,this.r2);
  while(x.compareTo(this.r2) < 0) x.dAddOffset(1,this.m.t+1);
  x.subTo(this.r2,x);
  while(x.compareTo(this.m) >= 0) x.subTo(this.m,x);
}

// r = x^2 mod m; x != r
...
```

#### <a name="apidoc.element.jsbn.default.prototype.negate"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>negate ()](#apidoc.element.jsbn.default.prototype.negate)
- description and source-code
```javascript
function bnNegate() { var r = nbi(); BigInteger.ZERO.subTo(this,r); return r; }
```
- example usage
```shell
...

## API

### bi.toString()

returns the base-10 number as a string

### bi.negate()

returns a new BigInteger equal to the negation of 'bi'

### bi.abs

returns new BI of absolute value
...
```

#### <a name="apidoc.element.jsbn.default.prototype.not"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>not ()](#apidoc.element.jsbn.default.prototype.not)
- description and source-code
```javascript
function bnNot() {
  var r = nbi();
  for(var i = 0; i < this.t; ++i) r[i] = this.DM&~this[i];
  r.t = this.t;
  r.s = ~this.s;
  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.or"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>or (a)](#apidoc.element.jsbn.default.prototype.or)
- description and source-code
```javascript
function bnOr(a) { var r = nbi(); this.bitwiseTo(a,op_or,r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.pow"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>pow (e)](#apidoc.element.jsbn.default.prototype.pow)
- description and source-code
```javascript
function bnPow(e) { return this.exp(e,new NullExp()); }
```
- example usage
```shell
...
}

BigInteger.prototype.DB = dbits;
BigInteger.prototype.DM = ((1<<dbits)-1);
BigInteger.prototype.DV = (1<<dbits);

var BI_FP = 52;
BigInteger.prototype.FV = Math.pow(2,BI_FP);
BigInteger.prototype.F1 = BI_FP-dbits;
BigInteger.prototype.F2 = 2*dbits-BI_FP;

// Digit conversions
var BI_RM = "0123456789abcdefghijklmnopqrstuvwxyz";
var BI_RC = new Array();
var rr,vv;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.rShiftTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>rShiftTo (n, r)](#apidoc.element.jsbn.default.prototype.rShiftTo)
- description and source-code
```javascript
function bnpRShiftTo(n, r) {
  r.s = this.s;
  var ds = Math.floor(n/this.DB);
  if(ds >= this.t) { r.t = 0; return; }
  var bs = n%this.DB;
  var cbs = this.DB-bs;
  var bm = (1<<bs)-1;
  r[0] = this[ds]>>bs;
  for(var i = ds+1; i < this.t; ++i) {
    r[i-ds-1] |= (this[i]&bm)<<cbs;
    r[i-ds] = this[i]>>bs;
  }
  if(bs > 0) r[this.t-ds-1] |= (this.s&bm)<<cbs;
  r.t = this.t-ds;
  r.clamp();
}
```
- example usage
```shell
...
  }
  if(q != null) {
    r.drShiftTo(ys,q);
    if(ts != ms) BigInteger.ZERO.subTo(q,q);
  }
  r.t = ys;
  r.clamp();
  if(nsh > 0) r.rShiftTo(nsh,r); // Denormalize remainder
  if(ts < 0) BigInteger.ZERO.subTo(r,r);
}

// (public) this mod a
function bnMod(a) {
  var r = nbi();
  this.abs().divRemTo(a,null,r);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.remainder"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>remainder (a)](#apidoc.element.jsbn.default.prototype.remainder)
- description and source-code
```javascript
function bnRemainder(a) { var r = nbi(); this.divRemTo(a,null,r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.setBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>setBit (n)](#apidoc.element.jsbn.default.prototype.setBit)
- description and source-code
```javascript
function bnSetBit(n) { return this.changeBit(n,op_or); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.shiftLeft"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shiftLeft (n)](#apidoc.element.jsbn.default.prototype.shiftLeft)
- description and source-code
```javascript
function bnShiftLeft(n) {
  var r = nbi();
  if(n < 0) this.rShiftTo(-n,r); else this.lShiftTo(n,r);
  return r;
}
```
- example usage
```shell
...
    function bnpFromNumber(a,b,c) {
if("number" == typeof b) {
  // new BigInteger(int,int,RNG)
  if(a < 2) this.fromInt(1);
  else {
    this.fromNumber(a,c);
    if(!this.testBit(a-1))    // force MSB set
      this.bitwiseTo(BigInteger.ONE.shiftLeft(a-1),op_or,this);
    if(this.isEven()) this.dAddOffset(1,0); // force odd
    while(!this.isProbablePrime(b)) {
      this.dAddOffset(2,0);
      if(this.bitLength() > a) this.subTo(BigInteger.ONE.shiftLeft(a-1),this);
    }
  }
}
...
```

#### <a name="apidoc.element.jsbn.default.prototype.shiftRight"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shiftRight (n)](#apidoc.element.jsbn.default.prototype.shiftRight)
- description and source-code
```javascript
function bnShiftRight(n) {
  var r = nbi();
  if(n < 0) this.lShiftTo(-n,r); else this.rShiftTo(n,r);
  return r;
}
```
- example usage
```shell
...
}

// (protected) true if probably prime (HAC 4.24, Miller-Rabin)
function bnpMillerRabin(t) {
  var n1 = this.subtract(BigInteger.ONE);
  var k = n1.getLowestSetBit();
  if(k <= 0) return false;
  var r = n1.shiftRight(k);
  t = (t+1)>>1;
  if(t > lowprimes.length) t = lowprimes.length;
  var a = nbi();
  for(var i = 0; i < t; ++i) {
    //Pick bases at random, instead of starting at 2
    a.fromInt(lowprimes[Math.floor(Math.random()*lowprimes.length)]);
    var y = a.modPow(r,this);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.shortValue"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>shortValue ()](#apidoc.element.jsbn.default.prototype.shortValue)
- description and source-code
```javascript
function bnShortValue() { return (this.t==0)?this.s:(this[0]<<16)>>16; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.signum"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>signum ()](#apidoc.element.jsbn.default.prototype.signum)
- description and source-code
```javascript
function bnSigNum() {
  if(this.s < 0) return -1;
  else if(this.t <= 0 || (this.t == 1 && this[0] <= 0)) return 0;
  else return 1;
}
```
- example usage
```shell
...
  else if(this.t <= 0 || (this.t == 1 && this[0] <= 0)) return 0;
  else return 1;
}

// (protected) convert to radix string
function bnpToRadix(b) {
  if(b == null) b = 10;
  if(this.signum() == 0 || b < 2 || b > 36) return "0";
  var cs = this.chunkSize(b);
  var a = Math.pow(b,cs);
  var d = nbv(a), y = nbi(), z = nbi(), r = "";
  this.divRemTo(d,y,z);
  while(y.signum() > 0) {
    r = (a+z.intValue()).toString(b).substr(1) + r;
    y.divRemTo(d,y,z);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.square"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>square ()](#apidoc.element.jsbn.default.prototype.square)
- description and source-code
```javascript
function bnSquare() { var r = nbi(); this.squareTo(r); return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.squareTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>squareTo (r)](#apidoc.element.jsbn.default.prototype.squareTo)
- description and source-code
```javascript
function bnpSquareTo(r) {
  var x = this.abs();
  var i = r.t = 2*x.t;
  while(--i >= 0) r[i] = 0;
  for(i = 0; i < x.t-1; ++i) {
    var c = x.am(i,x[i],r,2*i,0,1);
    if((r[i+x.t]+=x.am(i+1,2*x[i],r,2*i+1,c,x.t-i-1)) >= x.DV) {
      r[i+x.t] -= x.DV;
      r[i+x.t+1] = 1;
    }
  }
  if(r.t > 0) r[r.t-1] += x.am(i,x[i],r,2*i,0,1);
  r.s = 0;
  r.clamp();
}
```
- example usage
```shell
...
function cConvert(x) {
  if(x.s < 0 || x.compareTo(this.m) >= 0) return x.mod(this.m);
  else return x;
}
function cRevert(x) { return x; }
function cReduce(x) { x.divRemTo(this.m,null,x); }
function cMulTo(x,y,r) { x.multiplyTo(y,r); this.reduce(r); }
function cSqrTo(x,r) { x.squareTo(r); this.reduce(r); }

Classic.prototype.convert = cConvert;
Classic.prototype.revert = cRevert;
Classic.prototype.reduce = cReduce;
Classic.prototype.mulTo = cMulTo;
Classic.prototype.sqrTo = cSqrTo;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.subTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>subTo (a, r)](#apidoc.element.jsbn.default.prototype.subTo)
- description and source-code
```javascript
function bnpSubTo(a, r) {
  var i = 0, c = 0, m = Math.min(a.t,this.t);
  while(i < m) {
    c += this[i]-a[i];
    r[i++] = c&this.DM;
    c >>= this.DB;
  }
  if(a.t < this.t) {
    c -= a.s;
    while(i < this.t) {
      c += this[i];
      r[i++] = c&this.DM;
      c >>= this.DB;
    }
    c += this.s;
  }
  else {
    c += this.s;
    while(i < a.t) {
      c -= a[i];
      r[i++] = c&this.DM;
      c >>= this.DB;
    }
    c -= a.s;
  }
  r.s = (c<0)?-1:0;
  if(c < -1) r[i++] = this.DV+c;
  else if(c > 0) r[i++] = c;
  r.t = i;
  r.clamp();
}
```
- example usage
```shell
...
    if(sh >= this.DB) sh -= this.DB;
  }
  if(k == 8 && (s[0]&0x80) != 0) {
    this.s = -1;
    if(sh > 0) this[this.t-1] |= ((1<<(this.DB-sh))-1)<<sh;
  }
  this.clamp();
  if(mi) BigInteger.ZERO.subTo(this,this);
}

// (protected) clamp off excess high words
function bnpClamp() {
  var c = this.s&this.DM;
  while(this.t > 0 && this[this.t-1] == c) --this.t;
}
...
```

#### <a name="apidoc.element.jsbn.default.prototype.subtract"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>subtract (a)](#apidoc.element.jsbn.default.prototype.subtract)
- description and source-code
```javascript
function bnSubtract(a) { var r = nbi(); this.subTo(a,r); return r; }
```
- example usage
```shell
...
    else {
      v.subTo(u,v);
      if(ac) c.subTo(a,c);
      d.subTo(b,d);
    }
  }
  if(v.compareTo(BigInteger.ONE) != 0) return BigInteger.ZERO;
  if(d.compareTo(m) >= 0) return d.subtract(m);
  if(d.signum() < 0) d.addTo(m,d); else return d;
  if(d.signum() < 0) return d.add(m); else return d;
}

var lowprimes = [2,3,5,7,11,13,17,19,23,29,31,37,41,43,47,53,59,61,67,71,73,79,83,89,97,101,103,107,109,113,127,131,137,139,149,
151,157,163,167,173,179,181,191,193,197,199,211,223,227,229,233,239,241,251,257,263,269,271,277,281,283,293,307,311,313,317,331,
337,347,349,353,359,367,373,379,383,389,397,401,409,419,421,431,433,439,443,449,457,461,463,467,479,487,491,499,503,509,521,523,
541,547,557,563,569,571,577,587,593,599,601,607,613,617,619,631,641,643,647,653,659,661,673,677,683,691,701,709,719,727,733,739,
743,751,757,761,769,773,787,797,809,811,821,823,827,829,839,853,857,859,863,877,881,883,887,907,911,919,929,937,941,947,953,967,
971,977,983,991,997];
var lplim = (1<<26)/lowprimes[lowprimes.length-1];
...
```

#### <a name="apidoc.element.jsbn.default.prototype.testBit"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>testBit (n)](#apidoc.element.jsbn.default.prototype.testBit)
- description and source-code
```javascript
function bnTestBit(n) {
  var j = Math.floor(n/this.DB);
  if(j >= this.t) return(this.s!=0);
  return((this[j]&(1<<(n%this.DB)))!=0);
}
```
- example usage
```shell
...
// (protected) alternate constructor
function bnpFromNumber(a,b,c) {
  if("number" == typeof b) {
    // new BigInteger(int,int,RNG)
    if(a < 2) this.fromInt(1);
    else {
      this.fromNumber(a,c);
      if(!this.testBit(a-1))    // force MSB set
        this.bitwiseTo(BigInteger.ONE.shiftLeft(a-1),op_or,this);
      if(this.isEven()) this.dAddOffset(1,0); // force odd
      while(!this.isProbablePrime(b)) {
        this.dAddOffset(2,0);
        if(this.bitLength() > a) this.subTo(BigInteger.ONE.shiftLeft(a-1),this);
      }
    }
...
```

#### <a name="apidoc.element.jsbn.default.prototype.toByteArray"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toByteArray ()](#apidoc.element.jsbn.default.prototype.toByteArray)
- description and source-code
```javascript
function bnToByteArray() {
  var i = this.t, r = new Array();
  r[0] = this.s;
  var p = this.DB-(i*this.DB)%8, d, k = 0;
  if(i-- > 0) {
    if(p < this.DB && (d = this[i]>>p) != (this.s&this.DM)>>p)
      r[k++] = d|(this.s<<(this.DB-p));
    while(i >= 0) {
      if(p < 8) {
        d = (this[i]&((1<<p)-1))<<(8-p);
        d |= this[--i]>>(p+=this.DB-8);
      }
      else {
        d = (this[i]>>(p-=8))&0xff;
        if(p <= 0) { p += this.DB; --i; }
      }
      if((d&0x80) != 0) d |= -256;
      if(k == 0 && (this.s&0x80) != (d&0x80)) ++k;
      if(k > 0 || d != this.s) r[k++] = d;
    }
  }
  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jsbn.default.prototype.toRadix"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toRadix (b)](#apidoc.element.jsbn.default.prototype.toRadix)
- description and source-code
```javascript
function bnpToRadix(b) {
  if(b == null) b = 10;
  if(this.signum() == 0 || b < 2 || b > 36) return "0";
  var cs = this.chunkSize(b);
  var a = Math.pow(b,cs);
  var d = nbv(a), y = nbi(), z = nbi(), r = "";
  this.divRemTo(d,y,z);
  while(y.signum() > 0) {
    r = (a+z.intValue()).toString(b).substr(1) + r;
    y.divRemTo(d,y,z);
  }
  return z.intValue().toString(b) + r;
}
```
- example usage
```shell
...
if(this.s < 0) return "-"+this.negate().toString(b);
var k;
if(b == 16) k = 4;
else if(b == 8) k = 3;
else if(b == 2) k = 1;
else if(b == 32) k = 5;
else if(b == 4) k = 2;
else return this.toRadix(b);
var km = (1<<k)-1, d, m = false, r = "", i = this.t;
var p = this.DB-(i*this.DB)%k;
if(i-- > 0) {
  if(p < this.DB && (d = this[i]>>p) > 0) { m = true; r = int2char(d); }
  while(i >= 0) {
    if(p < k) {
      d = (this[i]&((1<<p)-1))<<(k-p);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.toString"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>toString (b)](#apidoc.element.jsbn.default.prototype.toString)
- description and source-code
```javascript
function bnToString(b) {
  if(this.s < 0) return "-"+this.negate().toString(b);
  var k;
  if(b == 16) k = 4;
  else if(b == 8) k = 3;
  else if(b == 2) k = 1;
  else if(b == 32) k = 5;
  else if(b == 4) k = 2;
  else return this.toRadix(b);
  var km = (1<<k)-1, d, m = false, r = "", i = this.t;
  var p = this.DB-(i*this.DB)%k;
  if(i-- > 0) {
    if(p < this.DB && (d = this[i]>>p) > 0) { m = true; r = int2char(d); }
    while(i >= 0) {
      if(p < k) {
        d = (this[i]&((1<<p)-1))<<(k-p);
        d |= this[--i]>>(p+=this.DB-k);
      }
      else {
        d = (this[i]>>(p-=k))&km;
        if(p <= 0) { p += this.DB; --i; }
      }
      if(d > 0) m = true;
      if(m) r += int2char(d);
    }
  }
  return m?r:"0";
}
```
- example usage
```shell
...

    var bi = new BigInteger('91823918239182398123');
    console.log(bi.bitLength()); // 67


## API

### bi.toString()

returns the base-10 number as a string

### bi.negate()

returns a new BigInteger equal to the negation of 'bi'
...
```

#### <a name="apidoc.element.jsbn.default.prototype.xor"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>xor (a)](#apidoc.element.jsbn.default.prototype.xor)
- description and source-code
```javascript
function bnXor(a) { var r = nbi(); this.bitwiseTo(a,op_xor,r); return r; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbn.default.prototype.Barrett"></a>[module jsbn.default.prototype.Barrett](#apidoc.module.jsbn.default.prototype.Barrett)

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.Barrett"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.</span>Barrett (m)](#apidoc.element.jsbn.default.prototype.Barrett.Barrett)
- description and source-code
```javascript
function Barrett(m) {
  // setup Barrett
  this.r2 = nbi();
  this.q3 = nbi();
  BigInteger.ONE.dlShiftTo(2*m.t,this.r2);
  this.mu = this.r2.divide(m);
  this.m = m;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbn.default.prototype.Barrett.prototype"></a>[module jsbn.default.prototype.Barrett.prototype](#apidoc.module.jsbn.default.prototype.Barrett.prototype)

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.prototype.convert"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>convert (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.convert)
- description and source-code
```javascript
function barrettConvert(x) {
  if(x.s < 0 || x.t > 2*this.m.t) return x.mod(this.m);
  else if(x.compareTo(this.m) < 0) return x;
  else { var r = nbi(); x.copyTo(r); this.reduce(r); return r; }
}
```
- example usage
```shell
...

// (protected) true iff this is even
function bnpIsEven() { return ((this.t>0)?(this[0]&1):this.s) == 0; }

// (protected) this^e, e < 2^32, doing sqr and mul with "r" (HAC 14.79)
function bnpExp(e,z) {
  if(e > 0xffffffff || e < 1) return BigInteger.ONE;
  var r = nbi(), r2 = nbi(), g = z.convert(this), i = nbits(e)-1;
  g.copyTo(r);
  while(--i >= 0) {
    z.sqrTo(r,r2);
    if((e&(1<<i)) > 0) z.mulTo(r2,g,r);
    else { var t = r; r = r2; r2 = t; }
  }
  return z.revert(r);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.prototype.mulTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>mulTo (x, y, r)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.mulTo)
- description and source-code
```javascript
function barrettMulTo(x, y, r) { x.multiplyTo(y,r); this.reduce(r); }
```
- example usage
```shell
...
// (protected) this^e, e < 2^32, doing sqr and mul with "r" (HAC 14.79)
function bnpExp(e,z) {
  if(e > 0xffffffff || e < 1) return BigInteger.ONE;
  var r = nbi(), r2 = nbi(), g = z.convert(this), i = nbits(e)-1;
  g.copyTo(r);
  while(--i >= 0) {
    z.sqrTo(r,r2);
    if((e&(1<<i)) > 0) z.mulTo(r2,g,r);
    else { var t = r; r = r2; r2 = t; }
  }
  return z.revert(r);
}

// (public) this^e % m, 0 <= e < 2^32
function bnModPowInt(e,m) {
...
```

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.prototype.reduce"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>reduce (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.reduce)
- description and source-code
```javascript
function barrettReduce(x) {
  x.drShiftTo(this.m.t-1,this.r2);
  if(x.t > this.m.t+1) { x.t = this.m.t+1; x.clamp(); }
  this.mu.multiplyUpperTo(this.r2,this.m.t+1,this.q3);
  this.m.multiplyLowerTo(this.q3,this.m.t+1,this.r2);
  while(x.compareTo(this.r2) < 0) x.dAddOffset(1,this.m.t+1);
  x.subTo(this.r2,x);
  while(x.compareTo(this.m) >= 0) x.subTo(this.m,x);
}
```
- example usage
```shell
...
function Classic(m) { this.m = m; }
function cConvert(x) {
  if(x.s < 0 || x.compareTo(this.m) >= 0) return x.mod(this.m);
  else return x;
}
function cRevert(x) { return x; }
function cReduce(x) { x.divRemTo(this.m,null,x); }
function cMulTo(x,y,r) { x.multiplyTo(y,r); this.reduce(r); }
function cSqrTo(x,r) { x.squareTo(r); this.reduce(r); }

Classic.prototype.convert = cConvert;
Classic.prototype.revert = cRevert;
Classic.prototype.reduce = cReduce;
Classic.prototype.mulTo = cMulTo;
Classic.prototype.sqrTo = cSqrTo;
...
```

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.prototype.revert"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>revert (x)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.revert)
- description and source-code
```javascript
function barrettRevert(x) { return x; }
```
- example usage
```shell
...
  var r = nbi(), r2 = nbi(), g = z.convert(this), i = nbits(e)-1;
  g.copyTo(r);
  while(--i >= 0) {
    z.sqrTo(r,r2);
    if((e&(1<<i)) > 0) z.mulTo(r2,g,r);
    else { var t = r; r = r2; r2 = t; }
  }
  return z.revert(r);
}

// (public) this^e % m, 0 <= e < 2^32
function bnModPowInt(e,m) {
  var z;
  if(e < 256 || m.isEven()) z = new Classic(m); else z = new Montgomery(m);
  return this.exp(e,z);
...
```

#### <a name="apidoc.element.jsbn.default.prototype.Barrett.prototype.sqrTo"></a>[function <span class="apidocSignatureSpan">jsbn.default.prototype.Barrett.prototype.</span>sqrTo (x, r)](#apidoc.element.jsbn.default.prototype.Barrett.prototype.sqrTo)
- description and source-code
```javascript
function barrettSqrTo(x, r) { x.squareTo(r); this.reduce(r); }
```
- example usage
```shell
...

// (protected) this^e, e < 2^32, doing sqr and mul with "r" (HAC 14.79)
function bnpExp(e,z) {
  if(e > 0xffffffff || e < 1) return BigInteger.ONE;
  var r = nbi(), r2 = nbi(), g = z.convert(this), i = nbits(e)-1;
  g.copyTo(r);
  while(--i >= 0) {
    z.sqrTo(r,r2);
    if((e&(1<<i)) > 0) z.mulTo(r2,g,r);
    else { var t = r; r = r2; r2 = t; }
  }
  return z.revert(r);
}

// (public) this^e % m, 0 <= e < 2^32
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

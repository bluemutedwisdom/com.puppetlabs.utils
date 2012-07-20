# com.puppetlabs.utils

This is a collection of Clojure utilities shared between Puppet Labs projects,
extracted from the PuppetDB project. They are the starting point of building a
real library of reusable tools for other experiments and projects.


## Keywords in these Documents

The key words "*MUST*", "*MUST NOT*", "*REQUIRED*", "*SHALL*", "*SHALL
NOT*", "*SHOULD*", "*SHOULD NOT*", "*RECOMMENDED*", "*MAY*", and
"*OPTIONAL*" in the PuppetDB docs are to be interpreted as described
in [RFC 2119][RFC2119].

[RFC2119]: http://tools.ietf.org/html/rfc2119

## Installation guide

This isn't a user installable component. Eventually it should be published
somewhere you can reuse, but right now you would have to build a local jar and
publish to your local repository to make it work.


## Developing the package

Start with [Leiningen 2][leiningen] and do the standard:

    git clone git://github.com/puppetlabs/com.puppetlabs.utils
    cd com.puppetlabs.utils
    lein test


[leiningen]: https://github.com/technomancy/leiningen

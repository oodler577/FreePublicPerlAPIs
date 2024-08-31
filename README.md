# FreePublicPerlAPIs
List of Perl modules and clients for the web services listed at https://www.freepublicapis.com/.

If you think your favorite or personal module, idiom, or paradigm is the best - **_prove it_** by creating the best [Free Public API](https://github.com/oodler577/FreePublicPerlAPIs/wiki) Perl module!

# [Click to See What's Already Been Uploaded to CPAN!](https://github.com/oodler577/FreePublicPerlAPIs/wiki)

# How to participate

1. Claim a [Free Public API](https://www.freepublicapis.com/) at the [wiki page](https://github.com/oodler577/FreePublicPerlAPIs/wiki)
2. Create API and client, show casing your skills and favorite idioms/modules
3. Upload to CPAN using the `Acme::Free::API::` name space
4. [Update wiki](https://github.com/oodler577/FreePublicPerlAPIs/wiki) with appropriate links
5. Tell everybody!
6. [Discussions](https://github.com/oodler577/FreePublicPerlAPIs/discussions) are enabled, keep it clean and germane.

[See an example of a module on CPAN](https://metacpan.org/pod/Acme::Free::API::Ye).

# Rules && Guidelines

This is supposed to be easy and fun! This is not a race. It is a marathon.

1. Make sure [the API you select](https://www.freepublicapis.com/) at not been [claimed](https://github.com/oodler577/FreePublicPerlAPIs/wiki)
2. Make sure to s[elect an API that is FREE](https://www.freepublicapis.com/) from [https://www.freepublicapis.com/](https://www.freepublicapis.com/) and **API must require NO authentication mechanism**
3. A complete entry consists of at least 1 Perl module and 1 commandline client with commands to use all API endpoints
4. You MUST use the `Acme::Free::API::` name space on CPAN
5. Complete POD is required. POD is not required, but it must render in `perldoc` and on MetaCPAN
6. Installing the module must also install the client (so it's available via `PATH`) _and_ all dependencies.
7. Dist::Zilla is strongly recommended, so please include any [dist.ini](https://metacpan.org/release/OODLER/Acme-Free-API-Stonks-1.0.0/source/dist.ini) (see [example](https://metacpan.org/release/OODLER/Acme-Free-API-Stonks-1.0.0/source/dist.ini)) in your CPAN upload!
8. ALL endpoints of the API must be implemented and used in some way by the cli client
9. You must [claim your API](https://github.com/oodler577/FreePublicPerlAPIs/wiki) before you start working on it
10. There are no deadlines, but if your claim is clearly stale it can be scooped
11. NO `TRIAL` module uploaded to CPAN
12. Versions must start at `1.0.0` or _very near_ that if you anticipate some changes
13. Modules must be _complete_ (hence the preference for `1.0.0`
14. Modules must have at least 1 test in `t/`, as [trivial as it may be](https://metacpan.org/release/OODLER/Acme-Free-API-Ye-1.0.0/source/t/01-basic.t)
15. Modules and cli client must be _zero conf_ (no configuration files required)
16. You can use ChatGPT or whatever, but it must be clearly noted that you did this (and to what degree)
17. External code that is not yours used must be attributed
18. All code must be released with the Perl or similar licensing

# FAQ

1. Q: Will there be any voting or picking of some kind of winner? A: **NO**, the proof is in the pudding
2. Q: Is there a main place to discuss this? A: NO
3. Q: Is there a main point of contact for questions or clarifications? A: Best bet is to creat [an issue here](https://github.com/oodler577/FreePublicPerlAPIs/issues)
4. Q: Who is the final arbiter in any disputes related to this fun thing? A: OODLER - but let's not make it come to that :-)

# GOOD LUCK!

# Version numbering schemes: an observation

Thursday 7 March 2019

It's funny the things you notice when you're new to a place, but one of the things I've noticed is the inconsistent version numbering schemes that are in use across the Vision products.

A quick search through our internal documentation reveals that we currently use at least five different version numbering schemes:

* Major only, e.g. `ApplicationName 10490` or `TLA 720`.
* Major.minor, e.g. `ApplicationName 3.2` or `ApplicationName Tango 2.6`.
* Major.minor.patch, e.g. `ApplicationName 1.4.0`.
* Major.minor.patch.build, e.g. `ApplicationName 1.0.0.0` or `ApplicationName 2.2.1.1`.
* Year-based, e.g. `ApplicationName 2019.11`.

I wonder why there are so many different numbering schemes. I expect, like many of these things, it has simply grown organically without much planning.


## Semantic versioning

While there are many different ways of numbering software versions, one of the most widely adopted version numbering schemes is [semantic versioning](https://semver.org/). It is also my favourite thanks to its predictability.

At its simplest, semantic versioning uses three numbers:

1. MAJOR version — increased when you make incompatible API changes.
2. MINOR version — increased when you add new, backwards-compatible functionality.
3. PATCH version — increased when you make backwards-compatible bug fixes.

Using this versioning, you can easily see, for example, that v1.4.1 will offer the same functionality as v1.4.0 (or v1.4) but with bug fixes. Whereas v1.5.0 will add new features that are backwards-compatible with v1.4.0. v2.0.0, on the other hand, will make significant changes that are at least partially (if not completely) incompatible with the v1.x.x software.


## Benefits of a consistent numbering scheme

The most obvious benefit of using a consistent numbering scheme across an organisation, particularly one like semantic versioning, is that at a glance you can see what has changed in a release. A version number helps manage expectations.

When you have close software dependencies, as we do, it becomes incredibly helpful when planning releases.

Imagine looking across the product roadmap and seeing that the database system your own application relies on is anticipating to bump up from v1.5.0 to v2.0.0 in three release cycles' time. That gives you an immediate heads-up that there are likely going to be significant changes to that system that will require work on your own product. There are now conversations to be had and work to be scheduled into your own up-coming sprints to anticipate this.


## Conclusion

Like I said, this is just an observation. But as we move forward our inter-dependencies are likely to deepen. It might be beneficial to address this inconsistency sooner rather than later.

---

Originally published on the internal blog.
I've edited a few of the details for this public version.
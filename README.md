# Sanitized ALI files for Genode

[Genode](https://github.com/genodelabs/genode) requires a static description
of an API provided by a package. As generating ALIs during compilation does not
fit Genode's build system well, we check in the ALI files and use them from a
dedicated port. They are also purged from architecture specific compiler flags
and should be CPU architecture agnostic.

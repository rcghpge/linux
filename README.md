# linux
---
[![Kernel Uptime](https://github.com/rcghpge/linux/actions/workflows/sync.yml/badge.svg)](https://github.com/rcghpge/linux/actions/workflows/sync.yml)

A fork of the Linux kernel source tree. This repository mirrors the official Linux kernel source tree maintained by Linus Torvalds and the Linux community, with additional features or changes I may explore in the future.

---

## Documentation

The Linux kernel comes with a comprehensive set of guides for developers and users. These guides can be rendered in various formats, such as HTML and PDF. To start, please refer to:

- `Documentation/admin-guide/README.rst`

---

### Building Documentation

To generate the documentation in different formats, use the following commands:

- HTML format:
  ```bash
  make htmldocs
  ```
- PDF format:
  ```bash
  make pdfdocs
  ```

Alternatively, you can read the formatted documentation online at:
[Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)

---

### Additional Resources

The `Documentation/` subdirectory contains numerous text files, some of which use the reStructuredText markup notation. These files provide information on various kernel components and processes.

For essential requirements and information on building and running the kernel, please read:
- `Documentation/process/changes.rst`

This file outlines:
- Requirements for building and running the kernel.
- Potential issues that may arise when upgrading the kernel.

---

## Contribution and Exploration

While this fork is primarily a mirror, I may introduce experimental changes, configurations, or features. If you’re interested in collaborating or reviewing these modifications, feel free to explore the branches of this repository.

For further details, refer to the official Linux Kernel documentation or visit the official [Linux Kernel website](https://www.kernel.org).

---

Happy coding!


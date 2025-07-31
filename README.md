# linux
---
[![Kernel Uptime](https://github.com/rcghpge/linux/actions/workflows/sync.yml/badge.svg)](https://github.com/rcghpge/linux/actions/workflows/sync.yml)

This is a mirror of the Linux kernel source tree maintained by Linus Torvalds and the Linux community

The Linux kernel is the core of the Linux operating system — managing hardware, running processes, and enabling secure, efficient computing across everything from phones to servers, supercomputers, and embedded devices.

---

## Documentation

The Linux kernel comes with a comprehensive set of guides for developers and users. These guides can be rendered in various formats, such as HTML and PDF. To start, please refer to:

- [`Documentation/admin-guide/README.rst`](./Documentation/admin-guide/README.rst)

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

The [`Documentation/`](./Documentation) subdirectory contains numerous text files, some of which use the reStructuredText markup notation. These files provide information on various kernel components and processes.

For essential requirements and information on building and running the kernel, please read:
- [`Documentation/process/changes.rst`](./Documentation/process/changes.rst)

This file outlines:
- Requirements for building and running the kernel.
- Potential issues that may arise when upgrading the kernel.

---

## Contributing

This repository exists to support the broader Linux and FOSS/OSS community. While it primarily follows upstream development, you're welcome to explore the branches, experiment, or adapt the codebase for your own work in accordance with the broader Linux community.

For official contribution guidelines, please refer to the [Linux Kernel documentation](https://www.kernel.org/doc/html/latest/process/index.html) or visit [kernel.org](https://www.kernel.org/) to get involved in the community's mainline development.

---

Happy coding!


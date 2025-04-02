# Chapter 4: Advanced IOC Configuration and Startup

This chapter significantly expands on IOC development by delving into advanced configuration techniques and the details of the IOC runtime environment. You will learn how to develop effectively an `iocsh` file and master database templating for scalable configurations. You will then apply these techniques to efficiently manage multiple similar devices within the IOC startup script (`st.cmd`), and finally explore the details of the different phases within that script.

This chapter covers the following topics:

* [Working with `iocsh`: Script Files and Commands](iocsh_basics.md): Developing startup script snippets (`*.iocsh` files) and understanding interactive shell usage.
* [Database Templates and Substitution](db_templates.md): Using `.template` and `.substitution` files with `Db/Makefile` for reusable database definitions.
* [Managing Multiple Devices in `st.cmd`](multiple_devices.md): Applying templates and `iocsh` commands in the startup script for efficient configuration.
* [IOC Startup Sequence (`st.cmd` Phases)](stcmd_phases.md): Learning about commands executed before and after `iocInit()`.

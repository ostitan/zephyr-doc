:orphan:

.. title:: SYS_CLOCK_EXISTS

.. option:: CONFIG_SYS_CLOCK_EXISTS:
.. _CONFIG_SYS_CLOCK_EXISTS:

This option specifies that the kernel lacks timer support.



:Symbol:           SYS_CLOCK_EXISTS
:Type:             bool
:Value:            "y"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:
 (no prompts)
:Default values:

 *  y (value: "y")
 *   Condition: (none)
 *  n (value: "n")
 *   Condition: SYS_CLOCK_TICKS_PER_SEC = 0 (value: "n")
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 (no additional dependencies)
:Locations:
 * ../kernel/Kconfig:47
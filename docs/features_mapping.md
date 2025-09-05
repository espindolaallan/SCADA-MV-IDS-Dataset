# Features Mapping — SCADA-MV-IDS

This document maps the feature identifiers used in the **SCADA-MV-IDS** dataset to the names and descriptions reported in the paper.

---

## **Linux — Network View**
| Feature ID | Paper Name | Description                                |
| ---------- | ---------- | ---------------------------------------- |
| **rxpck**  | **rxpck**  | Packet receiving rate |
| **txpck**  | **txpck**  | Packet transmitting rate |
| **rxkB**   | **rxkB**   | Data receiving rate |
| **txkB**   | **txkB**   | Data transmitting rate |
| **rxcmp**  | **rxcmp**  | Compressed packets receiving rate |
| **txcmp**  | **txcmp**  | Compressed packets transmitting rate |
| **rxmcst** | **rxmcst** | Multicast packets receiving rate |
| **ifutil** | **ifutil** | NIC usage percentage |

---

## **Linux — Host View**
| Feature ID  | Paper Name | Description                                |
| ----------- | ---------- | ---------------------------------------- |
| **kbdirty** | **dirty**  | Memory to get written back to the disk |
| **kbkstack**| **stack**  | Memory used for kernel stack space |
| **kbvmused**| **vmused** | Memory of used virtual address space |
| **usr**     | **usr**    | CPU utilization at the user level (application) |
| **nice**    | **nice**   | CPU utilization at the user level with priority |
| **sys**     | **sys**    | CPU utilization at the system level (kernel) |
| **iowait**  | **iowait** | CPU idle percentage during I/O wait |
| **steal**   | **steal**  | CPU time delayed by hypervisor contention |
| **irq**     | **irq**    | CPU time to service hardware interrupts |
| **soft**    | **soft**   | CPU time to service software interrupts |
| **guest**   | **guest**  | CPU time to run a virtual processor |
| **gnice**   | **gnice**  | CPU time to run a niced guest |
| **idle**    | **idle**   | Idle CPU time without disk I/O request |
| **pswpin**  | **pswpin** | Swap pages the system brought in per second |
| **pswpout** | **pswpout**| Swap pages the system brought out per second |
| **proc**    | **proc**   | Total number of tasks created per second |
| **cswch**   | **cswch**  | Total number of context switches per second |

---

## **Windows — User Activity View**
| Feature ID | Paper Name | Description                               |
| ---------- | ---------- | --------------------------------------- |
| **id1**    | **newp**      | New process |
| **id2**    | **filech**    | A process changed a file creation time |
| **id5**    | **pterm**     | Process terminated |
| **id10**   | **popen**     | Process opening other process |
| **id11**   | **filew**     | File creation or overwrite |
| **id12**   | **regw**      | Writing of values to registry |
| **id13**   | **regr**      | Renaming of keys and values in registry |
| **id14**   | **filestr**   | Creation of a named file stream |
| **id15**   | **regc**      | Changes to registry |

---

## **Windows — System Activity View**
| Feature ID | Paper Name | Description                               |
| ---------- | ---------- | --------------------------------------- |
| **id3**    | **netc**      | Network connection |
| **id4**    | **sysmch**    | Sysmon service state changed |
| **id6**    | **driverl**   | Driver loaded |
| **id7**    | **imgl**      | Image loaded |
| **id8**    | **tcreate**   | Process thread creation in another thread |
| **id9**    | **fread**     | File read operation |
| **id16**   | **dns**       | DNS query |
| **id17**   | **cbind**     | Consumer binds to a filter |
| **id18**   | **sysmchf**   | Changes in Sysmon configuration |
| **id19**   | **namedp**    | Creation of named pipes |
| **id20**   | **namedph**   | Named pipe connection between hosts |
| **id21**   | **wmifilter** | WMI event filter registration |
| **id22**   | **wmireg**    | Registration of WMI consumers |
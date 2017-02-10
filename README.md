# gdb_commands
command list of gdb

```
$ gdb EXEFILE COREFILE
(gdb) bt
(gdb) f NUMBER
(gdb) list
(gdb) p VARIABLE
```

### [gdb Attach]
```
   $ sudo gdb EXEFILE PID
or $ gdb EXEFILE
          (gdb) attach PID
or $ gdb -p PID
```

### [Generate Core Dump]
```
(gdb) generate-core-file coredump.1
```

### [Thread Info]
```
(gdb) info threads
(gdb) t #thread_num
(gdb) bt
(gdb) f #num
```

### [break]
```
(gdb) info breakpoints
(gdb) break filename:line
(gdb) step
(gdb) next
(gdb) info locals
(gdb) continue
^C
(gdb) clear
```

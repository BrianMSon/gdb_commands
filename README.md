# gdb commands
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
<or>
$ gdb EXEFILE
   (gdb) attach PID
<or>
$ gdb -p PID
```

### [Generate Core Dump]
```
(gdb) generate-core-file coredump.1
<or>
$ gcore PID
```

### [Thread Info]
```
(gdb) info threads
(gdb) t THREAD_NUMBER
(gdb) bt
(gdb) f #num
```

### [All Thread Info]
```
(gdb) thread apply all bt
(gdb) thread apply all bt full
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

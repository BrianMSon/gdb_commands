# gdb_commands
command list of gdb

```
$ gdb ExeFileName CoreFileName
(gdb) bt
(gdb) f 번호
(gdb) list
(gdb) p 변수명
```

### [gdb Attach]
```
   $ sudo gdb 실행파일명 PID
or $ gdb 실행파일명
          (gdb) attach PID
or $ gdb -p PID
```

### [강제 덤프 남기기]
```
(gdb) generate-core-file coredump.1
```

### [Thread 상태 확인]
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

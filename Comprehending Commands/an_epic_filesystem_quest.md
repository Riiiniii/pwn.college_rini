# Challenge Name
An epic filesystem quest

## My solve
**Flag:** `pwn.college{MtHf_PmCi8qK1jwWjvdSuJ2zPFQ.QX5IDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
CLUE  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin   challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat CLUE
Lucky listing!
The next clue is in: /usr/share/racket/pkgs/realm/chapter8/compiled
The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd /usr
hacker@commands~an-epic-filesystem-quest:/usr$ cd share
hacker@commands~an-epic-filesystem-quest:/usr/share$ cd racket
hacker@commands~an-epic-filesystem-quest:/usr/share/racket$ cd pkgs
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs$ cd realm
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm$ cd chapter8
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm/chapter8$ cd compiled
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm/chapter8/compiled$ cat /compiled
cat: /compiled: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm/chapter8/compiled$ ls
BRIEF  source_rkt.dep  source_rkt.zo
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm/chapter8/compiled$ cat BRIEF
Tubular find!
The next clue is in: /usr/share/locale/zh_TW.UTF-8/LC_MESSAGES

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/realm/chapter8/compiled$ cd /usr
hacker@commands~an-epic-filesystem-quest:/usr$ cd share
hacker@commands~an-epic-filesystem-quest:/usr/share$ cd locale
hacker@commands~an-epic-filesystem-quest:/usr/share/locale$ cd zh_TW.UTF-8/LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ ls -a
.  ..  .NOTE  nvim.mo
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat .NOTE
Yahaha, you found me!
The next clue is in: /usr/share/racket/pkgs/typed-racket-lib/typed/racket/base/compiled

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat /usr/share/racket/pkgs/typed-racket-lib/typed/racket/base/compiled
cat: /usr/share/racket/pkgs/typed-racket-lib/typed/racket/base/compiled: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ ls /usr/share/racket/pkgs/typed-racket-lib/typed/racket/base/compiled
POINTER-TRAPPED  no-check_rkt.dep  no-check_rkt.zo
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat POINTER-TRAPPED
cat: POINTER-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat /POINTER-TRAPPED
cat: /POINTER-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat /compiled/POINTER-TRAPPED
cat: /compiled/POINTER-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cat /usr/share/racket/pkgs/typed-racket-lib/typed/racket/base/compiled/POINTER-TRAPPED
Tubular find!
The next clue is in: /usr/local/lib/python3.8/dist-packages/sympy/polys/numberfields
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_TW.UTF-8/LC_MESSAGES$ cd /usr
hacker@commands~an-epic-filesystem-quest:/usr$ cd local
hacker@commands~an-epic-filesystem-quest:/usr/local$ cd lib
hacker@commands~an-epic-filesystem-quest:/usr/local/lib$ cd pyhon3.8
bash: cd: pyhon3.8: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/local/lib$ cd python3.8
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8$ cd dist-packages
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages$ cd sympy
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/sympy$ cd polys
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/sympy/polys$ cd numberfields
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/sympy/polys/numberfields$ ls
HINT         __pycache__  exceptions.py         galoisgroups.py  modules.py  resolvent_lookup.py  tests
__init__.py  basis.py     galois_resolvents.py  minpoly.py       primes.py   subfield.py          utilities.py
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/sympy/polys/numberfields$ cat HINT
Congratulations, you found the clue!
The next clue is in: /usr/share/giac
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/sympy/polys/numberfields$ cd /usr
hacker@commands~an-epic-filesystem-quest:/usr$ cd share
hacker@commands~an-epic-filesystem-quest:/usr/share$ cd giac
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ ls
INSIGHT  aide_cas
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cat INSIGHT
Lucky listing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/markdown_it/rules_inline/__pycache__

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cat /usr/local/lib/python3.8/dist-packages/markdown_it/rules_inline/__pycache__
cat: /usr/local/lib/python3.8/dist-packages/markdown_it/rules_inline/__pycache__: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ ls /usr/local/lib/python3.8/dist-packages/markdown_it/rules_inline/__pycache__
SECRET-TRAPPED                emphasis.cpython-38.pyc        image.cpython-38.pyc         strikethrough.cpython-38.pyc
__init__.cpython-38.pyc       entity.cpython-38.pyc          link.cpython-38.pyc          text.cpython-38.pyc
autolink.cpython-38.pyc       escape.cpython-38.pyc          linkify.cpython-38.pyc
backticks.cpython-38.pyc      fragments_join.cpython-38.pyc  newline.cpython-38.pyc
balance_pairs.cpython-38.pyc  html_inline.cpython-38.pyc     state_inline.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cat SECRET-TRAPPED
cat: SECRET-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cat /SECRET-TRAPPED
cat: /SECRET-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cat /usr/local/lib/python3.8/dist-packages/markdown_it/rules_inline/__pycache__/SECRET-TRAPPED
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qed
hacker@commands~an-epic-filesystem-quest:/usr/share/giac$ cd /opt
hacker@commands~an-epic-filesystem-quest:/opt$ cd linux
hacker@commands~an-epic-filesystem-quest:/opt/linux$ cd linux-5.4
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4$ cd drivers
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers$ cd net
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net$ cd ethernet
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet$ cd qlogic
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic$ cd qed
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qed$ ls
INFO        qed_debug.c    qed_hw.c             qed_iscsi.c  qed_ll2.h      qed_ptp.c       qed_selftest.h     qed_vf.h
Makefile    qed_debug.h    qed_hw.h             qed_iscsi.h  qed_main.c     qed_rdma.c      qed_sp.h
qed.h       qed_dev.c      qed_init_fw_funcs.c  qed_iwarp.c  qed_mcp.c      qed_rdma.h      qed_sp_commands.c
qed_cxt.c   qed_dev_api.h  qed_init_ops.c       qed_iwarp.h  qed_mcp.h      qed_reg_addr.h  qed_spq.c
qed_cxt.h   qed_fcoe.c     qed_init_ops.h       qed_l2.c     qed_mng_tlv.c  qed_roce.c      qed_sriov.c
qed_dcbx.c  qed_fcoe.h     qed_int.c            qed_l2.h     qed_ooo.c      qed_roce.h      qed_sriov.h
qed_dcbx.h  qed_hsi.h      qed_int.h            qed_ll2.c    qed_ooo.h      qed_selftest.c  qed_vf.c
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qed$ cat INFO
Congratulations, you found the clue!
The next clue is in: /usr/share/racket/pkgs/data-enumerate-lib/data/enumerate/lib

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qed$ ls /usr/share/racket/pkgs/data-enumerate-lib/data/enumerate/lib
README  compiled  unsafe.rkt
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/qlogic/qed$ cat /usr/share/racket/pkgs/data-enumerate-lib/data/enumerate/lib/README
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{MtHf_PmCi8qK1jwWjvdSuJ2zPFQ.QX5IDO0wyM3MzNzEzW}
```

## What I learned
I learnt how to effectively use the "ls", "cat" and "cd" command. 
## References 
None.

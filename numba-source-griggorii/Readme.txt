https://github.com/Griggorii/python3.8-numba_amd64.deb

Patent rebuild autor griggorii <griggorii@gmail.com> ubuntu 20.04 glibc-2.31

+ data.tar.xz structure rebuild not default python3

/usr/lib/python3.8/

/usr/lib/python3.8/dist-packages/numba/

ar r python3-numba_amd64.deb debian-binary control.tar.xz data.tar.xz

Example edit control dependency repack to new deb

XZ_OPT=-9 tar -Jcvf control.tar.xz ./control ./postinst ./prerm

ar r python3-numba_amd64.deb debian-binary control.tar.xz data.tar.xz

 

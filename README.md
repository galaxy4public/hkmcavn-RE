# hkmcavn-RE
A repository to keep track of reverse engineering effort on HKMC firmware binaries

Each directory is named after the corresponding binary and contains an IDC file generated by IDA.
To use the IDC file, you need to acquire the binary first (e.g. by downloading the firmware from
HKMC, decrypting and unpacking the mango-rootfs.tar.gz archive), to download in install IDA (you
can get a Freeware edition, which works fine), then you need to load the binary into IDA (by
either starting IDA and opening the binary via GUI or by launching IDA with the binary given via
the `-c` command line option).  Finally, depending on your version of IDA you will either have
the "Load IDC" or "Script file..." entry under the "File" menu.  Use the entry your version
provides to load the file.

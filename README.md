# Bitwig Studio on Fedora
Automatization of Bitwig Studio installation process on Fedora.

For older versions check the repository tags.

## TAGS
- Bitwig Studio **3.2.7** (Fedora 32)
- Bitwig Studio **3.1.3** (Fedora 31)
- Bitwig Studio **3.1.1** (Fedora 30)
- Bitwig Studio **2.4.2** (Fedora 29)

----
## Install procedure:
1. ```git clone https://github.com/nunodio/bitwig-fedora.git```

2. ```cd bitwig-fedora```

3. ```chmod +x bitwig-fedora.sh```

4. ```sudo ./bitwig-fedora.sh -i```


## Uninstall procedure
This procedure is only available if you installed Bitwig Studio with this script.

To uninstall Bitwig Studio run the **same script version/tag** used in the installation.
Example: if you installed Bitwig Studio with the script version/tag 2.2.2, use the same script version to uninstall it.

1. ```sudo ./bitwig-fedora.sh -u```

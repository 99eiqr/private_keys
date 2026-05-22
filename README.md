# Keys For Signing Build

> Private signing keys for secure build integration.

---

### How?

```bash
git clone https://github.com/pos-hound/private_keys.git vendor/private/keys
cd vendor/private/keys
./keys.sh
```

### Include in Your Device Makefile

Add the following line to your device makefile:

```makefile
-include vendor/private/keys/keys.mk
```

---

<p align="center">CRUOOOOOT</p>

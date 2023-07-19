## Prebuilt APKs

- Clone this repository in `vendor/prebuilt-apps` in your ROM's Sourcecode.

```
git clone https://github.com/parixxshit/android_vendor_prebuilt-apps.git vendor/prebuilt-apps
```

- Inherit Prebuilt APKs Using these lines in your Device Makefile.

```
# Prebuilt APKs
$(call inherit-product-if-exists, vendor/prebuilt-apps/config.mk)
```

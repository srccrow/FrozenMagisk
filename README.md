# FrozenMagisk

This version of Magisk, 24.1 should be used on Android devices using an old kernel like 3.4.113 and 3.18.140 to utilize addon.d inside TWRP and being able to enable Zygisk, furthermore devices utilizing these kernel versions should avoid using AdGuard Certificate module as it disables Zygisk.

# Reference

https://github.com/topjohnwu/Magisk/issues/5395

# Alternative to AdGuard Certificate

Alternative is using module Move Certificate + Specific browsers that don't enforce Certificate Transparency like Mulch https://gitlab.com/divested-mobile/mulch or Bromite https://www.bromite.org/ enabling chrome://flags#allow-user-certificates Enabled chrome://flags#certificate-transparency-enabled Disabled + Specific Hooking using https://github.com/jpacg/TrustMeAlready of the Browser.

<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  
<remote name="Dooms-v" fetch="https://github.com/Dooms-v" />
<remote name="kdrag0n" fetch="https://github.com/kdrag0n" />

     <!--Trees-->

  <project path="device/xiaomi/beryllium" name="beryllium" remote="Dooms-v" revision="Elixir" />
  
  <project path="device/xiaomi/sdm845-common" name="common" remote="Dooms-v" revision="SL" />
           
  <project path="vendor/xiaomi" name="vendor" remote="Dooms-v" revision="12.1" />

  <project path="kernel/xiaomi/sdm845" name="kernel_xiaomi_sdm845" remote="Dooms-v" revision="12.1-silver" />
  
    <!-- Toolchain -->

  <project path="prebuilts/clang/host/linux-x86/clang-proton" name="proton-clang" remote="Dooms-v" revision="master" clone-depth="1" />

</manifest>

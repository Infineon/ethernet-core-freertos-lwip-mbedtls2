<img src="./images/IFX_LOGO_600.gif" align="right" width="150"/>

# Ethernet Core FreeRTOS lwIP mbedtls library for KIT_T2G-B-H_LITE
**This library has same functionality with original [Ethernet Core FreeRTOS lwIP mbedtls library](https://github.com/Infineon/ethernet-core-freertos-lwip-mbedtls) except for a few changes which are made to fit with use on [KIT_T2G-B-H_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_t2g-b-h_lite/).**

## Base Library
- [Ethernet Core FreeRTOS lwIP mbedtls library](https://github.com/Infineon/ethernet-core-freertos-lwip-mbedtls) : release-v1.0.0 (SHA-1: 9e92746d75779dcaaa5d3e35aa48b6015fa3029c)

## Differences

**Library dependencies**
<table border="1" style="border-collapse: collapse">
<thead><tr>
<th></th><th>Base Library</th><th>This Library</th></tr></thead>
<tbody>
<tr><td><code>Secure sockets library</code></td><td><a href="https://github.com/Infineon/secure-sockets">GitHub</a></td><td><a href="https://github.com/Infineon/secure-sockets2">GitHub</a></td></tr>
<tr><td><code>Ethernet Connection Manager (ECM)</code></td><td><a href="https://github.com/Infineon/ethernet-connection-manager">GitHub</a></td><td><a href="https://github.com/Infineon/ethernet-connection-manager2">GitHub</a></td></tr>
<tr><td><code>mbedTLS Crypto acceleration</code></td><td>N/A</td><td><a href="https://github.com/Infineon/cy-mbedtls-acceleration">GitHub</a></td></tr>
</tbody>
</table>

## References  

ModusToolbox™ is available online:
- <https://www.infineon.com/modustoolbox>

Associated TRAVEO™ T2G MCUs can be found on:
- <https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/>

More code examples can be found on the GIT repository:
- [TRAVEO™ T2G Code examples](https://github.com/orgs/Infineon/repositories?q=mtb-t2g-&type=all&language=&sort=)

For additional trainings, visit our webpage:  
- [TRAVEO™ T2G trainings](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/32-bit-traveo-t2g-arm-cortex-for-body/traveo-t2g-cyt4bf-series/#!trainings)

For questions and support, use the TRAVEO™ T2G Forum:  
- <https://community.infineon.com/t5/TRAVEO-T2G/bd-p/TraveoII>  

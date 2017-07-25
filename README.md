# ubnt-airview2-cc2511-f32
 Hi,
 
 I have a USB dongle AirView2 in my drawer. I would like to find a new use for it. Maybe a sniffing device.
 
 AirView2 is a special Spectrum analyzer for the 2.4 GHz band.
 
 __DISCLAIMER: This software/tutorial is for educational purposes only. It should not be used for illegal activity. The author is not responsible for its use. Don't be a dick.__
 
## Hardware
AirView2 has:
- USB Type A
- MMCX for external antenna
- cpu CC2511-F32
- green LED
- pin on PCB for Button
- pin PWR (power)
- pin RESET_N
- pin CLK
- pin DATA
- pin GND

[![PCB](https://wakygw-am3pap001.files.1drv.com/y4m6NaRCc7P8FNoK_G2AHrIFgZnmZdj8VMrzq1CEHk7PKtiKo6LBDYePhe1VSKdz6yNzmSBM3jL4N4TRxrhWEFwAFrDNFdiAR2PSLgIxOOZt4Gdkyh5a9wAV18kb1gn35Q7tQf68YtnukdZlUcpERrCH_3xLsQiOZS54CE0D4X40z9NDzGRUrJFmUbfpEOzWeNcLCJORXsLGM_AA9vq_8xRDA?width=600&height=912&cropmode=none)](https://wakygw-am3pap001.files.1drv.com/y4m6NaRCc7P8FNoK_G2AHrIFgZnmZdj8VMrzq1CEHk7PKtiKo6LBDYePhe1VSKdz6yNzmSBM3jL4N4TRxrhWEFwAFrDNFdiAR2PSLgIxOOZt4Gdkyh5a9wAV18kb1gn35Q7tQf68YtnukdZlUcpERrCH_3xLsQiOZS54CE0D4X40z9NDzGRUrJFmUbfpEOzWeNcLCJORXsLGM_AA9vq_8xRDA?width=600&height=912&cropmode=none)

### Detail hardware
CC2511-F32

[![CC2511-F32](https://wqkegw-am3pap001.files.1drv.com/y4m-CTxOo-KGqSoPBWzbJO40sWSBwmYoYv0dC7fhfoQYL0C-o12RR_lr-pEBzmW06qlv6VGQ_YUP_kTGooOVhz3_XR2qxWZ-_8QWGyBwcweT5OQWEHppudYKucGrMiOf3QLhGBnB6hNP3tD7XDk7lUEGPgORuUa10PQqWz96-IdHVKKOF4zhd4hP9vPJXdJHv85wHjcH_aANDhkA6gSz7F3Zw?width=320&height=298&cropmode=none)](https://wqkegw-am3pap001.files.1drv.com/y4m-CTxOo-KGqSoPBWzbJO40sWSBwmYoYv0dC7fhfoQYL0C-o12RR_lr-pEBzmW06qlv6VGQ_YUP_kTGooOVhz3_XR2qxWZ-_8QWGyBwcweT5OQWEHppudYKucGrMiOf3QLhGBnB6hNP3tD7XDk7lUEGPgORuUa10PQqWz96-IdHVKKOF4zhd4hP9vPJXdJHv85wHjcH_aANDhkA6gSz7F3Zw?width=320&height=298&cropmode=none)

Reserved for the button

[![Reserved for the button](https://wakwgw-am3pap001.files.1drv.com/y4m-MugYJEm_7J2PrZcnTWM56OXjCgu1P-pajTVCC6vn3C63WGM_m1-z0ezvMNNY1eCnsL5bvHxSAtMMR1fWoKP1uzdO5kFlBAlVX9mC7ICtX1G1bCHO1yWBQcwtPbrQkv6NiLE-fs5UpISPex_0ikX4o5ybGtePnJhmr91U3YcEX0xfHJERdEkqTsYRV_WTg2b5F3mtaK5bjcPyE6NrUlg3Q?width=320&height=291&cropmode=none)](https://wakwgw-am3pap001.files.1drv.com/y4m-MugYJEm_7J2PrZcnTWM56OXjCgu1P-pajTVCC6vn3C63WGM_m1-z0ezvMNNY1eCnsL5bvHxSAtMMR1fWoKP1uzdO5kFlBAlVX9mC7ICtX1G1bCHO1yWBQcwtPbrQkv6NiLE-fs5UpISPex_0ikX4o5ybGtePnJhmr91U3YcEX0xfHJERdEkqTsYRV_WTg2b5F3mtaK5bjcPyE6NrUlg3Q?width=320&height=291&cropmode=none)

???

[![???](https://wakxgw-am3pap001.files.1drv.com/y4mgS5jGChv2CmPmwah9atZ6TD2NJt0WQIvMPMV-Bkv90xhxzN53mBBGGaclh7GJuKcafMXbnEtKDvLqnaDDyvdD2UWJnCZeqnTLgoO2yb1uP1rb38yT7qRyrNKbLWg2H4awdNJRuDZw9BGEH-IN7DNbKOPbxVzgbRl_0Oly0bhb1DN6WEM11mxcm_cAQlKHChqxHB2lsjF7FPB3lx-r-1hXg?width=320&height=273&cropmode=none)](https://wakxgw-am3pap001.files.1drv.com/y4mgS5jGChv2CmPmwah9atZ6TD2NJt0WQIvMPMV-Bkv90xhxzN53mBBGGaclh7GJuKcafMXbnEtKDvLqnaDDyvdD2UWJnCZeqnTLgoO2yb1uP1rb38yT7qRyrNKbLWg2H4awdNJRuDZw9BGEH-IN7DNbKOPbxVzgbRl_0Oly0bhb1DN6WEM11mxcm_cAQlKHChqxHB2lsjF7FPB3lx-r-1hXg?width=320&height=273&cropmode=none)

Voltage Regulator

[![Voltage Regulator](https://wakvgw-am3pap001.files.1drv.com/y4mNCcrIpWTeUmx4CeEPQohQqzc0-efEijlMu2Tw1a__ycdiMDwLneI7wBxplSeGwnI4ydlZwNOJBXbSN8YWoYJSxilCnuDMOJgCHUZS7AA0TGkIXDOozRlkG4PdAjISIR1yOPStiix3-Wxu0dCEp50aGOJp6zgEJYkEENeD9MBHLYJAL3YHBf2__kfVgKlHg-2XaIRdrmPRqnMnHzSTPeBKg?width=320&height=320&cropmode=none)](https://wakvgw-am3pap001.files.1drv.com/y4mNCcrIpWTeUmx4CeEPQohQqzc0-efEijlMu2Tw1a__ycdiMDwLneI7wBxplSeGwnI4ydlZwNOJBXbSN8YWoYJSxilCnuDMOJgCHUZS7AA0TGkIXDOozRlkG4PdAjISIR1yOPStiix3-Wxu0dCEp50aGOJp6zgEJYkEENeD9MBHLYJAL3YHBf2__kfVgKlHg-2XaIRdrmPRqnMnHzSTPeBKg?width=320&height=320&cropmode=none)
## Pin connections
?pic
?pic

Do you have any idea?



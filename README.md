# Z97-HD3-Patches

Patches for the Z97-HD3.

SSDT-HACK, Simulating OS X/MacOS which is needed for USB to function properly.
SSDT-IGPU, Onboard IGPU which injects appropriate Device ID for HD 4600 Desktop, Takes care of injecting ig-platform-id via Clover's Config.
SSDT-LPC, Injecting supported Device ID in order for AppleLPC to load. Note Z97/H97 shares same supported Device ID as Skylake/Z170/H170.
SSDT-MCHC, Injecting Device MCHC which is missing without SSDT-MCHC.
SSDT-SATA, Injects appropriate AAPL Values for SATA also fixes cosmetic problem.
SSDT-SMBUS, Injects DVL0 device for SMBUS Controller.
SSDT-UIAC, Port Mapping. Note removed 3rd USB 2 header, USB 3 port on back to stay within 15 Port Limit Restrictor.
SSDT-XHC, Injects appropriate AAPL Values/ Fixed USB Power/Charging.
SSDT-XWAK, Fixes known issues after sleep i.e Kernel Panics out of cold long sleep states/fixed instant wake ups.

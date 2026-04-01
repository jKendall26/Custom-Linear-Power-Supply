# System Parts

This is a description of all the parts used in this project in order from the input to the output

## Line Input Stage

The line input is a switchable [IEC 60320 C13](https://en.wikipedia.org/wiki/IEC_60320#C13/C14_coupler) female recepticle

## Over current breaker

There will be a one amp breaker/resettable fuse

## Transformer

NOTE TO SELF, USE [circuit lab](https://www.circuitlab.com/) to make the full circuit/ transformer

Likely in the neighborhood of 600VA

-> Step down transformer

-> Primary is center taped, 

-> DCR across full primary is $1.2 \ \Omega$

-> DCR is split $1 \ \Omega$ on one side and $0.2 \ \Omega$ on the other

-> Turn ratio is X:X %need to find%

-> Secondary is a single winding

## Rectifier

This device will use an all-in-one full bridge rectifier I harvested from a dead power supply

It's model number is [XXXXX]() -> [Datasheet]()

## Smoothing Capacitor(s)

The size of a smoothing capacitor for a full bridge rectified signal is:

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ C=\frac{I_{load}}{2 \bullet f_{AC} \bullet V_{ripple}}$

NOTE: $I_{load}$ is the secondary side current

For this project I assume I

## Linear Regulators

Texas Instruments LM1084 [3.3V Regulator](https://www.mouser.com/ProductDetail/926-LM1084IT-3.3NOPB) -> [Datasheet](Texas_Instruments_LM1084_datasheet.pdf)

ONSEMI MC7800D [5V Regulator](https://www.mouser.com/ProductDetail/863-MC7805BTG) -> [Datasheet](onsemi_MC7800-D_datasheet.PDF)

Texas Instruments LM2940c [12V Regulator](https://www.mouser.com/ProductDetail/926-LM2940T-12.0NOPB) -> [Datasheet](Texas_Instruments_lm2940c_datasheet.pdf)

ST Microelectronics LM317 [Adjustable Regulator](https://www.mouser.com/ProductDetail/511-LM317T-DG) -> [Datasheet](ST_Microelectronics_lm317_datasheet.pdf)

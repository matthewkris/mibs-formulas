# IBU

## Info

## Tinseth

#### Formula

IBUs = Decimal Alpha Acid Utilization * mg/l of added alpha acids

#### Variables

- mg/l of added alpha acids = (decimal AA rating * ozs hops * 7490) / gallons of wort
- Decimal Alpha Acid Utilization = Bigness Factor * Boil Time Factor
- Bigness Factor = 1.65 * 0.000125^(wort gravity – 1)
- Boil Time Factor = (1 – e^(-0.04 * time in mins) )/4.15

#### Example

## Rager

#### Formula

IBU = (OUNCES OF HOPS * %UTILIZATION * %ALPHA * 7462) / (Batch Volume* (1 + GA))

#### Variables

GA = (BOIL_GRAVITY – 1.050) / 0.2

%UTILIZATION = 18.11 + (13.86 * hyptan[(MINUTES – 31.32) / 18.27] )

#### Example

## Garetz

#### Formula

IBU = (%Utilization * %Alpha * Hop weight(oz) * 0.749) / (Volume in gallons * CA)

#### Variables

Utilization % = 7.2994 + (15.0746 * tanh((minutes – 21.86) / 24.71))

CA = GF * HF * TF

So in order to find CA for the above formula, we first need to calculate our CF number.

CF = Final Volume / Pre-Boil Volume

Once we’ve solved for CF, We then need to find our BG value.

BG = (CF * (Starting Gravity – 1)) + 1

Now that we’ve solved for Boil gravity, we can then begin calculating for GF:

GF = (BG – 1.050)/.2 +1
HF = ((CF * Desired IBUs)/260) + 1
TF = ((Elevation in feet) / 550) * 0.02) + 1

#### Example

## Daniels

#### Formula
#### Variables
#### Example
# IBU

## General Info

- [Tinseth](#tinseth)
- [Rager](#rager)
- [Garetz](#garetz)
- [Daniels](#daniels)

## <a name="tinseth"></a>Tinseth

The Tinseth formula is used by default in MIBrew.

#### Formula

IBU = Decimal Alpha Acid Utilization * mg/l of added alpha acids

#### Variables

- mg/l of added alpha acids = (decimal AA rating * Hop weight(oz) * 7490) / gallons of wort
- Decimal Alpha Acid Utilization = Bigness Factor * Boil Time Factor
- Bigness Factor = 1.65 * 0.000125^(wort gravity – 1)
- Boil Time Factor = (1 – e^(-0.04 * Minutes) )/4.15

#### Example

## <a name="rager"></a>Rager

#### Formula

IBU = (Hop weight(oz) * %Utilization * %Alpha * 7462) / (Batch Volume* (1 + GA))

#### Variables

- GA = (Boil Gravity – 1.050) / 0.2
- %Utilization = 18.11 + (13.86 * hyptan[(Minutes – 31.32) / 18.27] )

#### Example

## <a name="garetz"></a>Garetz

#### Formula

IBU = (%Utilization * %Alpha * Hop weight(oz) * 0.749) / (Volume in gallons * CA)

#### Variables

- %Utilization = 7.2994 + (15.0746 * tanh((Minutes – 21.86) / 24.71))
- CA = GF * HF * TF

- CF = Final Volume / Pre-Boil Volume
- BG = (CF * (Starting Gravity – 1)) + 1

- GF = (BG – 1.050)/.2 +1
- HF = ((CF * Desired IBUs)/260) + 1
- TF = ((Elevation in feet) / 550) * 0.02) + 1

#### Example

## <a name="daniels"></a>Daniels

#### Formula
#### Variables
#### Example
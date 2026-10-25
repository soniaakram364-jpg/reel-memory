# USED — reel prompt history (one line per prompt)

Format: `dialogue | location | outfit | structure | gesture`
structure = shot size · camera height · distance   |   gesture = family · amplitude(cm) · timing (pre/on/post)
`—` means the prompt was written before the registry existed; treat the line as used but unknown on that axis.

Rules for any AI reading this file:
- Never reuse a location, outfit, structure or gesture token that already appears below.
- A dialogue may only return after every other usable line has been used, and never with the same location or gesture.
- After writing N prompts, output one `USED` block of N lines in this exact format instead of prose.

D01 | studio                    | an olive crewneck sweatshirt + soft gr| hands·+eye·1.5m | question·50·post
D04 | hotel room                | a cream silk blouse + tailored black t| elbow·-eye·2m   | question·50·pre
D01 | rented bedroom            | An oversized grey jersey tee slipping | —               | —
D08 | kitchen at night          | A cream ribbed tank with soft grey sho| —               | —
D04 | living room in late aftern| A burgundy satin slip dress with thin | —               | —
D16 | city balcony at dusk      | A sage linen shirt worn open over a cr| —               | —
D05 | cafe back booth           | A charcoal jersey tee tucked into stra| —               | —
D31 | hallway by the front door | A black one-shoulder mini dress with a| —               | —
D06 | bedroom floor beside an un| A blush ribbed sleep set + cropped tan| —               | —
D42 | passenger seat of a parked| A light denim shirt open over a pale t| —               | —
D07 | bathroom at the basin     | A cream waffle robe loosely belted ove| —               | —
D51 | small garden patio        | An olive fine-knit top with cream tail| —               | —
D58 | stone step outside a front| A mustard cotton tee with high-waisted| —               | —
D10 | small shop counter        | A tan linen shirt with the sleeves rol| —               | —
D11 | living room floor by a low| A navy ribbed lounge set + long sleeve| —               | —
D19 | park bench on a path      | A red wrap midi dress with a V necklin| —               | —
D18 | train seat by the window  | A grey hoodie with the sleeves pushed | —               | —
D58 | train seat by the window  | A grey hoodie with the sleeves pushed | —               | —
D31 | living room floor         | A navy ribbed lounge set + long sleeve| —               | —
D56 | cafe back booth           | A charcoal jersey tee tucked into stra| —               | —
D09 | studio                    | an olive crewneck sweatshirt + soft gr| thigh·+eye·1.5m | count·50·on
D12 | hotel room                | a black slip dress with thin straps + | thigh·-eye·2m   | question·35·on
D21 | kitchen                   | a black fitted turtleneck + a pleated | hands·-eye·1.5m | self_point·15·post
D22 | bedroom                   | a soft white cotton shirt + unbuttoned| thigh·-eye·1m   | offer·15·on
D23 | laundry room              | a pale pink knit cardigan + ripped blu| thigh·eye·1.5m  | offer·50·post
D45 | shop                      | a black bodycon dress with long sleeve| elbow·+eye·1.5m | stop·15·pre


# USED — reel prompt history (one line per prompt)

Format: `dialogue | location | outfit | structure | gesture`
structure = shot size · camera height · distance   |   gesture = family · amplitude(cm) · timing (pre/on/post)
`—` means the prompt was written before the registry existed; treat the line as used but unknown on that axis.

Rules for any AI reading this file:
- Never reuse a location, outfit, structure or gesture token that already appears below.
- A dialogue may only return after every other usable line has been used, and never with the same location or gesture.
- After writing N prompts, output one `USED` block of N lines in this exact format instead of prose.

D01 | studio                    | an olive crewneck sweatshirt + soft gr| hands·+eye·1.5m | question·50·post

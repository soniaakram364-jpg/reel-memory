# USED — reel prompt history (one line per prompt)

Format: `dialogue | location | outfit | structure | gesture`
structure = shot size · camera height · distance   |   gesture = family · amplitude(cm) · timing (pre/on/post)
`—` means the prompt was written before the registry existed; treat the line as used but unknown on that axis.

Rules for any AI reading this file:
- Never reuse a location, outfit, structure or gesture token that already appears below.
- A dialogue may only return after every other usable line has been used, and never with the same location or gesture.
- After writing N prompts, output one `USED` block of N lines in this exact format instead of prose.

USED
D01  | train seat                 | a black bodycon dress with long sleeves | thigh·+eye·1.5m | self_point·50·post
D04  | bedroom                    | a beige knit polo                      | hands·-eye·1m   | count·35·on
D05  | hallway                    | a pale pink knit cardigan              | hands·-eye·2m   | dismiss·15·pre
D06  | garden                     | a black bodycon dress with long sleeves | hands·+eye·1.5m | settle·50·on
D07  | kitchen                    | a black slip dress with thin straps    | thigh·eye·1.5m  | stop·35·on
D08  | hotel room                 | a black cotton camisole                | hands·eye·2m    | confess·15·post
D09  | bathroom                   | a charcoal jersey tee                  | knee·eye·1m     | question·50·pre
D10  | balcony                    | a black one-shoulder dress             | thigh·-eye·1m   | show·35·on
D11  | car                        | a black cotton camisole                | elbow·eye·1m    | offer·50·post
D12  | living room                | a denim shirt                          | thigh·-eye·1.5m | self_touch·15·pre
D16  | laundry room               | a deep green column dress              | knee·+eye·2m    | self_point·35·on
D18  | park path                  | a deep green column dress              | elbow·+eye·1m   | count·35·post
D19  | cafe booth                 | a cream silk blouse                    | elbow·-eye·1.5m | dismiss·35·post
D21  | bedroom                    | a burgundy wrap top                    | elbow·+eye·2m   | settle·50·pre
D22  | studio                     | a black slip dress with thin straps    | knee·-eye·1m    | stop·35·pre
D23  | garden                     | a denim shirt                          | thigh·+eye·1m   | confess·35·pre
D31  | stairwell                  | a denim shirt                          | knee·eye·1.5m   | question·35·pre
D42  | hotel room                 | a black slip dress with thin straps    | thigh·eye·2m    | show·35·pre
D45  | hallway                    | a red wrap dress                       | elbow·eye·1.5m  | offer·50·pre
D46  | balcony                    | a soft white cotton shirt              | knee·-eye·1.5m  | self_touch·35·pre
D50  | shop                       | a burgundy satin slip dress            | elbow·+eye·1.5m | self_point·35·pre
D51  | living room                | a plain white tee                      | thigh·-eye·2m   | count·50·post
D52  | bathroom                   | a soft white cotton shirt              | hands·-eye·1.5m | dismiss·50·post
D53  | garden                     | a grey blazer over a white tee         | knee·eye·2m     | settle·50·post
D56  | train seat                 | a denim shirt                          | knee·+eye·1.5m  | stop·35·on
D57  | bedroom                    | a deep green column dress              | hands·eye·1m    | confess·15·pre
D58  | laundry room               | a burgundy wrap top                    | elbow·-eye·2m   | question·50·post
D59  | balcony                    | a grey hoodie                          | thigh·eye·1m    | show·15·pre
D01  | kitchen                    | a cream silk blouse                    | elbow·eye·2m    | offer·15·post
D04  | hotel room                 | a cream silk blouse                    | knee·-eye·2m    | self_touch·15·post
D05  | studio                     | an oversized grey jersey tee           | hands·eye·1.5m  | self_point·50·post
D06  | garden                     | a navy shirt with the cuffs rolled     | knee·+eye·1m    | count·35·on
D07  | car                        | a beige knit polo                      | hands·+eye·2m   | dismiss·15·on
D08  | living room                | a beige knit polo                      | elbow·-eye·1m   | settle·15·post
D09  | hallway                    | a beige knit polo                      | thigh·+eye·2m   | stop·50·post
D10  | balcony                    | a denim shirt                          | hands·+eye·1m   | confess·35·post
D11  | cafe booth                 | a plain white tee                      | thigh·+eye·1.5m | question·15·pre
D12  | bedroom                    | a cream ribbed tank                    | hands·-eye·1m   | show·35·post
D16  | bathroom                   | a cream silk blouse                    | hands·-eye·2m   | offer·15·on
D18  | garden                     | a burgundy satin slip dress            | hands·+eye·1.5m | self_touch·35·on
D19  | stairwell                  | a deep green column dress              | thigh·eye·1.5m  | self_point·35·pre
D21  | hotel room                 | a navy ribbed long-sleeve              | hands·eye·2m    | count·15·on
D22  | laundry room               | an olive crewneck sweatshirt           | knee·eye·1m     | dismiss·15·post
D23  | balcony                    | a soft white cotton shirt              | thigh·-eye·1m   | settle·35·on
D31  | shop                       | a navy shirt with the cuffs rolled     | elbow·eye·1m    | stop·35·post
D42  | living room                | an olive crewneck sweatshirt           | thigh·-eye·1.5m | confess·35·on
D45  | studio                     | a plain white tee                      | knee·+eye·2m    | question·50·post
D46  | garden                     | a burgundy wrap top                    | elbow·+eye·1m   | show·35·post
D50  | train seat                 | a grey hoodie                          | elbow·-eye·1.5m | offer·35·pre
D51  | bedroom                    | a navy shirt with the cuffs rolled     | elbow·+eye·2m   | self_touch·50·pre
D52  | hallway                    | a charcoal jersey tee                  | knee·-eye·1m    | self_point·35·pre
D53  | balcony                    | an olive crewneck sweatshirt           | thigh·+eye·1m   | count·50·pre
D56  | kitchen                    | a charcoal jersey tee                  | knee·eye·1.5m   | dismiss·50·pre
D57  | hotel room                 | a charcoal jersey tee                  | thigh·eye·2m    | settle·50·on
D58  | bathroom                   | a charcoal jersey tee                  | elbow·eye·1.5m  | stop·15·pre
D59  | garden                     | a navy shirt with the cuffs rolled     | knee·-eye·1.5m  | confess·50·pre
D01  | car                        | a charcoal jersey tee                  | elbow·+eye·1.5m | question·15·post
D04  | living room                | a burgundy wrap top                    | thigh·-eye·2m   | show·50·pre
D05  | laundry room               | a navy ribbed long-sleeve              | hands·-eye·1.5m | offer·50·pre
D06  | balcony                    | a striped long-sleeve top              | knee·eye·2m     | self_touch·35·pre
D07  | cafe booth                 | an olive crewneck sweatshirt           | knee·+eye·1.5m  | self_point·50·pre
D08  | bedroom                    | a beige knit polo                      | hands·eye·1m    | count·15·pre
D09  | studio                     | a red wrap dress                       | elbow·-eye·2m   | dismiss·15·on
D10  | garden                     | an oversized grey jersey tee           | thigh·eye·1m    | settle·35·on
D11  | stairwell                  | a grey hoodie                          | elbow·eye·2m    | stop·15·on
D12  | hotel room                 | a burgundy wrap top                    | knee·-eye·2m    | confess·50·post
D16  | hallway                    | an olive crewneck sweatshirt           | hands·eye·1.5m  | question·35·on
D18  | balcony                    | a navy ribbed long-sleeve              | knee·+eye·1m    | show·35·on
D19  | shop                       | a charcoal jersey tee                  | hands·+eye·2m   | offer·35·post
D21  | living room                | a charcoal jersey tee                  | elbow·-eye·1m   | self_touch·50·pre
D22  | laundry room               | a red wrap dress                       | thigh·+eye·2m   | self_point·50·on
D23  | garden                     | a red wrap dress                       | hands·+eye·1m   | count·15·on
D31  | train seat                 | a denim shirt                          | thigh·+eye·1.5m | dismiss·35·on
D42  | bedroom                    | a pale pink knit cardigan              | hands·-eye·1m   | settle·35·pre
D45  | studio                     | a pale pink knit cardigan              | hands·-eye·2m   | stop·50·on
D46  | balcony                    | a pale pink knit cardigan              | hands·+eye·1.5m | confess·50·on
D50  | kitchen                    | an olive crewneck sweatshirt           | thigh·eye·1.5m  | question·35·on
D51  | hotel room                 | a red wrap dress                       | hands·eye·2m    | show·35·pre
D52  | hallway                    | a navy shirt with the cuffs rolled     | knee·eye·1m     | offer·50·pre
D53  | garden                     | a denim shirt                          | thigh·-eye·1m   | self_touch·35·post
D56  | car                        | a pale pink knit cardigan              | elbow·eye·1m    | self_point·35·post
D57  | living room                | a denim shirt                          | thigh·-eye·1.5m | count·50·pre
D58  | laundry room               | a grey hoodie                          | knee·+eye·2m    | dismiss·35·pre
D59  | balcony                    | a deep green column dress              | elbow·+eye·1m   | settle·50·pre
D01  | cafe booth                 | a pale pink knit cardigan              | elbow·-eye·1.5m | stop·35·pre
D04  | bedroom                    | a denim shirt                          | elbow·+eye·2m   | confess·50·on
D05  | studio                     | an oversized grey jersey tee           | knee·-eye·1m    | question·15·post
D06  | garden                     | an olive crewneck sweatshirt           | thigh·+eye·1m   | show·15·post
D07  | stairwell                  | a pale pink knit cardigan              | knee·eye·1.5m   | offer·35·post
D08  | hotel room                 | a red wrap dress                       | thigh·eye·2m    | self_touch·35·post
D09  | hallway                    | a denim shirt                          | elbow·eye·1.5m  | self_point·15·on
D10  | balcony                    | a red wrap dress                       | knee·-eye·1.5m  | count·15·post
D11  | shop                       | a denim shirt                          | elbow·+eye·1.5m | dismiss·15·pre
D12  | living room                | a denim shirt                          | thigh·-eye·2m   | settle·15·post
D16  | laundry room               | a striped long-sleeve top              | hands·-eye·1.5m | stop·15·on
D18  | garden                     | a denim shirt                          | knee·eye·2m     | confess·15·post
D19  | kitchen                    | a striped long-sleeve top              | knee·+eye·1.5m  | question·50·pre
D21  | bedroom                    | a striped long-sleeve top              | hands·eye·1m    | show·15·post
D22  | studio                     | a denim shirt                          | elbow·-eye·2m   | offer·50·pre
D23  | balcony                    | a striped long-sleeve top              | thigh·eye·1m    | self_touch·35·on
USED
D01  | balcony                    | a grey hoodie                          | elbow·eye·1m    | question·15·on
D04  | kitchen                    | a beige knit polo                      | thigh·+eye·1.5m | confess·15·on
D05  | park path                  | a denim shirt                          | hands·eye·1.5m  | self_point·15·pre
D06  | car                        | a cream ribbed tank                    | knee·+eye·2m    | offer·35·on
D07  | balcony                    | a grey blazer over a white tee         | knee·eye·1m     | show·50·post
D08  | kitchen                    | a red wrap dress                       | hands·-eye·2m   | self_touch·15·on
D09  | garden                     | a black one-shoulder dress             | knee·eye·2m     | dismiss·50·on
D10  | bedroom                    | a soft white cotton shirt              | thigh·-eye·1m   | settle·15·pre
D11  | park path                  | a red wrap dress                       | thigh·-eye·1.5m | count·50·on
D12  | car                        | a burgundy wrap top                    | hands·-eye·1.5m | stop·15·post
D16  | garden                     | a deep green column dress              | elbow·-eye·1.5m | question·50·on
D18  | car                        | a grey blazer over a white tee         | hands·-eye·1m   | confess·15·on
D19  | park path                  | a denim shirt                          | knee·+eye·1.5m  | self_point·15·post
D21  | living room                | a pale pink knit cardigan              | elbow·+eye·1.5m | offer·35·on
D22  | park path                  | a charcoal jersey tee                  | elbow·+eye·2m   | show·15·on
D23  | train seat                 | a cream ribbed tank                    | hands·+eye·1m   | self_touch·50·on
D31  | balcony                    | a black slip dress with thin straps    | knee·-eye·1m    | dismiss·50·on
D42  | stairwell                  | a charcoal jersey tee                  | knee·-eye·1.5m  | settle·15·pre
D45  | car                        | a burgundy satin slip dress            | thigh·+eye·2m   | count·35·pre
D46  | bedroom                    | a black one-shoulder dress             | hands·+eye·1.5m | stop·15·post
D50  | bathroom                   | a navy shirt with the cuffs rolled     | thigh·eye·1.5m  | question·50·on
D51  | hallway                    | a cream ribbed tank                    | elbow·eye·2m    | confess·15·on
D52  | kitchen                    | a plain white tee                      | elbow·-eye·2m   | self_point·15·pre
D53  | stairwell                  | a cream ribbed tank                    | hands·eye·2m    | offer·50·on
D56  | bedroom                    | a denim shirt                          | thigh·+eye·1m   | show·15·on
D57  | bedroom                    | a cream ribbed tank                    | elbow·eye·1.5m  | self_touch·50·on
D58  | car                        | a soft white cotton shirt              | thigh·-eye·2m   | dismiss·50·on
D59  | bathroom                   | a burgundy wrap top                    | thigh·eye·1m    | settle·35·post
D01  | stairwell                  | a beige knit polo                      | elbow·-eye·1m   | count·50·on
D04  | stairwell                  | a cream silk blouse                    | hands·eye·1m    | stop·15·post
D05  | park path                  | a navy ribbed long-sleeve              | thigh·eye·2m    | question·35·post
D06  | living room                | a navy ribbed long-sleeve              | hands·+eye·2m   | confess·15·on
D07  | garden                     | a burgundy satin slip dress            | knee·+eye·1m    | self_point·15·post
D08  | laundry room               | a soft white cotton shirt              | knee·-eye·2m    | offer·15·pre
D09  | stairwell                  | a navy shirt with the cuffs rolled     | elbow·+eye·1m   | show·50·on
D10  | bathroom                   | a striped long-sleeve top              | knee·eye·1.5m   | self_touch·50·post
D11  | cafe booth                 | a cream silk blouse                    | elbow·eye·1m    | dismiss·50·on
D12  | stairwell                  | a navy shirt with the cuffs rolled     | thigh·+eye·1.5m | settle·15·on
D16  | stairwell                  | a navy shirt with the cuffs rolled     | hands·eye·1.5m  | count·35·pre
D18  | stairwell                  | an olive crewneck sweatshirt           | knee·+eye·2m    | stop·50·pre
D19  | park path                  | an oversized grey jersey tee           | knee·eye·1m     | question·50·on
D21  | stairwell                  | a charcoal jersey tee                  | hands·-eye·2m   | confess·15·on
D22  | park path                  | a deep green column dress              | knee·eye·2m     | self_point·15·post
D23  | hotel room                 | a navy shirt with the cuffs rolled     | thigh·-eye·1m   | offer·35·on
D31  | hotel room                 | a red wrap dress                       | thigh·-eye·1.5m | show·50·post
D42  | hallway                    | a grey hoodie                          | hands·-eye·1.5m | self_touch·50·post
D45  | laundry room               | a red wrap dress                       | elbow·-eye·1.5m | dismiss·50·on
D46  | studio                     | a burgundy wrap top                    | hands·-eye·1m   | settle·15·on
D50  | park path                  | a pale pink knit cardigan              | knee·+eye·1.5m  | count·50·on
D51  | cafe booth                 | an olive crewneck sweatshirt           | elbow·+eye·1.5m | stop·15·post
D52  | kitchen                    | a denim shirt                          | elbow·+eye·2m   | question·35·post
D53  | stairwell                  | a striped long-sleeve top              | hands·+eye·1m   | confess·15·on
D56  | laundry room               | a deep green column dress              | knee·-eye·1m    | self_point·15·post
D57  | cafe booth                 | a burgundy satin slip dress            | knee·-eye·1.5m  | offer·50·on
D58  | car                        | a denim shirt                          | thigh·+eye·2m   | show·50·on
D59  | living room                | a beige knit polo                      | hands·+eye·1.5m | self_touch·50·post
D01  | hallway                    | a deep green column dress              | thigh·eye·1.5m  | dismiss·50·on
D04  | laundry room               | an oversized grey jersey tee           | elbow·eye·2m    | settle·35·post
D05  | shop                       | a charcoal jersey tee                  | elbow·-eye·2m   | count·50·on
D06  | cafe booth                 | a red wrap dress                       | hands·eye·2m    | stop·50·pre
D07  | stairwell                  | a striped long-sleeve top              | thigh·+eye·1m   | question·50·on
D08  | laundry room               | a denim shirt                          | elbow·eye·1.5m  | self_point·15·pre
D09  | kitchen                    | a pale pink knit cardigan              | thigh·-eye·2m   | offer·50·on
D10  | train seat                 | a striped long-sleeve top              | thigh·eye·1m    | show·50·on
D11  | car                        | a deep green column dress              | elbow·-eye·1m   | self_touch·15·on
D12  | car                        | an olive crewneck sweatshirt           | hands·eye·1m    | settle·15·on
D16  | hallway                    | a denim shirt                          | thigh·eye·2m    | count·35·pre
D18  | bathroom                   | a striped long-sleeve top              | hands·+eye·2m   | stop·50·pre
D19  | train seat                 | a beige knit polo                      | knee·+eye·1m    | question·15·on
D21  | laundry room               | a striped long-sleeve top              | knee·-eye·2m    | self_point·15·pre
D22  | laundry room               | a beige knit polo                      | elbow·+eye·1m   | offer·15·pre
D23  | hallway                    | a beige knit polo                      | knee·eye·1.5m   | show·50·post
D31  | cafe booth                 | a striped long-sleeve top              | elbow·eye·1m    | self_touch·15·on
D42  | kitchen                    | a denim shirt                          | thigh·+eye·1.5m | settle·15·on
D45  | park path                  | a striped long-sleeve top              | hands·eye·1.5m  | count·50·on
D46  | living room                | a denim shirt                          | knee·+eye·2m    | stop·50·pre
D50  | bedroom                    | a striped long-sleeve top              | knee·eye·1m     | question·15·on
D51  | cafe booth                 | a striped long-sleeve top              | hands·-eye·2m   | self_point·15·post
D52  | train seat                 | a deep green column dress              | knee·eye·2m     | offer·35·on
D53  | studio                     | a striped long-sleeve top              | thigh·-eye·1m   | show·15·on


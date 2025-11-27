# TODO: Add Broth Option to Bakso Mekar Pedas and Sosis Mekar Pedas

## Steps
- [ ] Update renderProducts: Add method select for id 3 and 4. Add kuah select (hidden by default). Add event listener to show kuah only if Direbus selected.
- [ ] Update addToCart: Validate method for id 3 and 4. If Direbus, validate kuah. Store in choices. If kuah "ya", price += 1000.
- [ ] Update renderCart: Display choices for id 2,3,4 as "Metode: ..., Kuah: ..."
- [ ] Update checkout/printNota: Include choices in messages and notes.
- [ ] Test: Add items with options, verify prices, cart display, checkout, and nota.

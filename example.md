---
# General options
lang: english # english or ngerman
letteroption: DINmtext # DINmtext (more compact) or DIN, folding differs!
date: '\today'

# From/To Information
author: Max Sender
company: Supercompany
mail: mas@maxsender.org
phone: +49 192 91925719
taxid: 62 212 897 090
IBAN: DE18 9289 0020 9201 2719 92
Bank: Legit Bank AG

from:
- Example Street 57
- 11225 Town

to:
- Antonia Peterson
- Am Waldrand 4
- 10408 Wurzhausen

# Invoice
invoicenr: 2021-01
currency: EUR
commasep: true # comment out line for dot separators
VAT: 19
service:
- description: Lots of stuff
  price: 120.00
  details:
    - 12 hours of work
    - very exhausting
- description: friend bonus
  price: -10.00

preinvoice: |
  This text will be displaye befor the invoice.

postinvoice: |
  This text will be displayed after the invoice.

# Letter
subject: Invoice
opening: Dear Mrs. Peterson,
closing: Cheers

enclosure:
- Contract
- Pictures of Cats

---
You can provide more text in the body of the document. This might be more
important for the letter case (where you can delete all the invocie stuff
from the markdown file).

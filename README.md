# Taxcalculate

Tax calculation to read and save a file from input and output for the tax calculation result. A Java with Ant GUI program with Netbeans IDE. My school project.

# Test cases

| Input Income | Condition being tested     | Expected output | Result      |
| ------------ | ----------------------     | --------------- | ------      |
| 37123        | In range $18,201 – $45,000 | $3027.68        | Success ✅ |
| -1050        | Negative income            | 0               | Success ✅ |
| 89241.43     | Non-integer income         | ERROR           | Success ✅ |
| %#¤%!        | Special characters         | ERROR           | Success ✅ |
| 0            | Lower than 18,200 dollars  | 0               | Success ✅ |
| abcdefg      | Non-numeric input          | ERROR           | Success ✅ |
| 45200        | In range $45,001 - $135,000 | $4348.00       | Success ✅ |
| 140000       | In range $135,001 - $190,000 | $33138.00     | Success ✅ |
| 250000       | In range $190,001 and over | $78638.00       | Success ✅ |
| 500,52       | Comma income               | ERROR           | Success ✅ |
| 50-50        | Fifty chance of dash       | ERROR           | Success ✅ |
|              | Empty income               | ERROR           | Success ✅ |
| (9000)       | Paranthesis income         | ERROR           | Success ✅ |
| 25000+50     | Range $18,201-$45,000 + add income | ERROR   | Success ✅ |
| 250 / 5      | Division of 250 by 5       | ERROR           | Success ✅ |

- Martin Eesmaa
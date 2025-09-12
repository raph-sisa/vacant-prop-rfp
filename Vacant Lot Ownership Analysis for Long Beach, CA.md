## Vacant Lot Ownership Analysis for Long Beach, CA

This analysis is based on the provided `vacantlots_602_with_zoneinfo.xlsx` dataset, which contains information for 602 vacant lots.

### Owner Type Distribution

The distribution of owner types for the vacant lots is as follows:

| Owner_Type             |   count |
|:-----------------------|--------:|
| Individual             |     242 |
| Corporate/Business     |     213 |
| Government             |     100 |
| Trust                  |      30 |
| Estate/Multiple Owners |      12 |
| Financial Institution  |       3 |
| Non-Profit/Religious   |       2 |

**Key Observations:**
*   **Individual owners** represent the largest single category, accounting for approximately 40% of the vacant lots. This suggests that a significant portion of the problematic lots are held by private citizens.
*   **Corporate/Business entities** are the second largest group, owning about 35% of the lots. This category could include developers, investment firms, or other businesses.
*   **Government-owned lots** make up a notable portion (around 16.6%), indicating that the city itself or other governmental bodies are significant landowners of vacant parcels.
*   **Trusts** are also a considerable owner type, often used for estate planning or asset management.

### Owner Location Distribution (for Long Beach Situs properties)

This distribution categorizes owners based on whether their mailing address is local to Long Beach, within California but outside Long Beach, or out-of-state, for properties whose situs city is Long Beach.

| Owner_Location          |   count |
|:------------------------|--------:|
| Not Long Beach Situs    |     384 |
| Local                   |     132 |
| Absentee (CA)           |      76 |
| Absentee (Out-of-State) |      10 |

**Key Observations:**
*   A large number of entries (`Not Long Beach Situs`) indicate that the situs city in the dataset is not Long Beach for these properties. This might be due to data entry or properties located just outside the city limits but included in the broader dataset. For the purpose of understanding Long Beach's problematic lots, we focus on those with a Long Beach situs.
*   Among the properties with a Long Beach situs, **Local owners** (mailing address in Long Beach, CA) account for 132 lots.
*   **Absentee owners within California** (mailing address in CA but outside Long Beach) own 76 lots.
*   **Absentee owners from out-of-state** own 10 lots.
*   The presence of a significant number of **absentee owners (both in-state and out-of-state)**, totaling 86 lots, aligns with the RFP's mention of 

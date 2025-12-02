# L0B RRSD

**Metadata**

| /science/LSAR/identification/absoluteOrbitNumber | Absolute orbit number |
| :---- | :---- |
| /science/LSAR/identification/missionId | Mission identifier |
| /science/LSAR/identification/processingCenter | Data processing center |
| /science/LSAR/identification/productType | Product type |
| /science/LSAR/identification/granuleId | Unique granule identification name |
| /science/LSAR/identification/productVersion | Product version which represents the structure of the product and the science content governed by the algorithm, input data, and processing parameters |
| /science/LSAR/identification/productSpecificationVersion | Product specification version which represents the schema of this product |
| /science/LSAR/identification/lookDirection | Look direction, either "Left" or "Right" |
| /science/LSAR/identification/orbitPassDirection | Orbit direction, either "Ascending" or "Descending" |
| /science/LSAR/identification/zeroDopplerStartTime | Azimuth start time (in UTC) of the product |
| /science/LSAR/identification/zeroDopplerEndTime | Azimuth stop time (in UTC) of the product |
| /science/LSAR/identification/listOfFrequencies | List of frequency layers available in the product |
| /science/LSAR/identification/productLevel | Product level. L0A: Unprocessed instrument data; L0B: Reformatted, unprocessed instrument data; L1: Processed instrument data in radar coordinates system; and L2: Processed instrument data in geocoded coordinates system |
| /science/LSAR/identification/boundingPolygon | OGR compatible WKT representation of bounding polygon of the image |
| /science/LSAR/identification/processingDateTime | Processing date and time (in UTC) |
| /science/LSAR/identification/radarBand | Acquired frequency band, either "L" or "S" |
| /science/LSAR/identification/platformName | Name of the platform used to collect the remote sensing data provided in this product |
| /science/LSAR/identification/instrumentName | Name of the instrument used to collect the remote sensing data provided in this product |
| /science/LSAR/identification/processingType | Nominal (or) Urgent (or) Custom (or) Undefined |
| /science/LSAR/identification/isMixedMode | "True" if this product is a composite of data collected in multiple radar modes, "False" otherwise |
| /science/LSAR/identification/isJointObservation | "True" if any portion of this product was acquired in a joint observation mode (e.g., L-band and S-band simultaneously), "False" otherwise |
| /science/LSAR/RRSD/swaths/frequencyA/listOfTxPolarizations | List of processed transmit polarizations |
| /science/LSAR/RRSD/swaths/frequencyA/txH/centerFrequency | Center frequency of the acquisition in Hertz |
| /science/LSAR/RRSD/swaths/frequencyA/txH/slantRangeSpacing | Slant range spacing of grid |
| /science/LSAR/RRSD/swaths/frequencyA/txH/listOfRxPolarizations | List of processed receive polarizations |
| /science/LSAR/RRSD/metadata/processingInformation/algorithms    /softwareVersion | Software version |
| /science/LSAR/RRSD/metadata/processingInformation/inputs    /l0aGranules | List of input L0A products used |

**Data dimensions**

| `/science/LSAR/RRSD/swaths/frequencyA/txH/slantRange` | `(frequencyASlantRangeWidth)` |
| :---- | :---- |
| `/science/LSAR/RRSD/swaths/frequencyA/txH/rxH/[HH/HV]` | `(alongTrackTimeLength,   frequencyASlantRangeWidth)` |
| `/science/LSAR/RRSD/swaths/frequencyA/txH/radarTime` | `(alongTrackTimeLength)` |
| `/science/LSAR/RRSD/swaths/frequencyA/txH/rangeLineIndex` | `(alongTrackTimeLength)` |
| `/science/LSAR/RRSD/swaths/frequencyA/txH/UTCtime` | `(alongTrackTimeLength)` |

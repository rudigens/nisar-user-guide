# L3 SME2

**Metadata**

| `/science/LSAR/identification/absoluteOrbitNumber` | `Absolute orbit number` |
| :---- | :---- |
| `/science/LSAR/identification/boundingPolygon` | `OGR compatible WKT representing the bounding polygon of the image` |
| `/science/LSAR/identification/frameNumber` | `Frame number` |
| `/science/LSAR/identification/granuleId` | `Unique granule identification name` |
| `/science/LSAR/identification/instrumentName` | `Name of the instrument used to collect the remote sensing data provided in this product` |
| `/science/LSAR/identification/isFullFrame` | `"True” if the product fully covers a NISAR frame, "False" if partial coverage` |
| `/science/LSAR/identification/isJointObservation` | `"True" if any portion of this product was acquired in a joint observation mode (e.g., L-band and S-band simultaneously), "False" otherwise` |
| `/science/LSAR/identification/isMixedMode` | `"True" if this product is a composite of data collected in multiple radar modes, "False" otherwise` |
| `/science/LSAR/identification/lookDirection` | `Look direction, either "Left" or "Right"` |
| `/science/LSAR/identification/missionId` | `Mission identifier` |
| `/science/LSAR/identification/orbitPassDirection` | `Orbit direction, either "Ascending" or "Descending"` |
| `/science/LSAR/identification/platformName` | `Name of the platform used to collect the remote sensing data provided in this product` |
| `/science/LSAR/identification/processingCenter` | `Data processing center` |
| `/science/LSAR/identification/processingDateTime` | `Processing UTC date and time` |
| `/science/LSAR/identification/processingType` | `Nominal (or) Urgent (or) Custom (or) Undefined` |
| `/science/LSAR/identification/productDoi` | `Digital Object Identifier (DOI) for the product` |
| `/science/LSAR/identification/productLevel` | `Product level` |
| `/science/LSAR/identification/productSpecificationVersion` | `Product specification version which represents the schema of this product` |
| `/science/LSAR/identification/productType` | `Product type` |
| `/science/LSAR/identification/productVersion` | `Product version which represents the structure of the product and the science content governed by the algorithm, input data, and processing parameters` |
| `/science/LSAR/identification/radarBand` | `Acquired frequency band, either "L" or "S"` |
| `/science/LSAR/identification/trackNumber` | `Track number` |
| `/science/LSAR/identification/zeroDopplerEndTime` | `Azimuth end time of the product` |
| `/science/LSAR/identification/zeroDopplerStartTime` | `Azimuth start time of the product` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG/projection` | `Product map grid projection: EPSG code` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /xCoordinateSpacing` | `X coordinates spacing` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /yCoordinateSpacing` | `Y coordinates spacing` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/projection` | `Product map grid projection: EPSG code` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /xCoordinateSpacing` | `X coordinates spacing` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /yCoordinateSpacing` | `Y coordinates spacing` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR/projection` | `Product map grid projection: EPSG code` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /xCoordinateSpacing` | `X coordinates spacing` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /yCoordinateSpacing` | `Y coordinates spacing` |
| `/science/LSAR/SME2/grids/ancillaryData/projection` | `Product map grid projection: EPSG code` |
| `/science/LSAR/SME2/grids/ancillaryData/xCoordinateSpacing` | `X coordinates spacing` |
| `/science/LSAR/SME2/grids/ancillaryData/yCoordinateSpacing` | `Y coordinates spacing` |
| `/science/LSAR/SME2/grids/projection` | `Product map grid projection: EPSG code` |
| `/science/LSAR/SME2/grids/xCoordinateSpacing` | `X coordinates spacing` |
| `/science/LSAR/SME2/grids/yCoordinateSpacing` | `Y coordinates spacing` |
| `/science/LSAR/SME2/metadata/processingInformation/algorithms    /softwareVersion` | `Software version` |
| `/science/LSAR/SME2/metadata/processingInformation/inputs    /l2GcovGranules` | `List of input L2 GCOV products used` |

**Data dimensions**

| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /algorithmParameterBeta` | `(productWidth, productLength)` |
| :---- | :---- |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /algorithmParameterGamma` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /retrievalQualityFlag` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG/soilMoisture` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG    /soilMoistureUncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG/xCoordinates` | `(productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/DSG/yCoordinates` | `(productWidth)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/cropType` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /dielectricConstant` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /retrievalQualityFlag` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/roughness` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/soilMoisture` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /soilMoistureUncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /vegetationWaterContentHV` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /vegetationWaterContentNDVI` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI    /vegetationWaterContentRetrieved` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/xCoordinates` | `(productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/PMI/yCoordinates` | `(productWidth)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /algorithmParameterAlpha1` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /algorithmParameterAlpha1Uncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /algorithmParameterAlpha2` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /algorithmParameterAlpha2Uncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /retrievalQualityFlag` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR/soilMoisture` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR    /soilMoistureUncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR/xCoordinates` | `(productLength)` |
| `/science/LSAR/SME2/grids/algorithmCandidates/TSR/yCoordinates` | `(productWidth)` |
| `/science/LSAR/SME2/grids/ancillaryData/landCover` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData/localIncidenceAngle` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData    /localIncidenceAngleUncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData/surfaceQualityFlag` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData/waterbodyFraction` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData/xCoordinates` | `(productLength)` |
| `/science/LSAR/SME2/grids/ancillaryData/yCoordinates` | `(productWidth)` |
| `/science/LSAR/SME2/grids/EASEGridColumnIndex` | `(productLength)` |
| `/science/LSAR/SME2/grids/EASEGridRowIndex` | `(productWidth)` |
| `/science/LSAR/SME2/grids/latitude` | `(productWidth)` |
| `/science/LSAR/SME2/grids/longitude` | `(productLength)` |
| `/science/LSAR/SME2/grids/retrievalQualityFlag` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/soilMoisture` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/soilMoistureUncertainty` | `(productWidth, productLength)` |
| `/science/LSAR/SME2/grids/xCoordinates` | `(productLength)` |
| `/science/LSAR/SME2/grids/yCoordinates` | `(productWidth)` |


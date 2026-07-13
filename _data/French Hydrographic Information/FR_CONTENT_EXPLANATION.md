---
permalink: /French Hydrogeographic Data/
title: "French Hydrogeographic Data"
---

# FR.txt File Contents

## Overview
The `FR.txt` file contains geographic and administrative data for locations in France, sourced from the **Geonames database**. It consists of **174,592 records** of geographic features and settlements.

## File Format
- **Format**: Tab-separated values (TSV)
- **Encoding**: UTF-8
- **Records**: 174,592 entries

## Data Fields

Each record contains the following tab-separated columns:

| Column | Name | Description |
|--------|------|-------------|
| 1 | Geonames ID | Unique identifier for the geographic location |
| 2 | Name | Primary name of the location (UTF-8 encoded) |
| 3 | ASCII Name | ASCII-encoded version of the location name |
| 4 | Alternative Names | Comma-separated list of alternate names and transliterations |
| 5 | Latitude | Geographic latitude coordinate (decimal degrees) |
| 6 | Longitude | Geographic longitude coordinate (decimal degrees) |
| 7 | Feature Class | General category of the feature (P, T, H, L, V, etc.) |
| 8 | Feature Code | Specific subcategory code (PPL, PASS, STM, MT, etc.) |
| 9 | Country Code | ISO 3166 country code (FR = France) |
| 10 | Alternate Country Codes | Secondary country codes if applicable |
| 11-14 | Admin Levels 1-4 | Administrative division codes (regions, departments, districts, etc.) |
| 15 | Population | Population count (0 if not applicable) |
| 16 | Elevation | Elevation in meters above sea level (blank if not applicable) |
| 17 | DEM | Digital Elevation Model value |
| 18 | Timezone | IANA timezone identifier (e.g., Europe/Paris) |
| 19 | Modification Date | Date the record was last updated (YYYY-MM-DD format) |

## Feature Classes

The Feature Class categorizes the type of geographic feature:

- **P** = City, village, or populated place
- **T** = Mountain, hill, terrain feature
- **H** = Stream, river, water feature
- **L** = Administrative region or boundary
- **V** = Forest, vegetation area

## Examples

The file includes diverse geographic features such as:
- **Mountain peaks**: Col de Recon, Les Cornettes de Bise, Le Cheval Blanc
- **Streams and rivers**: Allondon, Rosselle, Lertzbach, Zorn
- **Towns and villages**: Peyrat-le-Château, Blaye, Zuydcoote, Zutzendorf
- **Geographic regions**: Soule
- **Islands**: Île Boucheau
- **Forest areas**: Forêt Territoriale de Zonza

## Geographic Coverage

The data covers all regions of France including:
- Mainland France (metropolitan regions and administrative departments)
- Overseas territories (indicated by department codes like 2A, 2B for Corsica; 94 for overseas)
- Border regions adjacent to Switzerland, Germany, Luxembourg, and Spain

## Data Quality Notes

- Locations have multilingual alternative names and transliterations (French, German, Chinese, Arabic, Cyrillic, etc.)
- Elevation data is provided for terrain features (peaks, hills)
- Population data is available for populated places
- All records have a modification date indicating when the Geonames data was last updated

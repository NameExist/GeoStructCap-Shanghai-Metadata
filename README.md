# GeoStructCap-Shanghai-Metadata

This repository contains the metadata for the large-scale unlabeled imagery dataset used in **GeoStructCap**.

The dataset covers a research area in **Shanghai, China**. It consists of **9,546** image patches.

## Dataset Specifications

*   **Source:** Tianditu API
*   **Coverage:**
    *   Longitude: $121.398926^\circ\text{E}$ to $121.551358^\circ\text{E}$
    *   Latitude: $31.179971^\circ\text{N}$ to $31.280898^\circ\text{N}$
*   **Grid Size:** $111 \times 86$ cells

## File Description

The file `shanghai_dataset_metadata.csv` contains the necessary information to retrieve or locate each image patch.

| Column | Description |
| :--- | :--- |
| `id` | Unique identifier for the patch (0-9545). |
| `tile_x` | Web Mercator tile X coordinate. |
| `tile_y` | Web Mercator tile Y coordinate. |
| `zoom` | Zoom level. |
| `filename` | Filename for the image. |
| `lat_nw` | Latitude of the North-West corner of the patch. |
| `lon_nw` | Longitude of the North-West corner of the patch. |

## How to Access Imagery

Researchers can use the `tile_x`, `tile_y`, and `zoom` columns provided in the CSV to retrieve images via the **Tianditu API**.


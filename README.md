Pycortex viewer of voxelwise model performance for one participant from:

Gong, X., Huth, A.G., Deniz, F., Johnson, K., Gallant, J.L., Theunissen, F.E. (2023). Phonemic segmentation of narrative speech in human cerebral cortex. *Nature Communications*, 14, 4309. https://www.nature.com/articles/s41467-023-39872-w

Maps show FDR-corrected (q<0.05) R² (`hot`, 0–0.1), on four pages:

1. **Overview**: acoustic (baseline), phonemic, semantic, and a winner-take-all map.
2. **Acoustic**: spectrum, phoneme count, and a 2D map comparing them.
3. **Phonemic**: single phoneme, diphone, triphone (unique variance), and a winner-take-all map.
4. **Semantic**: phonemic, semantic, and the 2D comparison (paper Fig. 7).

Click a voxel to see that page's R² values as a bar chart. As in the paper, acoustic maps use the full-model significance mask, so some masked voxels have R² ≤ 0 (black on the map, "≤ 0" in the popup). Semantic is the variance-partitioned semantic component.

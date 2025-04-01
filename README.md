# Minimum-Excess-Work Guidance

This repository contains additional results for the work *Minimum-Excess-Work (MEW) Guidance*.

## Path Guidance

In the folder `path guidance`, you can find supplementary results comparing guidance with and without MEW regularization.

#### `Path Guidance/toy example-MEW effect.png`  
This plot compares both path guidance and loss guidance with and without MEW regularization. It clearly shows that regularization is essential to prevent the collapse of sampled points.

#### `Path Guidance/Path guidance Chingolin.png`  
This plot compares path guidance with and without MEW regularization on the Chingolin data. While slightly higher guidance success can be achieved without MEW, the results demonstrate that MEW regularization is crucial to maintain both sample quality—measured via the Wasserstein Distance—and adherence to guiding points—measured via Maximum Mean Discrepancy (MMD).

## Observable Guidance

#### `Obersvable Guidance/Effect of MEW-regularisation.png`  

#### `Obersvable Guidance/kl-divergence and MEW regularisation.png`  

# sClass-PVDB: Synthetic Database for Palm Vein Images Classification 

This repository shares the database proposed in the paper: 

### “Palm Vein Image Classification for Large-Scale Biometric Recognition based on Convolutional Neural Networks” (submitted for review)
Mario González-Galdames, Marco Mora, Edwin Salazar-Jurado, Ruber Hernández-García, Ricardo Barrientos
Laboratory of Technological Research in Pattern Recognition (www.litrp.cl), Facultad de Ciencias de la Ingeniería, Universidad Católica del Maule, Chile

**Note:** The final database will be publicly shared upon completion of the review process.


## Directory Structure

```
sClass-PVDB/
├── dataset/              # Database files
│   ├── train/            # Train images
│   └── validation/       # Validation images
│   └── test/             # Test images
└── results/              # Experimental baseline results
```

## Dataset Description

We employed the method of generating synthetic images of palm veins proposed by Salazar et al. (2024) to create a database that reproduces the topological classes of the arterial network. The generated database comprises 80,000 images from 10,000 different subjects, with 8 images per subject, labeled with the arterial topological class. The class of each generated image was defined following a random pattern that simulates the real distribution of each class: 14.8% for class I, 8.37% for class II, 7.07% for class III, 50.58% for class IV, and 19.17% for class V. Therefore, we obtained a synthetic dataset representative of the real population.

## Citation

If you use our database for your research, please cite our paper:

Paper introducing the mathematical model for generating synthetic palm vein images: _Salazar-Jurado, E.H., Vilches-Ponce, K., Hernández-García, R. et al. Palm vein modeling for generating synthetic images with biometric purposes: a geometrical approach. Comp. Appl. Math. 43, 108 (2024)._ [https://doi.org/10.1007/s40314-024-02634-5](https://doi.org/10.1007/s40314-024-02634-5)
```
@article{salazar2024palm,
  title={Palm vein modeling for generating synthetic images with biometric purposes: a geometrical approach},
  author={Salazar-Jurado, Edwin H and Vilches-Ponce, Karina and Hern{\'a}ndez-Garc{\'\i}a, Ruber and Barrientos, Ricardo J},
  journal={Computational and Applied Mathematics},
  volume={43},
  number={3},
  pages={108},
  year={2024},
  publisher={Springer}
}
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 

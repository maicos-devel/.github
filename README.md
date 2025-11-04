# MAICoS Development Team

<p align="center">
  <img src="https://raw.githubusercontent.com/maicos-devel/maicos/refs/heads/main/docs/static/logo.svg" width="300" alt="MAICoS logo">
</p>

<p align="center">
  <a href="https://discord.gg/mnrEQWVAed"><img src="https://img.shields.io/badge/Join-Discord-7289da?logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://x.com/maicos_analysis"><img src="https://img.shields.io/badge/Follow-@maicos_analysis-1DA1F2?logo=x&logoColor=white" alt="X (Twitter)"></a>
</p>

## About Us

The **MAICoS Development Team** creates and maintains open-source Python tools for **preparing and analyzing molecular dynamics simulations**, focusing on studies of interfacial and confined systems while also offering powerful tools for the calculation of spectra or scattering profiles. Our mission is to provide the scientific community with **accessible, powerful, and well-documented software packages** that enable researchers to extract meaningful insights from molecular simulations and allow to follow the [**F.A.I.R. priciples**](https://www.go-fair.org/fair-principles/).

We develop tools that work seamlessly with popular MD simulation packages (LAMMPS, GROMACS, CHARMM, NAMD) and are built on top of [MDAnalysis](https://www.mdanalysis.org), ensuring compatibility and ease of use for both beginners and experienced users.

## 📜 Our Philosophy

- **Open Science**: All our software is open source under the GNU General Public License v3.0
- **User-Focused**: We design for both Python beginners (CLI) and advanced users (Python API)
- **Well Documented**: Comprehensive documentation with tutorials and examples
- **Community-Driven**: We value contributions and feedback from our users

## 📦 Our Packages

We currently develop and maintain the following Python packages for molecular dynamics analysis:

### [MAICoS](https://github.com/maicos-devel/maicos) - Molecular Analysis for Interfacial and Confined Systems
[![PyPI](https://img.shields.io/pypi/v/maicos)](https://pypi.org/project/maicos/)
[![Conda](https://img.shields.io/conda/vn/conda-forge/maicos)](https://anaconda.org/conda-forge/maicos)

Our flagship package for analyzing the structure and dynamics of interfacial and confined fluids. MAICoS provides a comprehensive toolkit for extracting density profiles, dielectric constants, structure factors, and transport properties from molecular simulations.

**Key analysis modules:**
- Density profiles (planar, cylindrical, spherical)
- Dielectric properties
- Dipolar order parameters
- Velocity and temperature profiles
- Pair distribution functions (PDF)
- Radial distribution functions (RDF)
- Kinetic energy analysis

**Installation:**
```bash
pip install maicos
# or
conda install -c conda-forge maicos
```

**Documentation:** [maicos-analysis.org](https://maicos-analysis.org)

### [Solvate](https://github.com/maicos-devel/solvate)

A tool for solvating confined geometries in molecular dynamics simulations. Solvate makes it easy to prepare systems with complex geometries for MD simulations.

*Currently in development*

### [ScatterKit](https://github.com/maicos-devel/scatterkit)

SAXS (Small-Angle X-ray Scattering) and other scattering analysis tools specifically designed for molecular dynamics simulations. ScatterKit helps researchers compute structure factors and scattering intensities from MD trajectories.

*Currently in development*

### [SpectraKit](https://github.com/maicos-devel/spectrakit)

Spectral analysis tools for molecular dynamics simulations, enabling frequency-domain analysis of various properties.

*Currently in development*

### [MAICoSData](https://github.com/maicos-devel/maicosdata)

A data repository containing example datasets, test files, and tutorials for use with MAICoS and related packages.


## 🤝 Join Our Community

We welcome users, contributors, and collaborators from around the world!

- **Ask Questions & Discuss**: Join our [Discord Server](https://discord.gg/mnrEQWVAed)
- **Stay Updated**: Follow us on [X (Twitter)](https://x.com/maicos_analysis)

## 🌟 Contributing

We welcome contributions from the community! Whether you're interested in:
- Reporting bugs or requesting features
- Contributing code or documentation
- Sharing your use cases and examples
- Helping other users

## 📜 License

All our software is open source and released under the [GNU General Public License v3.0](https://github.com/maicos-devel/maicos/blob/main/LICENSE).

## 🙏 Acknowledgments

Our work is powered by [MDAnalysis](https://www.mdanalysis.org) and made possible by the contributions of our amazing community.

### Our Contributors

<p align="center">
  <a href="https://github.com/maicos-devel/maicos/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=maicos-devel/maicos" alt="MAICoS Contributors" />
  </a>
</p>

---

<p align="center">
  <sub>This repository contains organization-wide GitHub configuration and resources for the MAICoS Development Team.</sub>
</p>
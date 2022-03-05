---
title: "Exponential Thermal Tensor Network Approach for Quantum Lattice Models"
date: 2018-09-01
publishDate: 2020-02-16T22:57:34.822218Z
authors: ["Bin-Bin Chen", "Lei Chen", "Ziyu Chen", "Wei Li", "Andreas Weichselbaum"]
publication_types: ["2"]
abstract: ""
featured: true
publication: "*Phys. Rev. X*"
doi: "10.1103/PhysRevX.8.031082"

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  focal_point: "center"
  preview_only: false
---

We speed up thermal simulations of quantum many-body systems in both one- (1D) and two-dimensional (2D) models in an exponential way by iteratively projecting the thermal density matrix $\rho=e^{-\beta H}$ onto itself. We refer to this scheme of doubling $\beta$ in each step of the imaginary time evolution as the exponential tensor renormalization group (XTRG). This approach is in stark contrast to conventional Trotter-Suzuki-type methods which evolve $\rho$ on a linear quasicontinuous grid in inverse temperature $\beta\equiv1/T$. As an aside, the large steps in XTRG allow one to swiftly jump across finite-temperature phase transitions, i.e., without the need to resolve each singularly expensive phase-transition point right away, e.g., when interested in low-energy behavior. A fine temperature resolution can be obtained, nevertheless, by using interleaved temperature grids. In general, XTRG can reach low temperatures exponentially fast and, thus, not only saves computational time but also merits better accuracy due to significantly fewer truncation steps. For similar reasons, we also find that the series expansion thermal tensor network approach benefits in both efficiency and precision, from the logarithmic temperature scale setup. We work in an (effective) 1D setting exploiting matrix product operators (MPOs), which allows us to fully and uniquely implement non-Abelian and Abelian symmetries to greatly enhance numerical performance. We use our XTRG machinery to explore the thermal properties of Heisenberg models on 1D chains and 2D square and triangular lattices down to low temperatures approaching ground-state properties. The entanglement properties, as well as the renormalization-group flow of entanglement spectra in MPOs, are discussed, where logarithmic entropies (approximately $\ln{\\beta}$) are shown in both spin chains and square-lattice models with gapless towers of states. We also reveal that XTRG can be employed to accurately simulate the Heisenberg XXZ model on the square lattice which undergoes a thermal phase transition. We determine its critical temperature based on thermal physical observables, as well as entanglement measures. Overall, we demonstrate that XTRG provides an elegant, versatile, and highly competitive approach to explore thermal properties, including finite-temperature thermal phase transitions as well as the different ordering tendencies at various temperature scales for frustrated systems.

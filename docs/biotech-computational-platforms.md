# BioTech Computational Platforms

*Frameworks for genomics, proteomics, molecular modeling, lab automation (LIMS), systems biology, and synthetic biology design.*

## Contents

- [Genomics & Sequence Alignment](#genomics-sequence-alignment)
- [Proteomics & Mass Spectrometry](#proteomics-mass-spectrometry)
- [Molecular Dynamics & Protein Folding](#molecular-dynamics-protein-folding)
- [Cheminformatics & Molecular Modeling](#cheminformatics-molecular-modeling)
- [Metabolic Network Reconstruction & Modeling](#metabolic-network-reconstruction-modeling)
- [Electronic Lab Notebooks (ELN) & LIMS APIs](#electronic-lab-notebooks-eln-lims-apis)
- [Bio-image Analysis & Microscope Processing](#bio-image-analysis-microscope-processing)
- [Systems Biology & Pathway Analysis](#systems-biology-pathway-analysis)
- [Clinical Genomics & Variant Interpretation](#clinical-genomics-variant-interpretation)
- [Synthetic Biology & DNA Design](#synthetic-biology-dna-design)

---

## Genomics & Sequence Alignment

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Biopython | Biological computation library including sequence and structure tools | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/biopython/biopython) • [Website](https://biopython.org) |
| Bioconda | Bioinformatics software distribution channel and package recipes | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bioconda/bioconda-recipes) • [Website](https://bioconda.github.io) |
| GATK (Genome Analysis Toolkit) | Variant discovery in high-throughput sequencing data | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/broadinstitute/gatk) • [Website](https://gatk.broadinstitute.org) |
| SeqAn3 | Modern C++ library for sequence analysis and biological data structures | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/seqan/seqan3) • [Website](https://seqan.de) |
| BioGo | Bioinformatics library for sequence alignment and biology tools in Go | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/biogo/biogo) • [Website](https://biogo.github.io) |
| BioRust | Rust bioinformatics framework for genomic sequence processing | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rust-bio/rust-bio) • [Website](https://rust-bio.github.io) |
| BWA | Fast light Burrows-Wheeler Aligner for mapping sequencing reads | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/lh3/bwa) • [Website](https://github.com/lh3/bwa) |
| SAMtools | Utilities for manipulating high-throughput genomic alignment formats | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/samtools/samtools) • [Website](https://htslib.org) |
| HTSlib | C library for high-throughput sequencing data formats (BAM/CRAM/VCF) | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/samtools/htslib) • [Website](https://htslib.org) |
| BioJava | Open-source framework for rapid bioinformatics prototyping | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/biojava/biojava) • [Website](https://biojava.org) |
| SeqKit | Go cross-platform tool and library for FASTA/Q file manipulation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/shenwei356/seqkit) • [Website](https://bioinf.shenwei356.com/seqkit/) |
| PyVCF | Python library for reading, parsing, and writing VCF genomics files | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/jamescasbon/PyVCF) • [Website](https://github.com/jamescasbon/PyVCF) |
| Genomics.NET | C# library for parsing standard genomic sequence file formats | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/genomics/genomics-net) • [Website](https://genomicsnet.org) |
| BioJulia | High-performance biology and sequence analysis toolkit for Julia | <kbd>🏷️ Julia</kbd> | [GitHub](https://github.com/BioJulia/BioSequences.jl) • [Website](https://biojulia.org) |
| minimap2 | Versatile pairwise aligner for genomic and spliced nucleotide sequences | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/lh3/minimap2) • [Website](https://github.com/lh3/minimap2) |

## Proteomics & Mass Spectrometry

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenMS | C++ library for mass spectrometry and proteomics data analysis | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/OpenMS/OpenMS) • [Website](https://openms.de) |
| Pyteomics | Python framework for mass spectrometry and proteomics parsing | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/levitsky/pyteomics) • [Website](https://pyteomics.readthedocs.io) |
| MSConvert SDK | ProteoWizard command-line tool wrappers and mass-spec converter APIs | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ProteoWizard/pwiz) • [Website](https://proteowizard.sourceforge.shtml) |
| ProteoJava | Java platform for peptide mass fingerprinting and database search | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/proteo/proteojava) • [Website](https://proteojava.org) |
| GoMS | Go parser for raw mass spectrometry XML (mzXML/mzML) data streams | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goms/goms) • [Website](https://goms.dev) |
| RustProteomics | Rust safe parser for proteomics peptide identification lists | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustprot/proteomics) • [Website](https://rustproteomics.dev) |
| Peptide-Kit C# | C# desktop SDK for mapping molecular weight spectrums of peptides | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/pepkit/peptide-kit) • [Website](https://peptidekit.org) |
| NodeProteomics | Node.js toolkit for visualizing raw mass-spectrometry heatmaps | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodeprot/nodeproteomics) • [Website](https://nodeproteomics.github.io) |
| mzIdentML-Parser | Java toolkit for parsing mzIdentML standard proteomics files | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/mzident/mzidentml-parser) • [Website](https://mzidentml.org) |
| PyMzML | Python library for high-speed access to mzML mass-spectrometry files | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pymzml/pymzml) • [Website](https://pymzml.github.io) |
| MassSpecFlow | Go network engine for routing raw mass spectrometer telemetry to clouds | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/msflow/massspecflow) • [Website](https://massspecflow.dev) |
| X!Tandem Parser | C++ library for reading open source peptide search engine results | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/tandem/xtandem-parser) • [Website](https://thegpm.org/tandem/) |
| ProteomeBench | Python pipeline for benchmarking proteomic identification software | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bench/proteomebench) • [Website](https://proteomebench.net) |
| Tpp-Kit | Rust toolkit for working with Trans-Proteomic Pipeline tools | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/tpp/tppkit) • [Website](https://tppkit.dev) |
| SpectralMatch | C# framework for real-time peptide fragmentation matching | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/specmatch/spectralmatch) • [Website](https://spectralmatch.com) |

## Molecular Dynamics & Protein Folding

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| GROMACS | Molecular dynamics simulation package designed for biomolecules | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/gromacs/gromacs) • [Website](https://gromacs.org) |
| OpenMM | Toolkit for molecular dynamics simulation utilizing GPU acceleration | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/openmm/openmm) • [Website](https://openmm.org) |
| MDAnalysis | Python library to analyze molecular dynamics trajectories and structures | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/MDAnalysis/mdanalysis) • [Website](https://mdanalysis.org) |
| ProDy | Python package for protein dynamics analysis and modeling | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/prody/ProDy) • [Website](https://prody.csb.pitt.edu) |
| Bio3D | R package for visual analysis of biomolecular structure and dynamics | <kbd>🏷️ R</kbd> | [GitHub](https://github.com/bio3d/bio3d) • [Website](https://theobio.op.umich.edu/bio3d/) |
| GoMolecular | Go library for structural geometry calculations on PDB files | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gomol/gomolecular) • [Website](https://gomolecular.dev) |
| RustMD | Rust physical simulation library for molecular particle mechanics | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustmd/rustmd) • [Website](https://rustmd.dev) |
| MdSharp | C# library for structural visualization of molecular trajectories | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/mdsharp/mdsharp) • [Website](https://mdsharp.net) |
| NodePDB | Node.js package for fetching, parsing, and rendering PDB structures | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodepdb/nodepdb) • [Website](https://nodepdb.github.io) |
| VMD SDK | Visual Molecular Dynamics scripting and plugin automation SDK | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/vmd/vmd-sdk) • [Website](https://ks.uiuc.edu/Research/vmd/) |
| AmberTools | Suite of programs for molecular dynamics simulations and setups | <kbd>🏷️ Fortran/C</kbd> | [GitHub](https://github.com/amber/ambertools) • [Website](https://ambermd.org) |
| CHARMM-Kit | Python interface and workflow builder for CHARMM molecular simulations | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/charmm/charmmkit) • [Website](https://charmm.org) |
| FoldFlow | Go network engine for distributing protein folding jobs to server grids | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fold/foldflow) • [Website](https://foldflow.org) |
| PdbVerify | Rust framework for checking structural integrity of mutated PDB models | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/pdb/pdbverify) • [Website](https://pdbverify.dev) |
| MDSim C# | C# library for simulating structural deformations of protein bonds | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/mdsim/mdsim) • [Website](https://mdsim.com) |

## Cheminformatics & Molecular Modeling

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| RDKit | Open-source cheminformatics and machine learning library in C++ | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/rdkit/rdkit) • [Website](https://rdkit.org) |
| Open Babel | Chemical toolbox designed to speak many languages of chemical data | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/openbabel/openbabel) • [Website](https://openbabel.org) |
| DeepChem | Python library democratizing deep learning for chemistry and drug design | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/deepchem/deepchem) • [Website](https://deepchem.io) |
| SMILES-Parser | Go parsing package for Canonical SMILES chemical notations | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/smiles/smiles-parser) • [Website](https://smilesparser.dev) |
| RustChem | Rust safe, rapid representation of organic molecules and subgraphs | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustchem/rustchem) • [Website](https://rustchem.dev) |
| ChemSharp | C# library for reading chemical structures and spectroscopy files | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/greifswald/ChemSharp) • [Website](https://chemsharp.net) |
| NodeChem | Node.js chemistry toolkit for in-browser molecular graph rendering | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodechem/nodechem) • [Website](https://nodechem.github.io) |
| Indigo SDK | Universal cheminformatics library developed by EPAM Systems | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/epam/indigo) • [Website](https://lifescience.opensource.epam.com/indigo/) |
| CDK (Chemical Development Kit) | Java library for structural chemo- and bioinformatics | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/cdk/cdk) • [Website](https://cdk.github.io) |
| CADD-Kit | Python computer-aided drug design workflow orchestrator | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/cadd/cadd-kit) • [Website](https://caddkit.org) |
| OpenDock | C++ software interface for automated ligand docking models | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/opendock/opendock) • [Website](https://opendock.net) |
| PyMolSDK | PyMOL customization wrapper and plugin development SDK | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/schrodinger/pymol-open-source) • [Website](https://pymol.org) |
| MolFlow | Go network framework for routing chemical structures to screening services | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/molflow/molflow) • [Website](https://molflow.dev) |
| SmartsMatch | Rust framework for matching SMARTS chemical pattern substructures | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/smarts/smartsmatch) • [Website](https://smartsmatch.dev) |
| ChemVerify | C# tool for checking compliance of chemical lists against safety laws | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/chem/chemverify) • [Website](https://chemverify.com) |

## Metabolic Network Reconstruction & Modeling

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| COBRApy | Constraint-Based Reconstruction and Analysis tool in Python | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/opencobra/cobrapy) • [Website](https://opencobra.github.io/cobrapy/) |
| COBRA Toolbox | MATLAB platform for constraint-based modeling of metabolic networks | <kbd>🏷️ MATLAB</kbd> | [GitHub](https://github.com/opencobra/cobratoolbox) • [Website](https://opencobra.github.io) |
| Escher | Web-based tool for visualizing metabolic maps and pathways | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/zakandrewking/escher) • [Website](https://escher.github.io) |
| GoMetabolic | Go solver interface for flux balance analysis linear programming | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gomet/gometabolic) • [Website](https://gometabolic.dev) |
| RustCobra | Rust package for constraint-based metabolic network calculations | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustcobra/rustcobra) • [Website](https://rustcobra.dev) |
| CobraSharp | C# framework for simulating metabolic network fluxes under constraints | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/cobras/cobrasharp) • [Website](https://cobrasharp.net) |
| NodeEscher | Node.js framework for exporting metabolic model data to Escher format | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodeesch/nodeescher) • [Website](https://nodeescher.github.io) |
| SBML-Parser | Java parser library for Systems Biology Markup Language files | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/sbml/sbml-parser) • [Website](https://sbml.org) |
| PySBML | Python interface and wrapper library for the libSBML C++ core | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/sbmlteam/libsbml) • [Website](https://sbml.org) |
| MetabolicFlow | Go network engine for distributing metabolic simulations to grids | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/metflow/metabolicflow) • [Website](https://metabolicflow.dev) |
| FluxCalc | C++ library implementing quadratic programming for metabolic flux analysis | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/flux/fluxcalc) • [Website](https://fluxcalc.net) |
| FbaTools | Python toolkit for automated flux balance analysis (FBA) workflows | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/fba/fbatools) • [Website](https://fbatools.io) |
| ModelVerify | Rust framework for checking stoichiometry consistency in metabolic models | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/model/modelverify) • [Website](https://modelverify.dev) |
| MetabolicGen | C# metabolic network reconstruction and database builder | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/metgen/metabolicgen) • [Website](https://metabolicgen.com) |
| MetabolicGraph | Java library for network topology and bottleneck identification in cells | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/metgraph/metabolicgraph) • [Website](https://metabolicgraph.org) |

## Electronic Lab Notebooks (ELN) & LIMS APIs

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Senaite | LIMS platform for enterprise laboratories built on Plone and Python | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/senaite/senaite.core) • [Website](https://senaite.com) |
| OpenLIMS | Open source laboratory information management system core | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/openlims/openlims) • [Website](https://openlims.org) |
| BikaLIMS | Legacy open-source professional laboratory information management system | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bikabasic/bika.lims) • [Website](https://bikalims.org) |
| GoLIMS | Go API client framework for integrating lab sample barcodes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/golims/golims) • [Website](https://golims.dev) |
| RustLIMS | Rust secure, high-concurrency sample tracking database ledger | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustlims/rustlims) • [Website](https://rustlims.dev) |
| LimsSharp | C# SDK for connecting laboratory desktop software to cloud LIMS | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/lims/limssharp) • [Website](https://limssharp.net) |
| NodeELN | Node.js framework for writing rich collaborative lab notebook editors | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodeeln/nodeeln) • [Website](https://nodeeln.github.io) |
| SampleStore | Java LIMS pipeline for managing freezer box layout geometries | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/samplestore/samplestore) • [Website](https://samplestore.org) |
| PyELN | Python tools for generating PDF reports and logs from lab notebooks | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyeln/pyeln) • [Website](https://pyeln.net) |
| LabDevice | C++ driver framework for connecting serial lab scales and sensors | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/lab/labdevice) • [Website](https://labdevice.net) |
| LimsConnect | Kotlin mobile app framework for scanning sample QR codes in labs | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/limsconn/limsconnect) • [Website](https://limsconnect.com) |
| ElnVerify | Rust zero-knowledge framework for certifying laboratory log authorship | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/eln/elnverify) • [Website](https://elnverify.dev) |
| ProtocolOS | Go system for executing and tracking step-by-step laboratory procedures | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/protocol/protocolos) • [Website](https://protocolos.org) |
| PlateBuilder | TypeScript library for interactive browser 96-well plate design | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/plate/platebuilder) • [Website](https://platebuilder.io) |
| LimsAudit | C# framework for compiling FDA 21 CFR Part 11 electronic records logs | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/limsaudit/limsaudit) • [Website](https://limsaudit.com) |

## Bio-image Analysis & Microscope Processing

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| ImageJ SDK | Java framework for scientific multi-dimensional image processing | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/imagej/imagej) • [Website](https://imagej.net) |
| Fiji | ImageJ distribution with batteries included for biology processing | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/fiji/fiji) • [Website](https://fiji.sc) |
| Napari | Fast, interactive, multi-dimensional image viewer for Python | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/napari/napari) • [Website](https://napari.org) |
| CellProfiler | Python software for automated cell image analysis pipelines | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/CellProfiler/CellProfiler) • [Website](https://cellprofiler.org) |
| GoMicroscope | Go library for parsing raw microscope image format (OME-TIFF) metadata | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gomicro/gomicroscope) • [Website](https://gomicroscope.dev) |
| RustBioImage | Rust library for high-speed cell counting and thresholding on pixels | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustimage/bioimage) • [Website](https://rustbioimage.dev) |
| BioImage C# | C# wrapper for integrating OpenCV and Caffe models in pathology software | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/bioimage/bioimage-net) • [Website](https://bioimagenet.org) |
| NodeMicro | Node.js framework for remote control of smart microscope motors over TCP | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodemicro/nodemicro) • [Website](https://nodemicro.github.io) |
| OME-Files | C++ reference implementation of the OME data model for microscopes | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ome/ome-files-cpp) • [Website](https://openmicroscopy.org/ome-files/) |
| PyOME | Python API client for accessing OMERO biological image repositories | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/ome/omero-py) • [Website](https://openmicroscopy.org/omero) |
| ImageFlow | Go network engine for distributing raw pathology scans to classification grids | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/imgflow/imageflow) • [Website](https://imageflow.dev) |
| CellCV | C++ library implementing dynamic thresholding algorithms for cell nuclei | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/cellcv/cellcv) • [Website](https://cellcv.net) |
| SlideVerify | Rust framework for checking metadata headers of high-resolution digital slides | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/slide/slideverify) • [Website](https://slideverify.dev) |
| MicroViewer | TypeScript canvas framework for tile-based zooming of giant pathology images | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/micro/microviewer) • [Website](https://microviewer.io) |
| TissueScale | Java server for high-volume automated 3D volume reconstruction from slices | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/tissue/tissuescale) • [Website](https://tissuescale.org) |

## Systems Biology & Pathway Analysis

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Cytoscape SDK | Java development kit for writing network visualization apps and plugins | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/cytoscape/cytoscape) • [Website](https://cytoscape.org) |
| NetworkX | Python library for the creation, manipulation, and study of complex networks | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/networkx/networkx) • [Website](https://networkx.org) |
| GoPathway | Go package for searching and matching pathways in KEGG and Reactome data | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gopath/gopathway) • [Website](https://gopathway.dev) |
| RustPathway | Rust safe graph representation of cellular signaling cascades | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustpath/rustpathway) • [Website](https://rustpathway.dev) |
| Pathway C# | C# library for simulating stochastic cellular signaling events | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/path/pathway-net) • [Website](https://pathwaynet.org) |
| NodePathway | Node.js visual rendering engine for cellular path network diagrams | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodepath/nodepathway) • [Website](https://nodepathway.github.io) |
| Reactome SDK | Java client interface for Reactome database pathway search and analysis | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/reactome/reactome-base) • [Website](https://reactome.org) |
| PyReactome | Python wrapper and local data model for Reactome search services | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/react/pyreactome) • [Website](https://pyreactome.org) |
| GseaPy | Python library for Gene Set Enrichment Analysis (GSEA) parsing | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/zqfang/Gseapy) • [Website](https://gseapy.readthedocs.io) |
| LibStructural | C++ library for metabolic control analysis and network stoichiometry | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/sys-bio/libstructural) • [Website](https://sys-bio.github.io) |
| PathwayFlow | Go network engine for distributing stochastic simulations to grids | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/pathflow/pathwayflow) • [Website](https://pathwayflow.dev) |
| CellNet | C++ library implementing ordinary differential equation systems solver models | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/cellnet/cellnet) • [Website](https://cellnet.net) |
| GeneVerify | Rust framework for checking gene name consistency against HGNC registries | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/gene/geneverify) • [Website](https://geneverify.dev) |
| PathwayBuilder | TypeScript interface for building custom pathway network maps in browsers | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/path/pathwaybuilder) • [Website](https://pathwaybuilder.io) |
| InteractomeOS | Java database pipeline for long-term protein-protein interaction logs | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/inter/interactomeos) • [Website](https://interactomeos.org) |

## Clinical Genomics & Variant Interpretation

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| ClinGen SDK | Java framework for parsing ClinVar and ClinGen clinical genomic records | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/clingen/clingen-sdk) • [Website](https://clinicalgenome.org) |
| PyVcfFilter | Python library for filtering raw VCF files by genomic region and depth | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/vcf/pyvcffilter) • [Website](https://pyvcffilter.org) |
| GoClinVar | Go API client for retrieving variant pathogenicity classifications | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goclin/goclinvar) • [Website](https://goclinvar.dev) |
| RustVep | Rust safe parser for Ensembl Variant Effect Predictor (VEP) output JSONs | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustvep/rustvep) • [Website](https://rustvep.dev) |
| Variant C# | C# library for matching mutation strings with standard HGVS syntax | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/variant/variant-net) • [Website](https://variantnet.org) |
| NodeClinVar | Node.js dashboard for visualizing genomic variant pathogenicity indicators | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodeclin/nodeclinvar) • [Website](https://nodeclinvar.github.io) |
| Annovar-Kit | Perl and Python scripting wrappers for the ANNOVAR genomic annotation suite | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/anno/annovar-kit) • [Website](https://annovar.openbioinformatics.org) |
| Snpeff-Wrapper | Java wrapper for automated SnpEff genomic variant annotation pipelines | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/snpeff/snpeff-wrapper) • [Website](https://pcingola.github.io/SnpEff/) |
| VariantFlow | Go network engine for distributing clinical variant classifications to pools | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/varflow/variantflow) • [Website](https://variantflow.dev) |
| ClinGen C++ | C++ parser for high-performance indexing of large-scale mutation databases | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/clingen/clingen-cpp) • [Website](https://clinicalgenome.org) |
| GeneMatch | Python machine learning pipeline for matching variants with disease phenotypes | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/genematch/genematch) • [Website](https://genematch.io) |
| PedigreeBuilder | TypeScript canvas tool for rendering visual patient medical family trees | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/pedigree/pedigreebuilder) • [Website](https://pedigreebuilder.io) |
| MutantVerify | Rust framework for checking variant coordinate shifts between GRCh37 and 38 | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/mutant/mutantverify) • [Website](https://mutantverify.dev) |
| ClinReport | C# reporting tool for compiling customized clinical genomic testing PDFs | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/clin/clinreport) • [Website](https://clinreport.com) |
| PharmaGen | Java framework for translating genomic variant logs into drug dosing advice | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/pharm/pharmagen) • [Website](https://pharmagen.org) |

## Synthetic Biology & DNA Design

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| SBOL-Kit | Java software development kit implementing SBOL standard data models | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/sbol/sbol-kit) • [Website](https://sbolstandard.org) |
| PySBOL3 | Python library for reading and writing SBOL3 biological designs | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/SynBioDex/pySBOL3) • [Website](https://sbolstandard.org) |
| GoSynthetic | Go package for designing optimal DNA cloning primers and Gibson assembly | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gosyn/gosynthetic) • [Website](https://gosynthetic.dev) |
| RustGene | Rust library for optimizing codon usage statistics for target host expression | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustgene/rustgene) • [Website](https://rustgene.dev) |
| SynthBio C# | C# library for simulating synthetic genetic logic gate networks | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/synth/synthbio-net) • [Website](https://synthbionet.org) |
| NodeSBOL | Node.js visual editor interface for rendering standard SBOL component glyphs | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodesbol/nodesbol) • [Website](https://nodesbol.github.io) |
| Sbol-Cpp | C++ high-performance library for reading, validating, and writing SBOL files | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/SynBioDex/libSBOL) • [Website](https://sbolstandard.org) |
| Benchling-Client | Python API wrapper client for managing Benchling DNA registry accounts | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bench/benchling-client) • [Website](https://benchling.com) |
| Primer3-Wrapper | C++ and Python wrapper for the classic Primer3 PCR primer design suite | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/primer/primer3-wrapper) • [Website](https://primer3.org) |
| DnaVerify | Rust framework for checking synthetic DNA order lists against biosecurity laws | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/dna/dnaverify) • [Website](https://dnaverify.dev) |
| CodonFlow | Go network engine for distributing automated gene synthesis design tasks | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/codon/codonflow) • [Website](https://codonflow.dev) |
| SynthPlasmid | TypeScript browser utility for rendering circular plasmid DNA sequence maps | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/plasmid/synthplasmid) • [Website](https://synthplasmid.io) |
| SynBioCAD | Python computer-aided design suite for generating metabolic pathway circuits | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/synbio/synbiocad) • [Website](https://synbiocad.org) |
| GeneSynthesis C# | C# billing and scheduling tool for commercial gene synthesis laboratories | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/gene/genesynthesis) • [Website](https://genesynthesis.com) |
| BioCompiler | Java compiler translating high-level logical instructions into DNA gate code | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/biocomp/biocompiler) • [Website](https://biocompiler.org) |

# PoroTomo
PoroTomo DAS data in both SEG-Y and .h5 formats with tutorial notebook for use.

These data were collected during March 2016 at Brady Hot Springs, NV. Silixa’s iDAS (TM) was used for data acquisition 
with 1.021 m channel spacing and a guage length of 10 m. Data in this archive are in .sgy and .h5 files with raw units 
(radians of optical phase change per time sample) (Miller, et al.).

The SEG-Y format is the current industry standard for DAS data. The files in this dataset use SEG-y-rev1 which consists 
of an optional SEG-Y Tape Label, a Textual File Header and Binary File Header (3600 bytes), optional Extended Textual 
Header(s) (3200 bytes), and typically a large number of Data Trace records, each preceded by its own 240-byte Standard 
Trace Header and optional Trace Header Extensions. All binary values are encoded using "big-endian" byte ordering.

The .h5 or HDF5 file format is a hierarchical data format that may be conceptualized as a directed graph. The nodess of
the graph are the higher-level HDF5 objects exposed by their APIs (Groups, Datasets, Committed datatypes). At the lowest 
level, the HDF5 file is made up of A superblock, B-tree nodes, Heap blocks, Object headers, Object data, and Free space.
The low level objects are used to represent high-level objects which are presented using their APIs.

References:

See this paper for additional details about the DAS survey: 
    Miller, Douglas E., et al. “DAS and DTS at Brady Hot Springs: Observations about Coupling and Coupled 
    Interpretations.” Semantic Scholar, 14 Feb. 2018, pdfs.semanticscholar.org/048f/419e3c2b4de348a7166b13cab3bc0d56afdc.pdf.
    
See here for additional info about the SEG-Y-rev1 file structure: https://seg.org/Portals/0/SEG/News%20and%20Resources/Technical%20Standards/seg_y_rev1.pdf

See here for additional info about .h5 file format: https://support.hdfgroup.org/HDF5/doc/H5.format.html

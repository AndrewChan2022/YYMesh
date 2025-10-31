# YYMesh



YYMesh is a mesh lib for both surface mesh and volume mesh



- design objection
  - high performance
    - memory and cache friendly
    - parallel support
    - good strategy for zone split
  - robust for dirty data
    - non-manifold support
    - duplicate and degenerate
    - hole
    - self-intersect
  - support both manifold, non-manifold mesh
    - data structure for general mesh



- feature
  - polygon mesh process
    - clean and repair
      - duplicate face remove
      - duplicate point remove
      - closed point merge
      - degenerate face remove
      - unreference point remove
      - hole filling
      - repair non-manifold edge
      - repair non-manifold vertices
      - repair self intersect 
    - simplification and decimation
    - parameterizing
    - smoothing and fairing
    - deform
    - geometry computation
      - normal
      - curvature
      - curvature flow
      - orientation repair
      - quality measure
  - remeshing
    - 
  - surface polygon mesh generation:  YYMesh2
    - plane mesh
    - surface mesh
  - volume mesh generation:  YYMesh3
    - unstructured mesh
      - CDT
      - RDT
    - structured mesh
      - structured
      - multiblock structured



- data structures
  - node data: save geometry data
  - connectivity data: save topology data
  - link data:  adjacency relationship
    - edge based data
      - half edge
      - redial edge
    - cell based data
      - node cell relationship
      - cell cell relationship
    
## progress



## prerequisite


## build
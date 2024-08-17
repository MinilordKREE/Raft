# raft-kv

## Getting Started

### Build
    mkdir -p raft-kv/build
    cd raft-kv/build
    cmake .. -DCMAKE_BUILD_TYPE=Release
    make -j8
    
### Running a cluster

First install [goreman](https://github.com/mattn/goreman), which manages Procfile-based applications.

    goreman start
`Kokkos::CudaUVMSpace` is a [`MemorySpace` type](MemorySpaceConcept) representing unified virtual memory on a Cuda-capable GPU system.  Unified virtual memory is also accessible from most host execution spaces.  Except in rare instances, it should not be used directly, but instead should be used generically as an memory space.  For details, see [the documentation on the `MemorySpace` concept](MemorySpaceConcept).
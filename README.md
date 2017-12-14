# G4BlineVisualization: visualization of magnetic field lines in geant4

To use, add the following to your user code's main executable (for example):
```
#include "G4BlineTracer.hh"

int main (int argc, char** argv)
{
  // Setup
  // ...

  // Load magnetic field line tracer
  G4BlineTracer* blineTracer = new G4BlineTracer();

  // ...
  // session->SessionStart();
  // ...

  delete blineTracer;
}

```

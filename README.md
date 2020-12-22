# Sobel Filter

**Directory structure**
* **README.md** - introduce the project, algorithm, reference ....
* **code/**
  * original - original code from open source if there is 
  * final (use inline pragma) - include both host and kernel code ※Note: host code must do auto-check
* **code-opt/** - Note it may have multiple code directories for different code structure, named by code-opt  (opt refer to optimization method, e.g. code-OoO  Out-Of-Order)
  * ...
* **testdata/** - include input test data, and output result data
* **script/** - makefile
  * ... - Build process shall include a trial-run with result check. 
* **impl/** - result of the implementation, only the metafile, and report, e.g. vitis summary file, HLS csynth report

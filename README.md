# OMCompilerDoxygen
I haven't found a good description of the [OpenModelica Compiler](https://github.com/OpenModelica/OMCompiler/) source design, but the compiler is bootstrapped, able to self-compile from the originating Modelica sources.
While successful, this produces an excessive amount of #defined code and a sprawling project.
The best place to start is with the OpenModelica Compiler C API at [OMC.h](https://github.com/OpenModelica/OMCompiler/blob/master/SimulationRuntime/cpp/omcCAPI/include/OMC.h).

This Doxygen configuration builds documentation with include graphs, to give some sense of the class relationships.
OMCompiler is a large project and it takes ~12hr to generate the include graphs, doubtless the config could be improved.

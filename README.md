# OMCompilerDoxygen
Doxygen with include graphs for the [OpenModelica Compiler](https://github.com/OpenModelica/OMCompiler/).
OMCompiler built on linux x64 from a configuration similar to [OMCompilerDocker](https://github.com/bc0n/OMCompilerDocker); as configured, generating the documentation takes ~12hr.

Browse from [index.html](html/index.html).

# OMCompiler
I haven't found a good description to the OMCompiler source design, but the compiler is bootstrapped, able to self-compile from the originating Modelica sources.  While successful, this produces an excessive amount of #defined code.  The best place to start is with the OpenModelica Compiler C API at [OMC.h](html/d6/d75/_o_m_c_8h.html).

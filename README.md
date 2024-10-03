# Multi Stage Docker Build

The main purpose of choosing a golang based applciation is because golang is a statically-typed programming language that does not require a runtime.
Unlike dynamically-typed languages like Python, Ruby, and JavaScript, which rely on a runtime environment to execute their code, Go compiles directly to machine code, which can then be executed directly by the operating system.

 The real advantage of multi stage docker build and distro less images can be understood with a drastic reduction in the size of the image.

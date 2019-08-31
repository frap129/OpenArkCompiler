# OpenArkCompiler

## Overview
-----------------
> A unified programming platform for multiple devices and multi-language support.

OpenArkCompiler is an open source project from the Huawei Ark compiler.

### OpenArkCompiler Four technical features ###

Ability to compile different language code into a set of executable files for efficient execution in the runtime environment:
- Support multi-language joint optimization and eliminate cross-language call overhead;
- Lighter language runtime;
- Soft and hard coordination to give full play to hardware energy efficiency;
- Support for diverse terminal equipment platforms

## Open source plan
**Compiler framework code open source**
- Time: August 2019
- Open source scope: compiler IR + mid-range language implementation
- Open ability:
   - Framework open source for reference learning, understand the Ark compiler architecture and framework code
   - Developers can build a complete compiler toolchain that supports Java Sample program compilation (non-application)

**Follow-up open source scope**
Open source compiler front-end, back-end, compiler optimization; full support for Java program compilation, JavaScript language application compilation.

**Plan to keep updating...**

## Related documents

- Architecture design principle
   - [MAPLE IR Design](doc/MapleIRDesign.md)
   - [RC API](doc/RC_API.md)
   - [Naive RC Operational insertion principle](doc/Naive_RC_Insertion_Description.md)
   - [Virtual function table and interface function table design introduction](doc/Vtable_Itable_Description.md)
   - [Phase design introduction](doc/Compiler_Phase_Description.md)

- [Environment configuration](doc/Development_Preparation.md)

- [Developer guide](doc/Developer_Guide.md)

- [Programming specification](doc/Programming_Specifications.md)



## License
- [LICENSE](license/LICENSE)
- [Open source software notice](license/Third_Party_Open_Source_Software_Notice.md)


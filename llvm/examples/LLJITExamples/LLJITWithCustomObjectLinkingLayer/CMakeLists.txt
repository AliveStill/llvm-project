set(LLVM_LINK_COMPONENTS
  Core
  IRReader
  OrcJIT
  Support
  nativecodegen
  )

add_llvm_example(LLJITWithCustomObjectLinkingLayer
  LLJITWithCustomObjectLinkingLayer.cpp
  )

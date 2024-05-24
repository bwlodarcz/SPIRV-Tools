use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '8bb0b50320274e4d8e0b63d26eafe1871f5241c0',

  'effcee_revision': 'aea1f4d62ca9ee2f44b5393e98e175e200a22e8e',

  'googletest_revision': '9b4993ca7d1279dec5c5d41ba327cb11a77bdc00',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': 'a771d3fbe7c432dc4db68360c6c0004fdde5646b',
  'spirv_headers_revision': '49a1fceb9b1d087f3c25ad5ec077bb0e46231297',
}

deps = {
  'external/abseil_cpp':
      Var('github') + '/abseil/abseil-cpp.git@' + Var('abseil_revision'),

  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/protobuf':
      Var('github') + '/protocolbuffers/protobuf.git@' + Var('protobuf_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}


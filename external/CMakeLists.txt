add_subdirectory(SDL3)

SET(SPIRV_SKIP_EXECUTABLES ON)
SET(SPIRV_CROSS_SHARED ON)
SET(SPIRV_CROSS_STATIC OFF)
SET(SPIRV_CROSS_CLI OFF)
SET(SPIRV_CROSS_ENABLE_TESTS OFF)
SET(SDLSHADERCROSS_VENDORED ON)
SET(SDLSHADERCROSS_CLI OFF)
add_subdirectory(SDL_shadercross)


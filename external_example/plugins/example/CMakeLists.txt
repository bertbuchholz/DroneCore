set(class_name
    Example
    PARENT_SCOPE
)

set(source_files
    example.cpp
    example_impl.cpp
    PARENT_SCOPE
)

set(unittest_source_files
    example_impl_test.cpp
    PARENT_SCOPE
)

set(header_files
    example.h
    PARENT_SCOPE
)

set(impl_header_files
    example_impl.h
    PARENT_SCOPE
)

# To include an additional library, use:
# set(additional_libs "some_library" PARENT_SCOPE)

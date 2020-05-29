add_example(Connectatron
    Connectatron.cpp
)

find_package(blueprint-utilities REQUIRED)

target_link_libraries(Connectatron PRIVATE blueprint-utilities)

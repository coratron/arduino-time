# Set the component name
set(COMPONENT_NAME "arduino-time")

# Create the component library
idf_component_register(SRCS "Time.cpp"
                            "DateStrings.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES "arduino"
                      )


godot_module()

target_sources(${module_name}
  PRIVATE "register_types.cpp"
          "summator.cpp"
)

project(my_cemrgproject_easi)

mitk_create_plugin(
  EXPORT_DIRECTIVE EASI_EXPORT
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDS MitkQtWidgetsExt MyCemrgLib
)

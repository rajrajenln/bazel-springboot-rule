## load("//tools/springboot:springboot2.bzl", "springboot2")
load("//tools/springboot:springboot.bzl", "springboot")


java_library(
  name = "javax_annotation_javax_annotation_api",
  visibility = ["//visibility:public"],
  exports = ["@javax_annotation_javax_annotation_api//jar"],
)


java_library(
  name = "org_skyscreamer_jsonassert",
  visibility = ["//visibility:public"],
  exports = ["@org_skyscreamer_jsonassert//jar"],
  runtime_deps = [
      ":com_vaadin_external_google_android_json",
  ],
)


java_library(
  name = "org_hibernate_validator_hibernate_validator",
  visibility = ["//visibility:public"],
  exports = ["@org_hibernate_validator_hibernate_validator//jar"],
  runtime_deps = [
      ":com_fasterxml_classmate",
      ":javax_validation_validation_api",
      ":org_jboss_logging_jboss_logging",
  ],
)


java_library(
  name = "com_jayway_jsonpath_json_path",
  visibility = ["//visibility:public"],
  exports = ["@com_jayway_jsonpath_json_path//jar"],
  runtime_deps = [
      ":net_minidev_accessors_smart",
      ":net_minidev_json_smart",
      ":org_ow2_asm_asm",
      ":org_slf4j_slf4j_api",
  ],
)


java_library(
  name = "org_slf4j_jul_to_slf4j",
  visibility = ["//visibility:public"],
  exports = ["@org_slf4j_jul_to_slf4j//jar"],
  runtime_deps = [
      ":org_slf4j_slf4j_api",
  ],
)


java_library(
  name = "org_springframework_spring_expression",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_expression//jar"],
  runtime_deps = [
      ":org_springframework_spring_core",
  ],
)


java_library(
  name = "org_jboss_logging_jboss_logging",
  visibility = ["//visibility:public"],
  exports = ["@org_jboss_logging_jboss_logging//jar"],
)


java_library(
  name = "org_ow2_asm_asm",
  visibility = ["//visibility:public"],
  exports = ["@org_ow2_asm_asm//jar"],
)


java_library(
  name = "org_assertj_assertj_core",
  visibility = ["//visibility:public"],
  exports = ["@org_assertj_assertj_core//jar"],
)



java_library(
  name = "com_fasterxml_jackson_datatype_jackson_datatype_jdk8",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_datatype_jackson_datatype_jdk8//jar"],
  runtime_deps = [
      ":com_fasterxml_jackson_core_jackson_core",
      ":com_fasterxml_jackson_core_jackson_databind",
  ],
)


java_library(
  name = "com_fasterxml_jackson_datatype_jackson_datatype_jsr310",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_datatype_jackson_datatype_jsr310//jar"],
  runtime_deps = [
      ":com_fasterxml_jackson_core_jackson_annotations",
      ":com_fasterxml_jackson_core_jackson_core",
      ":com_fasterxml_jackson_core_jackson_databind",
  ],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_test",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_test//jar"],
  runtime_deps = [
      ":com_jayway_jsonpath_json_path",
      ":com_vaadin_external_google_android_json",
      ":junit_junit",
      ":net_bytebuddy_byte_buddy",
      ":net_bytebuddy_byte_buddy_agent",
      ":net_minidev_accessors_smart",
      ":net_minidev_json_smart",
      ":org_assertj_assertj_core",
      ":org_hamcrest_hamcrest_core",
      ":org_hamcrest_hamcrest_library",
      ":org_mockito_mockito_core",
      ":org_objenesis_objenesis",
      ":org_ow2_asm_asm",
      ":org_skyscreamer_jsonassert",
      ":org_slf4j_slf4j_api",
      ":org_springframework_boot_spring_boot",
      ":org_springframework_boot_spring_boot_autoconfigure",
      ":org_springframework_boot_spring_boot_starter",
      ":org_springframework_boot_spring_boot_test",
      ":org_springframework_boot_spring_boot_test_autoconfigure",
      ":org_springframework_spring_core",
      ":org_springframework_spring_test",
      ":org_xmlunit_xmlunit_core",
  ],
)


java_library(
  name = "org_objenesis_objenesis",
  visibility = ["//visibility:public"],
  exports = ["@org_objenesis_objenesis//jar"],
)


java_library(
  name = "javax_validation_validation_api",
  visibility = ["//visibility:public"],
  exports = ["@javax_validation_validation_api//jar"],
)


java_library(
  name = "org_hamcrest_hamcrest_core",
  visibility = ["//visibility:public"],
  exports = ["@org_hamcrest_hamcrest_core//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter//jar"],
  runtime_deps = [
      ":ch_qos_logback_logback_classic",
      ":ch_qos_logback_logback_core",
      ":javax_annotation_javax_annotation_api",
      ":org_apache_logging_log4j_log4j_api",
      ":org_apache_logging_log4j_log4j_to_slf4j",
      ":org_slf4j_jul_to_slf4j",
      ":org_slf4j_slf4j_api",
      ":org_springframework_boot_spring_boot",
      ":org_springframework_boot_spring_boot_autoconfigure",
      ":org_springframework_boot_spring_boot_starter_logging",
      ":org_springframework_spring_aop",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_context",
      ":org_springframework_spring_core",
      ":org_springframework_spring_expression",
      ":org_springframework_spring_jcl",
      ":org_yaml_snakeyaml",
  ],
)


java_library(
  name = "com_vaadin_external_google_android_json",
  visibility = ["//visibility:public"],
  exports = ["@com_vaadin_external_google_android_json//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_test",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_test//jar"],
  runtime_deps = [
      ":org_springframework_boot_spring_boot",
  ],
)


java_library(
  name = "com_fasterxml_classmate",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_classmate//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_web",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_web//jar"],
  runtime_deps = [
      ":ch_qos_logback_logback_classic",
      ":ch_qos_logback_logback_core",
      ":com_fasterxml_classmate",
      ":com_fasterxml_jackson_core_jackson_annotations",
      ":com_fasterxml_jackson_core_jackson_core",
      ":com_fasterxml_jackson_core_jackson_databind",
      ":com_fasterxml_jackson_datatype_jackson_datatype_jdk8",
      ":com_fasterxml_jackson_datatype_jackson_datatype_jsr310",
      ":com_fasterxml_jackson_module_jackson_module_parameter_names",
      ":javax_annotation_javax_annotation_api",
      ":javax_validation_validation_api",
      ":org_apache_logging_log4j_log4j_api",
      ":org_apache_logging_log4j_log4j_to_slf4j",
      ":org_apache_tomcat_embed_tomcat_embed_core",
      ":org_apache_tomcat_embed_tomcat_embed_el",
      ":org_apache_tomcat_embed_tomcat_embed_websocket",
      ":org_hibernate_validator_hibernate_validator",
      ":org_jboss_logging_jboss_logging",
      ":org_slf4j_jul_to_slf4j",
      ":org_slf4j_slf4j_api",
      ":org_springframework_boot_spring_boot",
      ":org_springframework_boot_spring_boot_autoconfigure",
      ":org_springframework_boot_spring_boot_starter",
      ":org_springframework_boot_spring_boot_starter_json",
      ":org_springframework_boot_spring_boot_starter_logging",
      ":org_springframework_boot_spring_boot_starter_tomcat",
      ":org_springframework_spring_aop",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_context",
      ":org_springframework_spring_core",
      ":org_springframework_spring_expression",
      ":org_springframework_spring_jcl",
      ":org_springframework_spring_web",
      ":org_springframework_spring_webmvc",
      ":org_yaml_snakeyaml",
  ],
)


java_library(
  name = "com_fasterxml_jackson_core_jackson_databind",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_core_jackson_databind//jar"],
  runtime_deps = [
      ":com_fasterxml_jackson_core_jackson_annotations",
      ":com_fasterxml_jackson_core_jackson_core",
  ],
)


java_library(
  name = "org_apache_tomcat_embed_tomcat_embed_websocket",
  visibility = ["//visibility:public"],
  exports = ["@org_apache_tomcat_embed_tomcat_embed_websocket//jar"],
  runtime_deps = [
      ":org_apache_tomcat_embed_tomcat_embed_core",
  ],
)


java_library(
  name = "org_springframework_spring_core",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_core//jar"],
  runtime_deps = [
      ":org_springframework_spring_jcl",
  ],
)


java_library(
  name = "com_fasterxml_jackson_core_jackson_core",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_core_jackson_core//jar"],
)


java_library(
  name = "ch_qos_logback_logback_classic",
  visibility = ["//visibility:public"],
  exports = ["@ch_qos_logback_logback_classic//jar"],
  runtime_deps = [
      ":ch_qos_logback_logback_core",
      ":org_slf4j_slf4j_api",
  ],
)


java_library(
  name = "org_apache_tomcat_embed_tomcat_embed_el",
  visibility = ["//visibility:public"],
  exports = ["@org_apache_tomcat_embed_tomcat_embed_el//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_parent",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_parent//jar"],
)


java_library(
  name = "net_bytebuddy_byte_buddy_agent",
  visibility = ["//visibility:public"],
  exports = ["@net_bytebuddy_byte_buddy_agent//jar"],
)


java_library(
  name = "org_springframework_spring_test",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_test//jar"],
  runtime_deps = [
      ":org_springframework_spring_core",
  ],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_json",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_json//jar"],
  runtime_deps = [
      ":com_fasterxml_jackson_core_jackson_annotations",
      ":com_fasterxml_jackson_core_jackson_core",
      ":com_fasterxml_jackson_core_jackson_databind",
      ":com_fasterxml_jackson_datatype_jackson_datatype_jdk8",
      ":com_fasterxml_jackson_datatype_jackson_datatype_jsr310",
      ":com_fasterxml_jackson_module_jackson_module_parameter_names",
      ":org_springframework_boot_spring_boot_starter",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_core",
      ":org_springframework_spring_web",
  ],
)


java_library(
  name = "org_springframework_spring_context",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_context//jar"],
  runtime_deps = [
      ":org_springframework_spring_aop",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_core",
      ":org_springframework_spring_expression",
  ],
)


java_library(
  name = "org_mockito_mockito_core",
  visibility = ["//visibility:public"],
  exports = ["@org_mockito_mockito_core//jar"],
  runtime_deps = [
      ":net_bytebuddy_byte_buddy",
      ":net_bytebuddy_byte_buddy_agent",
      ":org_objenesis_objenesis",
  ],
)


java_library(
  name = "org_springframework_gs_rest_service",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_gs_rest_service//jar"],
  runtime_deps = [
      ":org_springframework_boot_spring_boot_starter_web",
  ],
)


java_library(
  name = "org_springframework_spring_aop",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_aop//jar"],
  runtime_deps = [
      ":org_springframework_spring_beans",
      ":org_springframework_spring_core",
  ],
)


java_library(
  name = "org_apache_logging_log4j_log4j_to_slf4j",
  visibility = ["//visibility:public"],
  exports = ["@org_apache_logging_log4j_log4j_to_slf4j//jar"],
  runtime_deps = [
      ":org_apache_logging_log4j_log4j_api",
      ":org_slf4j_slf4j_api",
  ],
)


java_library(
  name = "org_springframework_boot_spring_boot_test_autoconfigure",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_test_autoconfigure//jar"],
  runtime_deps = [
      ":org_springframework_boot_spring_boot_autoconfigure",
      ":org_springframework_boot_spring_boot_test",
  ],
)


java_library(
  name = "org_xmlunit_xmlunit_core",
  visibility = ["//visibility:public"],
  exports = ["@org_xmlunit_xmlunit_core//jar"],
)


java_library(
  name = "org_apache_logging_log4j_log4j_api",
  visibility = ["//visibility:public"],
  exports = ["@org_apache_logging_log4j_log4j_api//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_logging",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_logging//jar"],
  runtime_deps = [
      ":ch_qos_logback_logback_classic",
      ":ch_qos_logback_logback_core",
      ":org_apache_logging_log4j_log4j_api",
      ":org_apache_logging_log4j_log4j_to_slf4j",
      ":org_slf4j_jul_to_slf4j",
      ":org_slf4j_slf4j_api",
  ],
)


java_library(
  name = "ch_qos_logback_logback_core",
  visibility = ["//visibility:public"],
  exports = ["@ch_qos_logback_logback_core//jar"],
)


java_library(
  name = "net_minidev_json_smart",
  visibility = ["//visibility:public"],
  exports = ["@net_minidev_json_smart//jar"],
  runtime_deps = [
      ":net_minidev_accessors_smart",
      ":org_ow2_asm_asm",
  ],
)


java_library(
  name = "net_bytebuddy_byte_buddy",
  visibility = ["//visibility:public"],
  exports = ["@net_bytebuddy_byte_buddy//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot//jar"],
  runtime_deps = [
      ":org_springframework_spring_aop",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_context",
      ":org_springframework_spring_core",
      ":org_springframework_spring_expression",
      ":org_springframework_spring_jcl",
  ],
)


java_library(
  name = "com_fasterxml_jackson_module_jackson_module_parameter_names",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_module_jackson_module_parameter_names//jar"],
  runtime_deps = [
      ":com_fasterxml_jackson_core_jackson_core",
      ":com_fasterxml_jackson_core_jackson_databind",
  ],
)


java_library(
  name = "org_hamcrest_hamcrest_library",
  visibility = ["//visibility:public"],
  exports = ["@org_hamcrest_hamcrest_library//jar"],
  runtime_deps = [
      ":org_hamcrest_hamcrest_core",
  ],
)


java_library(
  name = "org_springframework_boot_spring_boot_starter_tomcat",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_starter_tomcat//jar"],
  runtime_deps = [
      ":javax_annotation_javax_annotation_api",
      ":org_apache_tomcat_embed_tomcat_embed_core",
      ":org_apache_tomcat_embed_tomcat_embed_el",
      ":org_apache_tomcat_embed_tomcat_embed_websocket",
  ],
)


java_library(
  name = "junit_junit",
  visibility = ["//visibility:public"],
  exports = ["@junit_junit//jar"],
  runtime_deps = [
      ":org_hamcrest_hamcrest_core",
  ],
)


java_library(
  name = "net_minidev_accessors_smart",
  visibility = ["//visibility:public"],
  exports = ["@net_minidev_accessors_smart//jar"],
  runtime_deps = [
      ":org_ow2_asm_asm",
  ],
)


java_library(
  name = "org_slf4j_slf4j_api",
  visibility = ["//visibility:public"],
  exports = ["@org_slf4j_slf4j_api//jar"],
)


java_library(
  name = "org_apache_tomcat_embed_tomcat_embed_core",
  visibility = ["//visibility:public"],
  exports = ["@org_apache_tomcat_embed_tomcat_embed_core//jar"],
)


java_library(
  name = "org_springframework_boot_spring_boot_autoconfigure",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_boot_spring_boot_autoconfigure//jar"],
  runtime_deps = [
      ":org_springframework_boot_spring_boot",
  ],
)


java_library(
  name = "com_fasterxml_jackson_core_jackson_annotations",
  visibility = ["//visibility:public"],
  exports = ["@com_fasterxml_jackson_core_jackson_annotations//jar"],
)


java_library(
  name = "org_springframework_spring_web",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_web//jar"],
  runtime_deps = [
      ":org_springframework_spring_beans",
      ":org_springframework_spring_core",
  ],
)


java_library(
  name = "org_springframework_spring_jcl",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_jcl//jar"],
)


java_library(
  name = "org_springframework_spring_beans",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_beans//jar"],
  runtime_deps = [
      ":org_springframework_spring_core",
  ],
)


java_library(
  name = "org_springframework_spring_webmvc",
  visibility = ["//visibility:public"],
  exports = ["@org_springframework_spring_webmvc//jar"],
  runtime_deps = [
      ":org_springframework_spring_aop",
      ":org_springframework_spring_beans",
      ":org_springframework_spring_context",
      ":org_springframework_spring_core",
      ":org_springframework_spring_expression",
      ":org_springframework_spring_web",
  ],
)


java_library(
  name = "org_yaml_snakeyaml",
  visibility = ["//visibility:public"],
  exports = ["@org_yaml_snakeyaml//jar"],
)





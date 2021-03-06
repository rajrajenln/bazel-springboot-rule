
# Spring Boot Packager
# (implemented by Salesforce)

# Even though there are no build steps for this Bazel package (just static files here),
# we need this BUILD file here to make it an addressable Bazel package.

# Example (for BUILD files):
#   load("//tools/springboot:springboot.bzl", "springboot")

# See the springboot.bzl file for detailed usage instructions.

## exports_files(["springboot.bzl", "springboot_pkg.sh"])

# Load our Spring Boot Rule
# load("//tools/springboot:springboot2.bzl",
#        "generated_maven_jars",
#        "generated_java_libraries"
# )

# Load our Spring Boot Rule
load("//tools/springboot:springboot.bzl",
        "springboot",
        "add_boot_tomcat_starter",
        "add_boot_web_starter",
        "add_boot_actuator_starter"
)

## add_boot_jetty_starter

#
# Internal Application Dependencies (Bazel targets)
# For this example, assume that //gs-rest-service-app/lib/some-internal-lib is a dependency. This is a
# library that is built in this Bazel workspace. Add it to the app_deps list as shown below.
# It might have a transitive dependency (e.g. //gs-rest-service-app/lib/some-transitive-lib) but no worries,
# that will be brought into the deployable jar for you without having to list it explicitly.

# External Application Dependencies (aka Maven Jars, aka Nexus, aka Artifactory)
# The solution for external dependencies isn't as nice. You have to list each dep explicitly
# in the app_deps list, and make sure there is a corresponding entry in the WORKSPACE file.
# The springboot rule automatically adds standard Spring Boot compile time dependencies to
# the app_deps list, but the WORKSPACE file is maintained entirely by you. Look at the
# WORKSPACE.sample file provided in this Git repository for guidance.
# Note that transitive dependencies of each external dependency MUST be also explicitly listed
# both here in app_deps and in the WORKSPACE file.
##  "../../samples/lib/myhello.jar"
app_deps = [
 "@org_apache_logging_log4j_log4j_api//jar",
 "@commons_logging_commons_logging//jar",
 "@com_fasterxml_classmate//jar",
 "@org_hibernate_hibernate_validator//jar",
 "@com_fasterxml_jackson_datatype_jdk8//jar",
 "@com_fasterxml_jackson_datatype_jsr310//jar",
 "@com_fasterxml_jackson_module_param//jar",
 "@javax_annotation_api//jar",
 "@org_jboss_logging//jar",
 "@org_yaml_snakeyaml//jar"
]

# Convenience Methods for Adding Entire Starters
## add_boot_jetty_starter(app_deps)

add_boot_actuator_starter(app_deps)
add_boot_tomcat_starter(app_deps)
add_boot_web_starter(app_deps)


# Build the app
springboot(
    name = "samples",
    boot_app_class = "hello.Application",
    deps = app_deps
)

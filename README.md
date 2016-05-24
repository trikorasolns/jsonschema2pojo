# jsonschema2pojo
jsonschema2pojo extension

This extension replaces the default annotation schem used by the jsonschema2pojo plugin, which use the `@JsonInclude(JsonInclude.Include.NON_NULL)` annotation, by another that extends from the core Jackson2 replacing `@JsonInclude(JsonInclude.Include.NON_NULL)` by `@JsonInclude(JsonInclude.Include.ALWAYS)`.
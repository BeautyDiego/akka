# extractSettings

## Description

Extracts the @unidoc[RoutingSettings] from the @unidoc[RequestContext].

By default the settings of the `Http()` extension running the route will be returned.
It is possible to override the settings for specific sub-routes by using the @ref[withSettings](withSettings.md) directive.

## Example

@@snip [BasicDirectivesExamplesTest.java]($test$/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #extractRequestContext }
- moved all templates to the partials dir.
- added a `themekit_library_info_alter` for library adding, which also required `use Drupal\Component\Utility\NestedArray;` and `use Drupal\Core\Serialization\Yaml;` as well.
- webpack loads in the base scss file automatically to all scss files for use
- webpack has a script to generate the partials yml.
- webpack auto finds scss and js and compiles them for you.
- add npm packages, glob, write-yaml, lodash.merge, lodash.set
- admin templates moved to admin dir (note sure we need these anymore idk)
- all partials functionality has its library auto generated.

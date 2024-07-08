allow_equivalents: asserted-only
babelon_translation_group: null
catalog_file: catalog-v001.xml
ci:
- github_actions
components: null
contact: null
contributors: null
create_obo_metadata: true
creators: null
custom_makefile_header: '

  # ----------------------------------------

  # More information: https://github.com/INCATools/ontology-development-kit/

  '
description: None
documentation: null
dosdp_tools_options: --obo-prefixes=true
edit_format: owl
ensure_valid_rdfxml: true
exclude_tautologies: structural
export_formats:
- owl
- obo
export_project_yaml: false
extra_rdfxml_checks: false
git_main_branch: main
git_user: ''
github_org: Tree-of-Sex
gzip_main: false
id: toso
import_component_format: ofn
import_group:
  annotate_defined_by: false
  annotation_properties:
  - rdfs:label
  - IAO:0000115
  base_merge_drop_equivalent_class_axioms: false
  directory: imports/
  disabled: false
  exclude_iri_patterns: null
  export_obo: false
  ids:
  - po
  - ro
  - pato
  - bfo
  - oba
  - go
  mirror_max_time_download: 200
  mirror_retry_download: 4
  module_type: slme
  module_type_slme: BOT
  products:
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: po
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: null
    module_type_slme: BOT
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: ro
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: null
    module_type_slme: BOT
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: pato
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: null
    module_type_slme: BOT
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: bfo
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: null
    module_type_slme: BOT
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: oba
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: null
    module_type_slme: BOT
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  - annotation_properties:
    - rdfs:label
    - IAO:0000115
    base_iris: null
    description: null
    id: go
    is_large: false
    maintenance: manual
    make_base: false
    mirror_from: null
    mirror_type: null
    module_type: filter
    rebuild_if_source_changes: true
    robot_settings: null
    slme_individuals: include
    use_base: false
    use_gzipped: false
  rebuild_if_source_changes: true
  release_imports: false
  slme_individuals: include
  use_base_merging: false
import_pattern_ontology: false
license: https://creativecommons.org/licenses/unspecified
namespaces: null
obo_format_options: ''
owltools_memory: ''
pattern_pipelines_group: null
primary_release: full
public_release: none
public_release_assets: null
reasoner: ELK
release_annotate_inferred_axioms: false
release_artefacts:
- full
- base
release_date: false
release_diff: false
release_use_reasoner: true
remove_owl_nothing: false
repo: toso
robot_java_args: ''
robot_plugins: null
robot_report:
  custom_profile: false
  custom_sparql_checks:
  - owldef-self-reference
  - iri-range
  - label-with-iri
  - multiple-replaced_by
  - dc-properties
  custom_sparql_exports:
  - basic-report
  - class-count-by-prefix
  - edges
  - xrefs
  - obsoletes
  - synonyms
  ensure_owl2dl_profile: true
  fail_on: null
  release_reports: false
  report_on:
  - edit
  sparql_test_on:
  - edit
  use_base_iris: true
  use_labels: true
robot_settings: null
robot_version: null
run_as_root: false
sssom_mappingset_group: null
subset_group: null
title: Tree of Sex ontology
travis_emails: null
uribase: http://purl.obolibrary.org/obo
uribase_suffix: null
use_context: false
use_custom_import_module: false
use_dosdps: false
use_edit_file_imports: true
use_env_file_docker: false
use_external_date: false
use_mappings: false
use_templates: false
use_translations: false
workflows:
- docs
- qc
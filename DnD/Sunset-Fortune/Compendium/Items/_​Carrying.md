---
database-plugin: basic
icon: FasSuitcase
---

```yaml:dbfolder
name: SF-Carrying
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 2
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Qty:
    input: number
    accessorKey: Qty
    key: Qty
    id: Qty
    label: Qty
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 26
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Value_(each:
    input: number
    accessorKey: Value_(each
    key: Value_(each
    id: Value_(each
    label: Value (each)
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 38
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  type-s:
    input: select
    accessorKey: type
    key: type
    id: Type
    label: Type
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    nestedKey: s
    width: 121
    options:
      - { label: "Armour", value: "armour", color: "hsl(79, 95%, 90%)"}
      - { label: "Wondrous Item", value: "wondrous item", color: "hsl(261,93%,88%)"}
      - { label: "Weapon", value: "weapon", color: "hsl(231, 95%, 90%)"}
      - { label: "Consumable", value: "consumable", color: "hsl(0, 95%, 90%)"}
      - { label: "Treasure", value: "treasure", color: "hsl(274, 95%, 90%)"}
      - { label: "character", value: "character", color: "hsl(78, 95%, 90%)"}
      - { label: "personal", value: "personal", color: "hsl(268, 95%, 90%)"}
      - { label: "major", value: "major", color: "hsl(28, 95%, 90%)"}
      - { label: "faction", value: "faction", color: "hsl(137, 95%, 90%)"}
      - { label: "timeline", value: "timeline", color: "hsl(73, 95%, 90%)"}
      - { label: "location", value: "location", color: "hsl(215, 95%, 90%)"}
      - { label: "event", value: "event", color: "hsl(310, 95%, 90%)"}
      - { label: "info", value: "info", color: "hsl(140, 95%, 90%)"}
      - { label: "npc", value: "npc", color: "hsl(267, 95%, 90%)"}
      - { label: "beast", value: "beast", color: "hsl(260, 95%, 90%)"}
      - { label: "session", value: "session", color: "hsl(275, 95%, 90%)"}
      - { label: "armor", value: "armor", color: "hsl(272, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Attunement:
    input: checkbox
    accessorKey: Attunement
    key: Attunement
    id: Attunement
    label: A
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 8
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  location:
    input: text
    accessorKey: location
    key: location
    id: Claimant
    label: Claimant
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 69
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      custom_link_alias: location
  description:
    input: text
    accessorKey: description
    key: description
    id: Notes
    label: Description
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 456
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: true
      content_vertical_alignment: align-middle
      content_alignment: text-align-justify
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: Sunset-Fortune/Compendium
  row_templates_folder: Templates
  current_row_template: Templates/Item.md
  pagination_size: 10
  font_size: 12
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```
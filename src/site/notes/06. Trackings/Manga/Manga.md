---
{"dg-publish":true,"permalink":"/06-trackings/manga/manga/"}
---


```yaml:dbfolder
name: new database
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
    width: 285
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
      wrap_content: true
  __modified__:
    key: __modified__
    id: __modified__
    input: metadata_time
    label: Modified
    accessorKey: __modified__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    position: 10
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Cover:
    input: text
    accessorKey: Cover
    key: Cover
    id: Cover
    label: Cover
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 118
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Read_on:
    input: number
    accessorKey: Read_on
    key: Read_on
    id: Read_on
    label: Read on
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 37
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  English:
    input: select
    accessorKey: English
    key: English
    id: English
    label: Story
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "1. Trash", value: "Trash", color: "hsl(13, 95%, 90%)"}
      - { label: "2. Tedious", value: "Tedious", color: "hsl(319, 95%, 90%)"}
      - { label: "3. Blant", value: "Blant", color: "hsl(173, 95%, 90%)"}
      - { label: "4. Intriguing", value: "Intriguing", color: "hsl(227, 95%, 90%)"}
      - { label: "5. Entrancing", value: "Entrancing", color: "hsl(312, 95%, 90%)"}
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
  Drawing:
    input: select
    accessorKey: Drawing
    key: Drawing
    id: Drawing
    label: Drawing
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 123
    options:
      - { label: "3. Average", value: "Average", color: "hsl(108, 95%, 90%)"}
      - { label: "4. Good", value: "Good", color: "hsl(76, 95%, 90%)"}
      - { label: "1. Draft", value: "Draft", color: "hsl(172, 95%, 90%)"}
      - { label: "2. Below Ave", value: "Below Ave", color: "hsl(191, 95%, 90%)"}
      - { label: "5. Excellent", value: "Excellent", color: "hsl(211, 95%, 90%)"}
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
      wrap_content: true
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
  English_Ver.:
    input: text
    accessorKey: English_Ver.
    key: English_Ver.
    id: English_Ver.
    label: English Ver.
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
      wrap_content: true
  Chinese_Ver.:
    input: text
    accessorKey: Chinese_Ver.
    key: Chinese_Ver.
    id: Chinese_Ver.
    label: Chinese Ver.
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 132
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Comment:
    input: text
    accessorKey: Comment
    key: Comment
    id: Comment
    label: Comment
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Decision:
    input: select
    accessorKey: Decision
    key: Decision
    id: Decision
    label: Decision
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Following", value: "Following", color: "hsl(116,100%,50%)"}
      - { label: "Evaluating", value: "Evaluating", color: "hsl(58,61%,62%)"}
      - { label: "Dropped", value: "Dropped", color: "hsl(9,100%,95%)"}
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
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: true
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 100
  font_size: 16
  enable_js_formulas: true
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
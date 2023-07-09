---

database-plugin: basic

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
    position: 4
    isHidden: false
    sortIndex: 0
    isSorted: true
    isSortedDesc: true
    width: 194
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: true
  Money:
    input: number
    accessorKey: Money
    key: Money
    id: Money
    label: Money
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: -10
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: sum
      persist_changes: false
      footer_formula: 
  __tags__:
    key: __tags__
    id: __tags__
    input: metadata_tags
    label: File Tags
    accessorKey: __tags__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 7
    width: 133
    isHidden: true
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
  completed:
    input: text
    accessorKey: completed
    key: completed
    id: completed
    label: completed
    position: 10
    skipPersist: false
    isHidden: true
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
  title:
    input: text
    accessorKey: title
    key: title
    id: title
    label: title
    position: 5
    skipPersist: false
    isHidden: true
    sortIndex: -1
    width: 127
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  date:
    input: calendar
    accessorKey: date
    key: date
    id: Date
    label: Date
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 86
    isSorted: false
    isSortedDesc: true
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Status:
    input: tags
    accessorKey: Status
    key: Status
    id: Pay
    label: Status
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: -5
    options:
      - { label: "Today", value: "Today", color: "hsl(50,100%,50%)"}
      - { label: "Had", value: "Had", color: "hsl(228,100%,50%)"}
      - { label: "Paid", value: "Paid", color: "hsl(113,100%,50%)"}
      - { label: "Tmr", value: "Tmr", color: "hsl(187, 95%, 90%)"}
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
      content_alignment: text-align-left
      content_vertical_alignment: align-middle
      wrap_content: true
      footer_formula: 
  newColumn8:
    input: relation
    accessorKey: newColumn8
    key: newColumn8
    id: newColumn8
    label: New Column 8
    position: 11
    skipPersist: false
    isHidden: true
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
  __tasks__:
    key: __tasks__
    id: __tasks__
    input: task
    label: Task
    accessorKey: __tasks__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 6
    isHidden: false
    sortIndex: -1
    width: 533
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: false
      footer_type: none
      persist_changes: false
  startTime:
    input: calendar_time
    accessorKey: startTime
    key: startTime
    id: startTime
    label: startTime
    position: 12
    skipPersist: false
    isHidden: true
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
  Score:
    input: number
    accessorKey: Score
    key: Score
    id: Score
    label: Score
    position: 13
    skipPersist: false
    isHidden: true
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
config:
  remove_field_when_delete_column: false
  cell_size: wide
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: true
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: true
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 20
  font_size: 14
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: dd-MM-yyyy
  datetime_format: "dd-MM-yyyy HH:mm:ss"
  metadata_date_format: "dd-MM-yyyy HH:mm:ss"
  enable_footer: true
  implementation: default
filters:
  enabled: true
  conditions:
      - condition: AND
        disabled: true
        label: "Nikita"
        color: "hsl(241,98%,45%)"
        filters:
        - field: file.name
          operator: CONTAINS
          value: "Nikita"
          type: text
      - condition: AND
        disabled: true
        label: "Kirill"
        color: "hsl(126,96%,45%)"
        filters:
        - field: file.name
          operator: CONTAINS
          value: "Kirill"
          type: text
      - condition: AND
        disabled: true
        label: "Today"
        color: "hsl(197,91%,46%)"
        filters:
        - field: date
          operator: EQUAL
          value: "@today"
          type: calendar
      - condition: AND
        disabled: true
        label: "Tomorrow"
        color: "hsl(290,67%,55%)"
        filters:
        - field: date
          operator: EQUAL
          value: "@tomorrow"
          type: calendar
      - condition: AND
        disabled: true
        label: "Unpaid"
        color: "hsl(0,100%,50%)"
        filters:
        - field: Status
          operator: NOT_CONTAINS
          value: "Paid"
          type: tags
        - condition: OR
          disabled: false
          filters:
          - field: date
            operator: LESS_THAN
            value: "@today"
            type: calendar
      - condition: AND
        disabled: true
        label: "This week"
        color: "hsl(191,57%,45%)"
        filters:
        - field: date
          operator: GREATER_THAN_OR_EQUAL
          value: "@thisweek"
          type: calendar
        - field: date
          operator: LESS_THAN
          value: "@nextweek"
          type: calendar
      - condition: AND
        disabled: true
        label: "Last week"
        color: "hsl(219,100%,47%)"
        filters:
        - field: date
          operator: LESS_THAN
          value: "@thisweek"
          type: calendar
        - field: date
          operator: GREATER_THAN_OR_EQUAL
          value: "@lastweek"
          type: calendar
      - condition: AND
        disabled: true
        label: "Next week"
        color: "hsl(82, 95%, 90%)"
        filters:
        - field: date
          operator: GREATER_THAN_OR_EQUAL
          value: "@nextweek"
          type: calendar
      - condition: AND
        disabled: true
        label: "Kristina"
        color: "hsl(184,98%,50%)"
        filters:
        - field: title
          operator: CONTAINS
          value: "Kristina"
          type: text
      - condition: AND
        disabled: false
        label: "Sergey"
        color: "hsl(28,100%,49%)"
        filters:
        - field: title
          operator: CONTAINS
          value: "Sergey"
          type: text
```
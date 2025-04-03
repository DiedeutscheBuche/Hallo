menu_title: 'Default Menu'
open_command: menu
size: 9
open_requirement:
  requirements:
    permission:
      type: has permission
      permission: deluxemenus.admin
      deny_commands:
        - '[message] &cYou don''t have permission to do that!'
items:
  'dirt':
    material: DIRT
    slot: 0
  'grass':
    material: GRASS
    slot: 1
  'gravel':
    material: GRAVEL
    slot: 2
  'cobblestone':
    material: COBBLESTONE
    slot: 3
  'stone':
    material: STONE
    slot: 4
  'coal_ore':
    material: COAL_ORE
    slot: 5
  'iron_ore':
    material: IRON_ORE
    slot: 6
  'gold_ore':
    material: GOLD_ORE
    slot: 7
  'diamond_ore':
    material: DIAMOND_ORE
    slot: 8
    display_name: 'Exit'
    lore:
      - 'click to exit'
    left_click_commands:
      - '[close]'
    right_click_commands:
      - '[close]'

# Description

This function pack is an editable raycasting template. It allows you to run your desired commands when your targets look at entities, blocks or specific block faces.

# Usage Commands

- `/scoreboard objectives add rayLimit dummy`
    - This objective will be used to adjust how far you want the ray to travel from target's eyes.
- `/execute as <target> run function raycast/cast`
    - Initiate raycast from desired target.

## Editable Files

- `functions > raycast > on_hit > ray_limit.mcfuntion`
    - Commands in this file will run when there are no blocks or entities in target's line of sight & ray limit is reached. Using `@s` here will execute as the caster (target from whose sight the ray is being cast)
- `functions > raycast > on_hit > block.mcfuntion`
    - Commands in this file will run when target is looking at a block. Using `@s` here will execute as the caster (target from whose sight the ray is being cast)
- `functions > raycast > on_hit > entity.mcfuntion`
    - Commands in this file will run when target is looking at an entity. Using `@s` here will execute as the entity who was looked at, not the caster.

## Additional Files
- `on_hit/block_face`
- `on_hit/block_face/north`
- `on_hit/block_face/south`
- `on_hit/block_face/east`
- `on_hit/block_face/west`
- `on_hit/block_face/up`
- `on_hit/block_face/down`

Commands in these files will run when target is looking at any specific face of a block. Using `@s` here will execute as the caster (target from whose sight the ray is being cast)

# Pack Download
- **Without Additional Files:** <https://www.mediafire.com/file/2reow8ljg593csg/Raycasting+[F].mcpack/file>

- **With Additional Files:** <https://www.mediafire.com/file/mg5j6vd502h1fd2/Advanced+Raycasting+[F].mcpack/file>

# Creator

@|| MajestikButter ||#3362
https://github.com/MajestikButter/

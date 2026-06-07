# Generated Top-Down Pixel Sprite Sheets

These are top-down vertical-shooter sprite sheets intended for gameplay sprites.

## Files

- `teio-tannhauser-topdown-sheet.png`: transparent RGBA Teio Tannhauser player sheet.
- `mambo-hachimi-topdown-sheet.png`: transparent RGBA Mambo Hachimi player sheet.
- `enemy-boss-topdown-sheet.png`: transparent RGBA enemy and boss sheet.

The matching `source/` files preserve the original chroma-key generations before background removal.

## Usage Notes

- The generated sheets are best treated as source art for slicing into fixed-size frames.
- The player sheets were requested as 4 columns by 3 rows, but AI-generated spacing may need manual crop guides before using Phaser spritesheet slicing.
- Use top-down frames for gameplay. Keep the earlier portrait assets for character select and dialogue only.
